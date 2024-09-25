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
    class="bg-[#5F3E2B] w-full pt-[139px] pb-[81px] flex flex-col items-center gap-[121px] laptop:gap-[61px] tablet:gap-[61px]">
    <div
      class="flex gap-[128px] justify-center items-center laptop:flex-col tablet:flex-col laptop:gap-[40px] tablet:gap-[40px]">
      <div class="flex flex-col gap-[11px]">
        <img src="@/assets/img/logo.png" alt="logo" class="w-[224px]">
        <div class="text-center text-[18px] font-[300] text-white">295 7th Ave, Brooklyn, NY<br />11215</div>
      </div>
      <div class="flex flex-col gap-[24px] text-white text-center">
        <span class="font-[500] text-[24px]">HOURS</span>
        <div class="font-[300] text-[18px]">Monday-Friday<br />7:30AM - 8PM</div>
        <div class="font-[300] text-[18px]">Saturday - Sunday<br />9:30AM - 8PM</div>
      </div>
      <div class="flex flex-col items-center gap-[24px] text-white text-center">
        <span class="font-[500] text-[24px]">CONTACT</span>
        <div class="font-[300] text-[18px]">347-987-3954</div>
        <div class="mt-[24px] flex gap-[15px]">
          <a href="https://www.facebook.com/profile.php?id=61565750253296" target="_blank"><img src="@/assets/mobile-fb.svg" alt="fblogo" class="cursor-pointer"></a>
          <a href="https://www.instagram.com/brew_memories" target="_blank"><img src="@/assets/mobile-ig.svg" alt="iglogo" class="cursor-pointer"></a>
        </div>
      </div>
    </div>
    <span class="text-[15px] font-[300] text-white laptop:text-center tablet:text-center">@2024 Brew Memories. All Rights Reserved. x WAG Marketing</span>
  </div>
</template>
