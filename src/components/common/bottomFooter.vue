<script setup>
import { ref, onMounted, watch, computed, reactive } from 'vue'
import { useRouter } from 'vue-router'
const router = useRouter()
const routerData = reactive([
  { linkName: '关于ＷＡＧ', link: '/about' },
  { linkName: '服务项目', link: '/service' },
  { linkName: '成功案例', link: '/example' },
  { linkName: '营销博客', link: '/blog' },
  { linkName: '招聘资讯', link: '/info' },
  { linkName: '联系我们', link: '/contact' }
])
const info = reactive([
  '美国电话 ❘ +1 929-545-4470', '邮箱 ❘ contact@wag.marketing', '微信 ❘ wagmarketing', '小红书 | WAG品牌营销'
])
const emailContent = ref('')

</script>
<template>
  <div
    class="bg-[#000] w-full pt-[30px] pb-[30px] flex flex-col items-center gap-[20px] laptop:gap-[61px] tablet:gap-[61px] tablet:pt-[57px]">
    <div
      class="flex gap-[128px] justify-center items-start laptop:flex-col tablet:flex-col laptop:gap-[40px] tablet:gap-[20px] tablet:items-center">
      <div class="flex flex-col gap-[11px] tablet:items-center tablet:mb-[2rem]">
        <img src="@/assets/img/logo.png" alt="logo" class="w-[224px] tablet:w-[126px] tablet:mb-[1rem]">
        <div class="text-center text-[18px] font-[300] text-white teko tracking-widest">133-55 Roosevelt Ave 2nd
          fl,<br />Flushing, NY
          11354</div>
      </div>
      <div class="flex flex-col gap-[24px] text-white text-center mt-[30px]">
        <span class="font-[500] text-[24px] tablet:text-[20px] teko tracking-widest">HOURS</span>
        <div class="font-[300] text-[18px] tablet:text-[15px] teko tracking-widest">Monday-Saturday<br />12PM - 7PM
        </div>
        <div class="font-[300] text-[18px] tablet:text-[15px] teko tracking-widest">Sunday<br />12PM - 6PM</div>
      </div>
      <div class="flex flex-col items-center gap-[24px] text-white text-center tablet:gap-[1rem] mt-[30px]">
        <span class="font-[500] text-[24px] tablet:text-[20px] teko tracking-widest">CONTACT</span>
        <div class="font-[300] text-[18px] tablet:text-[15px] teko tracking-widest">646-379-9995</div>
        <div class="mt-[24px] flex gap-[15px]">
          <a href="https://www.facebook.com/tattoo7traintattoo" target="_blank"><img src="@/assets/icon/fb.svg"
              alt="fblogo" class="cursor-pointer"></a>
          <a href="https://www.instagram.com/7traintattoo?fbclid=IwY2xjawFewnFleHRuA2FlbQIxMAABHcqHI_FMkjR8IT1735B0pgXEXPciDt_1_Nv7LE-oRxTY9pZbu13gukhsLA_aem_TEbDG7cQC85uP7ejRtsa2Q"
            target="_blank"><img src="@/assets/icon/ig.svg" alt="iglogo" class="cursor-pointer"></a>
        </div>
      </div>
    </div>
    <span
      class="text-[13px] font-[300] text-[#8A8A8A] laptop:text-center tablet:text-center tablet:text-[12px] tablet:mx-[10%] teko tracking-widest whitespace-nowrap">@2024
      @2024 7 Train Tattoo Studio. All Rights Reserved. x WAG Marketing</span>
  </div>
</template>
<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Teko:wght@300..700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&family=Teachers:ital,wght@0,400..800;1,400..800&display=swap');

.teko {
  font-family: "Teko", sans-serif;
}

.noto {
  font-family: "Noto Sans", sans-serif;
}

.tea {
  font-family: "Teachers", sans-serif;
}

.pic {
  background-color: rgba(0, 0, 0, 0.7);
}

.p-example {
  &__body {
    background: #d4e735;
    overflow: hidden;
    color: #333;
  }

  &__splide {
    padding: 3rem 2rem;

    @media screen and (min-width: 768px) {
      padding: 4rem;
    }
  }
}
</style>
