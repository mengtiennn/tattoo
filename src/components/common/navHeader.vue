<script setup lang="ts">
import { ref, onMounted, watch, computed, reactive } from 'vue'
import { useRouter } from 'vue-router'
const router = useRouter()
const optionList = ref(['HOME', 'ABOUT', 'ARTISTS', 'GALLERY', 'CONTACT'])
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
  <div
    class="flex bg-white pt-[7px] pl-[90px] pr-[90px] pb-[7px] justify-center items-center laptop:justify-center tablet:justify-center laptop:pt-[10px] laptop:pb-[10px] tablet:pt-[10px] tablet:pb-[10px] fixed top-0 left-0 z-50 w-full tablet:px-[5%]">
    <div class="flex justify-between items-center w-full gap-[5rem] max-w-[1200px]">
      <div class="w-full flex justify-between items-center gap-[5rem] tablet:justify-center">
        <div class="flex items-center cursor-pointer" @click="router.push('/')">
          <img class="w-[59px] h-[59px] object-contain" src="@/assets/img/logo.png" alt="logo">
          <div class="whitespace-nowrap text-[20px] font-[400] tablet:text-[15px] teko">7 Train Tattoo Studio Inc</div>
        </div>
        <div class="flex gap-[32px] text-black laptop:hidden tablet:hidden text-[17px]">
          <div v-for="(link, idx) in optionList" :key="idx" @click="scrollTo(link)" class="cursor-pointer teko">{{ link
            }}</div>
        </div>
      </div>

      <div
        class="whitespace-nowrap tablet:hidden laptop:hidden text-white bg-[#000] font-[500] h-[32px] px-[24px] py-[6px] rounded-full cursor-pointer flex justify-center items-center">
        <a :href="'tel:646-379-9995'" class="text-[17px] teko">BOOK NOW: 646-379-9995</a>
      </div>
    </div>
    <!-- <img src="@/assets/img/menu.svg" class="absolute top-[16px] right-4 cursor-pointer desktop:hidden mac:hidden tablet:hidden" @click="showHamburger = true"> -->
    <img src="@/assets/img/menuWhite.svg" class="absolute top-[1.5rem] right-4 cursor-pointer desktop:hidden mac:hidden"
      @click="showHamburger = true">
  </div>
  <Transition name="slide-fade">
    <div class="w-full h-full fixed top-0 left-0 bg-white z-50 flex items-center pt-[75px] flex-col"
      v-if="showHamburger">
      <img src="@/assets/icon/close.svg" class="fixed top-[16px] right-4 cursor-pointer desktop:hidden"
        @click="showHamburger = false">
      <div class="flex gap-[24px] text-text-black flex-col items-center">
        <div v-for="(link, idx) in optionList" :key="idx" @click="scrollTo(link)" class="cursor-pointer teko">{{ link }}
        </div>
      </div>
    </div>
  </Transition>
</template>
<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Teko:wght@300..700&display=swap');

.teko {
  font-family: "Teko", sans-serif;
}
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
