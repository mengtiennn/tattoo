<template>
  <div class="desktop:pt-[119px] tablet:pt-86px]">
    <div id="HOME" class="h-[710px] mac:h-[679px] relative mac:pt-[109px] tablet:pt-[86px] tablet:h-full">
      <div class="w-full h-full tablet:hidden">
        <img class="w-full h-full object-cover" src="@/assets/img/banner.png" alt="">
        <div
          class="w-fit absolute text-white left-[10%] top-[25%] flex flex-col gap-2 items-center tablet:left-0 tablet:top-[10%]">
          <div class="text-[2rem] font-[700] tablet:w-[80%] tablet:text-center tablet:text-[32px] mb-[1.5rem] w-fit">
            7 TRAIN TATTOO STUDIO INC</div>
          <div class="flex flex-col tablet:text-center w-fit">
            <div class="text-[1.5rem] font-[400] tablet:text-[14px] w-fit">Ink Your Story, Wear Your Soul.</div>
          </div>
          <div class="desktop:hidden mac:hidden laptop:hidden w-[1px] h-[67px] bg-white my-[1.2rem]" />
          <div
            class="bg-white px-[22px] py-[1rem] my-[2.5rem] font-[500] text-black w-max cursor-pointer underline mobile:py-[8px]">
            <a :href="'tel:646-379-9995'">Call to book (646) 379-9995</a>
          </div>
          <div class="flex flex-col justify-center items-center text-[1.5rem] font-[400] mac:text-[1rem]">
            <div>133-55 Roosevelt Ave 2nd fl,</div>
            <div>Flushing, NY 11354</div>
          </div>
        </div>
      </div>
      <div class="hidden tablet:flex tablet:flex-col justify-center items-center bg-black text-white pt-[5rem]">
        <div class="text-[2rem] font-[700] tablet:w-[80%] tablet:text-center tablet:text-[32px] mb-[1.5rem] w-fit">
          7 TRAIN TATTOO STUDIO INC</div>
        <div class="flex flex-col tablet:text-center w-fit mb-[2rem]">
          <div class="text-[1.5rem] font-[400] tablet:text-[14px] w-fit">Ink Your Story, Wear Your Soul.</div>
        </div>
        <div
          class="bg-white px-[22px] py-[1rem] my-[2.5rem] font-[500] text-black w-max cursor-pointer underline mobile:py-[8px]">
          <a :href="'tel:646-379-9995'">Call to book (646) 379-9995</a>
        </div>
        <div class="flex flex-col justify-center items-center text-[1rem] font-[400]">
          <div>133-55 Roosevelt Ave 2nd fl,</div>
          <div>Flushing, NY 11354</div>
        </div>
        <img class="mt-[5.5rem] w-full" src="@/assets/img/bannerPhone.png" alt="">
      </div>
    </div>
    <div class="bg-[#EAEAEA] h-[5rem] flex items-center justify-center tablet:hidden">If you would like to schedule a
      tattoo consultation, please call (646) 379-9995.</div>
    <div id="ABOUT" class="px-[10%] flex py-[12rem] justify-evenly tablet:py-[109px] mac:py-[8rem]">
      <div class="w-[50%] flex flex-col justify-center items-center tablet:hidden">
        <div class="w-[405px] flex justify-center items-center">
          <img src="@/assets/img/aboutImg.png" alt="">
        </div>
      </div>
      <div class="w-[50%] flex flex-col items-center tablet:hidden">
        <div class="flex flex-col items-center justify-center text-[2rem] font-[400] mb-[2rem]">
          <div>SERVICE BEYOND </div>
          <div>EXPECTATION</div>
        </div>
        <div class="w-full">
          7号铁刺青(7 Train Tattoo )专业纹身-穿孔。由多次获得“纽约国际纹身博览会”大奖的
          Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。我们的纹身师们具备丰富的创意和技术，可以为你实现各种纹身设计。我们擅长新/日传统纹身
          (Neotraditional tattoo/Traditionaltattoo)，日式纹身(Japanesetattoo)欧美写实纹身(Realistic tattoo),细线纹身(Fine line
          tattoo)，肖像纹身，美式(Old School)纹身，纹身覆盖等等。
          欢迎咨询:646-379-9995
          地址:133-55 Roosevelt Ave,2ndfloor, Flushing,NY 11354(纽约法拉盛)
          7 Train Tattoo - Professional Tattoo & Piercing Studio. Led by award-winning artist Mr. Ricky, a multiple-time
          winner at the New York International Tattoo Expo, our team of skilled tattoo artists is dedicated to providing
          a top-quality tattoo experience with a focus on hygiene and safety. We take the time to listen to your ideas
          and needs, working closely with you to create unique and stunning tattoo pieces. Our expertise includes
          Neo-traditional and Traditional tattoos, Japanese tattoos, Realistic tattoos, Fine line tattoos, Portrait
          tattoos, Old School tattoos, and tattoo cover-ups.
        </div>
      </div>
      <div class="desktop:hidden mac:hidden laptop:hidden flex flex-col justify-center items-center">
        <div class="text-[36px] font-[700] mb-[14px] whitespace-nowrap text-center">SERVICE BEYOND <br>EXPECTATION
        </div>
        <div class="text-[14px] font-[400] leading-[20px]">
          7号铁刺青(7 Train Tattoo )专业纹身-穿孔。由多次获得“纽约国际纹身博览会”大奖的
          Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。我们的纹身师们具备丰富的创意和技术，可以为你实现各种纹身设计。我们擅长新/日传统纹身
          (Neotraditional tattoo/Traditionaltattoo)，日式纹身(Japanesetattoo)欧美写实纹身(Realistic tattoo),细线纹身(Fine line
          tattoo)，肖像纹身，美式(Old School)纹身，纹身覆盖等等。
        </div>
        <div class="text-center">欢迎咨询:646-379-9995</div>
        <div class="text-center mb-[2rem]">地址:133-55 Roosevelt Ave,2ndfloor, Flushing,NY 11354(纽约法拉盛)</div>
        <div>
          7 Train Tattoo - Professional Tattoo & Piercing Studio. Led by award-winning artist Mr. Ricky, a multiple-time
          winner at the New York International Tattoo Expo, our team of skilled tattoo artists is dedicated to providing
          a top-quality tattoo experience with a focus on hygiene and safety. We take the time to listen to your ideas
          and needs, working closely with you to create unique and stunning tattoo pieces. Our expertise includes
          Neo-traditional and Traditional tattoos, Japanese tattoos, Realistic tattoos, Fine line tattoos, Portrait
          tattoos, Old School tattoos, and tattoo cover-ups.
        </div>
        <img class="mt-[4rem]" src="@/assets/img/aboutImgPhone.png" alt="">
      </div>
    </div>
    <!-- 刺青師介紹電腦版 -->
    <div class="px-[90px] mb-[119px] laptop:hidden tablet:hidden">
      <div class="w-full bg-[#EAEAEA] py-[105px] flex items-center gap-[8vw] px-[150px] justify-between">
        <div class="flex flex-col items-center gap-[13px]">
          <span class="teko font-[500] text-[36px] mac:text-[24px]">Ricky Chen</span>
          <img class="w-[489px]" src="@/assets/img/ricky.png" alt="contact">
          <div class="w-[453px] text-[20px] font-[400] text-center mac:text-[15px]">多次获得“纽约国际纹身博览会”大奖的
            Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。
            Award-winning tattoo artist Mr. Ricky, renowned for his multiple accolades at the New York International
            Tattoo Expo.</div>
        </div>
        <div class="flex flex-wrap gap-[26px]">
          <img :src="getAssetsImgFile('r', `r${r}.png`)" alt="" v-for="r in 9" @click="show('r', r)">
        </div>
      </div>
    </div>
    <div class="px-[90px] mb-[119px] laptop:hidden tablet:hidden">
      <div class="w-full bg-[#EAEAEA] py-[105px] flex items-center gap-[8vw] px-[150px] justify-between">
        <div class="flex flex-wrap gap-[26px]">
          <img :src="getAssetsImgFile('d', `d${d}.png`)" alt="" v-for="d in 9" @click="show2('d', d)">
        </div>
        <div class="flex flex-col items-center gap-[13px]">
          <span class="teko font-[500] text-[36px] mac:text-[24px]">Danny</span>
          <img class="w-[489px]" src="@/assets/img/danny.png" alt="contact">
          <div class="w-[453px] text-[20px] font-[400] text-center mac:text-[15px]">Danny
            师傅从小喜欢艺术，现在已经是有多年年经验的纹身师。擅长亚洲风格，中国水彩纹身，
            细线纹身，细小纹身等等。他讲究细节，构图精致，都能体现他的坚实的艺术基础。
            Master Danny has loved art since he was a child, and now he is a tattoo artist with many years of
            experience. He is good at Asian style, Chinese watercolor tattoos, fine line tattoos, small tattoos, etc.
            His attention to details and his composition is exquisite, which can reflect his solid artistic foundation.
          </div>
        </div>
      </div>
    </div>
    <div class="px-[90px] laptop:hidden tablet:hidden">
      <div class="w-full bg-[#EAEAEA] px-[252px] flex items-center h-[905px]">
        <div class="flex flex-col items-center gap-[13px]">
          <span class="teko font-[500] text-[36px] mac:text-[24px]">Kimberly</span>
          <img src="@/assets/img/kimberly.png" alt="contact">
        </div>
      </div>
    </div>
    <!-- 刺青師介紹 手機版 -->
    <div
      class="destop:hidden mac:hidden flex flex-col bg-[#EAEAEA] pt-[84px] pb-[106px] px-[30px] justify-center mb-[54px]">
      <div class="flex flex-col items-center gap-[18px]">
        <span class="teko font-[500] text-[36px] mac:text-[24px]">Ricky Chen</span>
        <img src="@/assets/img/ricky.png" alt="contact">
        <div class="text-[14px] text-center">Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。
          Award-winning tattoo artist Mr. Ricky, renowned for his multiple accolades at the New York International
          Tattoo Expo.</div>
      </div>
      <div class="flex flex-wrap gap-x-[30px] gap-y-[17px] justify-center mt-[53px]">
        <img class="w-[30vw]" :src="getAssetsImgFile('rm', `r${r}.png`)" alt="" v-for="r in 8">
      </div>
    </div>
    <div
      class="destop:hidden mac:hidden flex flex-col bg-[#EAEAEA] pt-[84px] pb-[106px] px-[30px] justify-center mb-[54px]">
      <div class="flex flex-col items-center gap-[18px]">
        <span class="teko font-[500] text-[36px] mac:text-[24px]">Danny</span>
        <img src="@/assets/img/danny.png" alt="contact">
        <div class="text-[14px] text-center">Danny 师傅从小喜欢艺术，现在已经是有多年年经验的纹身师。擅长亚洲风格，中国水彩纹身，
          细线纹身，细小纹身等等。他讲究细节，构图精致，都能体现他的坚实的艺术基础。
          Master Danny has loved art since he was a child, and now he is a tattoo artist with many years of experience.
          He is good at Asian style, Chinese watercolor tattoos, fine line tattoos, small tattoos, etc. His attention to
          details and his composition is exquisite, which can reflect his solid artistic foundation.</div>
      </div>
      <div class="flex flex-wrap gap-x-[30px] gap-y-[17px] justify-center mt-[53px]">
        <img class="w-[30vw]" :src="getAssetsImgFile('d', `d${r}.png`)" alt="" v-for="r in 8">
      </div>
    </div>
    <div class="destop:hidden mac:hidden flex bg-[#EAEAEA] pt-[84px] pb-[106px] justify-center">
      <div class="flex flex-col items-center gap-[18px]">
        <span class="teko font-[500] text-[36px] mac:text-[24px]">Kimberly</span>
        <img src="@/assets/img/kimberly.png" alt="contact">
      </div>
    </div>
    <!-- contact 電腦版 -->
    <div class="w-full flex justify-center items-center py-[247px] laptop:hidden tablet:hidden">
      <div class="w-fit h-fit relative">
        <img src="@/assets/img/contact.png" alt="contact">
        <div class="flex flex-col absolute right-[90px] top-[50%] translate-y-[-45%] justify-between gap-[8px]">
          <div class="flex flex-col gap-[4px] items-center">
            <span class="text-[36px] font-[400] text-white teko mac:text-[24px]">CONTACT</span>
            <span class="text-[24px] font-[300] text-white teko mac:text-[15px]">(646) 379-9995</span>
          </div>
          <div class="flex flex-col gap-[4px] items-center">
            <span class="text-[36px] font-[400] text-white teko mac:text-[24px]">LOCATION</span>
            <span class="text-[24px] font-[300] text-white teko text-center mac:text-[15px]">133-55 Roosevelt
              Ave<br />2nd fl, Flushing,
              NY
              11354</span>
          </div>
          <div class="flex flex-col gap-[4px] items-center">
            <span class="text-[36px] font-[400] text-white teko mac:text-[24px]">HOURS OF OPERATION</span>
            <span class="text-[24px] font-[300] text-white teko mac:text-[15px]">Mon - Sat --------- 12AM - 7PM</span>
            <span class="text-[24px] font-[300] text-white teko mac:text-[15px]">Sunday --------- 12AM - 6PM</span>
          </div>
        </div>
      </div>
    </div>
    <!-- contact 手機版 -->
    <div
      class="destop:hidden mac:hidden flex bg-[#292929] w-full pt-[191px] pb-[100px] justify-center relative mt-[200px] mb-[75px]">
      <img src="@/assets/img/mcontact.png" alt="" class="absolute top-[-100px]">
      <div class="flex flex-col justify-between gap-[46px]">
        <div class="flex flex-col gap-[4px] items-center">
          <span class="text-[15px] font-[400] text-white teko">CONTACT</span>
          <span class="text-[15px] font-[300] text-white teko">(646) 379-9995</span>
        </div>
        <div class="flex flex-col gap-[4px] items-center">
          <span class="text-[15px] font-[400] text-white teko">LOCATION</span>
          <span class="text-[15px] font-[300] text-white teko text-center">133-55 Roosevelt
            Ave<br />2nd fl, Flushing,
            NY
            11354</span>
        </div>
        <div class="flex flex-col gap-[4px] items-center">
          <span class="text-[15px] font-[400] text-white teko">HOURS OF OPERATION</span>
          <span class="text-[15px] font-[300] text-white teko">Mon - Sat --------- 12AM - 7PM</span>
          <span class="text-[15px] font-[300] text-white teko">Sunday --------- 12AM - 6PM</span>
        </div>
      </div>
    </div>
    <div id="CONTACT" class="mx-[20%] flex flex-col justify-center items-center">
      <div
        class="text-[2rem] mac:text-[1.5rem] font-[500] tablet:leading-[2rem] tablet:text-[1.5rem] tablet:text-center">7
        Train Tattoo Studio– Professional Tattooing and Piercing</div>
      <div class="text-[1.5rem] mac:text-[1rem] font-[400] text-center my-[2rem] tablet:text-[1rem]">
        Led by award-winning tattoo artist Ricky, who has won multiple honors at the New York International Tattoo Expo,
        our team is dedicated to providing you with a high-quality tattoo experience in a safe and hygienic environment.
        We listen carefully to your ideas and work with you to create a unique, stunning tattoo.
      </div>
      <div class="text-[1.5rem] mac:text-[1rem] font-[400] my-[2rem] text-center tablet:text-[1rem]">
        Our artists are skilled in a variety of styles, including Neo-traditional, Traditional, Japanese, Realistic,
        Fine Line, Portrait, Old School, and cover-up tattoos. Danny, another highly experienced artist on our team,
        specializes in Asian styles, Chinese watercolor, fine line, and small tattoos, with a keen eye for detail and
        refined compositions.
      </div>
      <div class="text-[1.5rem] mac:text-[1rem] font-[600] tablet:text-[1rem]">Book your appointment today! </div>
      <div class="text-[1.5rem] mac:text-[1rem] font-[600] tablet:text-[1rem]">Call (646) 379-9995 for consultation.
      </div>
    </div>
    <div class="flex justify-center items-center gap-[2rem] my-[10rem] tablet:flex-col tablet:my-[5rem]">
      <img src="@/assets/img/contactImg1.png" alt="">
      <img src="@/assets/img/contactImg2.png" alt="">
      <img src="@/assets/img/contactImg3.png" alt="">
    </div>
  </div>
  <div
    class="w-[53px] h-[53px] bg-[#D9D9D9] rounded-full fixed bottom-[24px] right-[20px] flex justify-center items-center">
    <img src="@/assets/icon/arrow.svg" alt="arrow" class="w-[40px] rotate-90" @click="goToTop()">
  </div>
  <div class="fixed top-0 left-0 w-screen h-screen flex items-center justify-center pic z-[1000]" v-if="showBigPhoto">
    <div class="absolute right-10 top-5 text-xl font-semibold z-20 text-white cursor-pointer"
      @click="showBigPhoto = false">CLOSE</div>
    <img src="@/assets/img/ca.png"
      class="rotate-180 w-[50px] absolute top-[50%] left-[20%] translate-y-[-50%] cursor-pointer" v-if="nowIndex > 1"
      @click="changePicIndex('back')">
    <img :src="nowPic" class="w-[70vw] h-[80vh] object-contain">
    <img src="@/assets/img/ca.png" class="w-[50px] absolute top-[50%] right-[20%] translate-y-[-50%] cursor-pointer"
      v-if="nowIndex < 9" @click="changePicIndex('go')">
  </div>
  <div class="fixed top-0 left-0 w-screen h-screen flex items-center justify-center pic z-[1000]" v-if="showBigPhoto2">
    <div class="absolute right-10 top-5 text-xl font-semibold z-20 text-white cursor-pointer"
      @click="showBigPhoto2 = false">CLOSE</div>
    <img src="@/assets/img/ca.png"
      class="rotate-180 w-[50px] absolute top-[50%] left-[20%] translate-y-[-50%] cursor-pointer" v-if="nowIndex2 > 1"
      @click="changePicIndex2('back')">
    <img :src="nowPic2" class="w-[70vw] h-[80vh] object-contain">
    <img src="@/assets/img/ca.png" class="w-[50px] absolute top-[50%] right-[20%] translate-y-[-50%] cursor-pointer"
      v-if="nowIndex2 < 9" @click="changePicIndex2('go')">
  </div>
