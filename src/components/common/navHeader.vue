<script setup lang="ts">
import { ref, onMounted, watch, computed, reactive } from 'vue'
import { useRouter } from 'vue-router'
const router = useRouter()
const optionList = ref(['HOME', 'ABOUT', 'MENU', 'GALLERY', 'CONTACT US'])
const showHamburger = ref(false)
const menuShow = ref<boolean>(false)
const scrollTo = (id:string) => {
  if(menuShow.value){
    menuShow.value = false
  }
  const element = document.getElementById(id)
  showHamburger.value = false
  console.log(element)
  if(element){
    const elementPosition = element.getBoundingClientRect().top;
    const offsetPosition = elementPosition + window.pageYOffset - 95;
    window.scrollTo({
      top: offsetPosition,
      behavior: 'smooth'
    });
  }
}
const orderUrl = ref<string>('https://order.mealkeyway.com/customer/release/index?mid=45774946684268454942534476706e424837583342773d3d#/main')

const goUrl = (url?: string) => {
  if(!url){
    url = orderUrl.value
  }
  window.open(url, '_blank');
}
</script>
<template>
  <div class="flex bg-white pt-[22px] pl-[90px] pr-[90px] pb-[22px] justify-center items-center laptop:justify-center tablet:justify-center laptop:pt-[10px] laptop:pb-[10px] tablet:pt-[10px] tablet:pb-[10px] fixed top-0 left-0 z-50 w-full">
    <div class="flex justify-center items-center w-full desktop:max-w-[1000px] gap-[8rem]">
      <div class="flex items-center gap-[8rem]">
        <div class="flex items-end cursor-pointer" @click="router.push('/')">
          <img class="w-[127px] h-[75px] object-cover" src="@/assets/img/logo.png" alt="logo">
        </div>
        <div class="flex gap-[32px] text-black laptop:hidden tablet:hidden text-[15px]">
          <div v-for="(link, idx) in optionList" :key="idx" @click="scrollTo(link)" class="cursor-pointer">{{ link }}</div>
        </div>
      </div>
      <div class="tablet:hidden laptop:hidden text-white bg-[#4B3426] font-[500] px-[18px] py-[12px] rounded-full underline cursor-pointer" @click="goUrl()">Oder Pickup</div>
    </div>
    <!-- <img src="@/assets/img/menu.svg" class="absolute top-[16px] right-4 cursor-pointer desktop:hidden mac:hidden tablet:hidden" @click="showHamburger = true"> -->
    <img src="@/assets/img/menuWhite.svg" class="absolute top-[32px] right-4 cursor-pointer desktop:hidden mac:hidden" @click="showHamburger = true">
  </div>
  <Transition name="slide-fade">
    <div class="w-full h-full fixed top-0 left-0 bg-white z-50 flex items-center pt-[75px] flex-col" v-if="showHamburger">
      <img src="@/assets/img/close.svg" class="fixed top-[16px] right-4 cursor-pointer desktop:hidden" @click="showHamburger = false">
      <div class="flex gap-[24px] text-text-black flex-col items-center">
        <div v-for="(link, idx) in optionList" :key="idx" @click="scrollTo(link)" class="cursor-pointer">{{ link }}</div>
      </div>
    </div>
  </Transition>
</template>
<style lang="scss" scoped>
.slide-fade-enter-active {
  transition: all 0.3s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.3s ease-out;
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateX(20px);
  opacity: 0;
}
</style>