</template>

<script setup>
import { ref, computed } from 'vue'
import { getAssetsImgFile } from '../utils/commonUse'
const content = ref(null)
const menu1List = ref(['COFFEE', 'SPECIALTY LATTE', 'FRIZZY SPARKLING & SLUSH', 'FRESH FRUIT  TEA'])
const menu2List = ref(['SPECIAL SMOOTHIE', 'LEMONADE', 'FOOD'])
const orderUrl = ref('https://order.mealkeyway.com/customer/release/index?mid=45774946684268454942534476706e424837583342773d3d#/main')

const goUrl = (url) => {
  if(!url){
    url = orderUrl.value
  }
  window.open(url, '_blank');
}

const goToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: "smooth"
  })
}
const showBigPhoto = ref(false)
const showBigPhoto2 = ref(false)
const nowIndex = ref(0)
const nowPic = computed(() => {
  return getAssetsImgFile('r', `r${nowIndex.value}.png`)
})
const nowIndex2 = ref(0)
const nowPic2 = computed(() => {
  return getAssetsImgFile('d', `d${nowIndex2.value}.png`)
})
const show = (type, idx) => {
  showBigPhoto.value = true
  nowIndex.value = idx
}
const show2 = (type, idx) => {
  console.log(idx)
  showBigPhoto2.value = true
  nowIndex2.value = idx
}
const changePicIndex = (type) => {
  type == 'back' ? nowIndex.value -= 1 : nowIndex.value += 1
}
const changePicIndex2 = (type) => {
  type == 'back' ? nowIndex2.value -= 1 : nowIndex2.value += 1
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Teko:wght@300..700&display=swap');
.teko {
  font-family: "Teko", sans-serif;
}
.pic {
  background-color: rgba(0, 0, 0, 0.7);
}
</style>