<template>
  <div class="desktop:pt-[72px] tablet:pt-[72px]">
    <div id="HOME" class="h-[710px] mac:h-[667px] relative mac:pt-[72px] tablet:pt-[0px] tablet:h-full">
      <div class="w-full h-full tablet:hidden px-[78px]">
        <img class="w-full h-full object-cover object-top" src="@/assets/img/banner.png" alt="">
        <div
          class="w-fit absolute text-white left-[calc(17.5%)] top-[calc(50%-100px)] flex flex-col items-center tablet:left-0 tablet:top-[10%]">
          <div class="text-[48px] font-[400] tablet:w-[80%] tablet:text-center tablet:text-[32px] w-fit teko">
            7 TRAIN TATTOO STUDIO INC</div>
          <div class="flex flex-col tablet:text-center w-fit">
            <div class="text-[24px] font-[300] tablet:text-[14px] w-fit teko">Ink Your Story, Wear Your Soul.</div>
          </div>
          <div class="desktop:hidden mac:hidden laptop:hidden w-[1px] h-[67px] bg-white my-[1.2rem]" />
          <div
            class="bg-white px-[22px] text-[20px] py-[7px] font-[400] my-[1rem] text-black w-max cursor-pointer mobile:py-[8px] teko rounded-[20px]">
            <a :href="'tel:646-379-9995'">Call to book (646) 379-9995</a>
          </div>
          <div class="flex flex-col justify-center items-center text-[20px] font-[300] mac:text-[1rem]">
            <div class="teko tracking-widest">133-55 Roosevelt Ave 2nd fl, Flushing, NY 11354</div>
          </div>
        </div>
        <div class="bg-[#EAEAEA] h-[5rem] flex items-center justify-center tablet:hidden tea">If you would like
          to schedule
          a
          tattoo consultation, please call (646) 379-9995.</div>
      </div>
      <div class="hidden tablet:flex tablet:flex-col justify-center items-center bg-black text-white">
        <div class="my-[64px] flex flex-col justify-center items-center">
          <div class="text-[36px] font-[400] tracking-wide tablet:w-[80%] tablet:text-center w-fit teko">
            7 TRAIN TATTOO <br> STUDIO INC</div>
          <!-- <div class="flex flex-col tablet:text-center w-fit mb-[2rem]">
            <div class="text-[1.5rem] font-[400] tablet:text-[14px] w-fit teko">Ink Your Story, Wear Your Soul.</div>
          </div> -->
          <div
            class="text-white px-[22px] py-[1rem] my-[2.5rem] font-[400] text-[18px] w-max cursor-pointer mobile:py-[8px] teko rounded-[20px] tablet:my-[0.5rem]"
            style="border: 1px solid white">
            <a :href="'tel:646-379-9995'" class="tracking-wide">Call to book (646) 379-9995</a>
          </div>
          <div class="flex flex-col justify-center items-center text-[14px] font-[400]">
            <div class="tea">133-55 Roosevelt Ave 2nd fl,Flushing, NY 11354</div>
          </div>
        </div>
        <img class="w-full" src="@/assets/img/bannerPhone.png" alt="">
      </div>
    </div>
    <div id="ABOUT" class="px-[10%] flex py-[12rem] justify-evenly tablet:py-[109px] mac:py-[8rem]">
      <div class="w-[50%] flex flex-col justify-center items-center tablet:hidden">
        <div class="w-[405px] flex justify-center items-center">
          <img src="@/assets/img/aboutImg.png" alt="">
        </div>
      </div>
      <div class="w-[50%] flex flex-col items-center tablet:hidden">
        <div class="flex flex-col items-center justify-center text-[48px] font-[400] mb-[2rem]">
          <div class="teko">SERVICE BEYOND </div>
          <div class="teko mt-[-20px]">EXPECTATION</div>
        </div>
        <div class="w-[90%]">
          <div class="noto text-[#636262] text-center">
            7号铁刺青(7 Train Tattoo )专业纹身-穿孔。由多次获得“纽约国际纹身博览会”大奖的
            Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。我们的纹身师们具备丰富的创意和技术，可以为你实现各种纹身设计。我们擅长新/日传统纹身
            (Neotraditional tattoo/Traditionaltattoo)，日式纹身(Japanesetattoo)欧美写实纹身(Realistic tattoo),细线纹身(Fine line
            tattoo)，肖像纹身，美式(Old School)纹身，纹身覆盖等等。<br /><br />
            欢迎咨询:646-379-9995<br />
            地址:133-55 Roosevelt Ave,2ndfloor, Flushing,NY 11354(纽约法拉盛)
          </div>
          <div class="tea text-[#636262] mt-[16px] text-center">
            7 Train Tattoo - Professional Tattoo & Piercing Studio. Led by award-winning artist Mr. Ricky, a
            multiple-time
            winner at the New York International Tattoo Expo, our team of skilled tattoo artists is dedicated to
            providing
            a top-quality tattoo experience with a focus on hygiene and safety. We take the time to listen to your ideas
            and needs, working closely with you to create unique and stunning tattoo pieces. Our expertise includes
            Neo-traditional and Traditional tattoos, Japanese tattoos, Realistic tattoos, Fine line tattoos, Portrait
            tattoos, Old School tattoos, and tattoo cover-ups.
          </div>
        </div>
      </div>
      <div class="desktop:hidden mac:hidden laptop:hidden flex flex-col justify-center items-center">
        <div class="text-[36px] font-[400] mb-[14px] whitespace-nowrap text-center teko">SERVICE BEYOND<br />EXPECTATION
        </div>
        <div class="text-[14px] font-[400] leading-[20px] noto text-[#636262] text-center w-[85%]">
          7号铁刺青(7 Train Tattoo )专业纹身-穿孔。由多次获得“纽约国际纹身博览会”大奖的
          Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。我们的纹身师们具备丰富的创意和技术，可以为你实现各种纹身设计。我们擅长新/日传统纹身
          (Neotraditional tattoo/Traditionaltattoo)，日式纹身(Japanesetattoo)欧美写实纹身(Realistic tattoo),细线纹身(Fine line
          tattoo)，肖像纹身，美式(Old School)纹身，纹身覆盖等等。
        </div>
        <div class="text-center noto text-[#636262] mt-[8px]">欢迎咨询:646-379-9995</div>
        <div class="text-center mb-[2rem] noto text-[#636262]">地址:133-55 Roosevelt Ave,2ndfloor, Flushing,NY
          11354(纽约法拉盛)</div>
        <div class="text-[#636262] font-[400] text-center w-[85%] tea">
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
    <div
      class="w-full text-center text-black text-[40px] teko font-[500] mb-[35px] laptop:text-[36px] tablet:text-[36px]">
      Artist & Showcase</div>
    <div class="px-[90px] mb-[119px] laptop:hidden tablet:hidden">
      <div class="w-full bg-[#EAEAEA] py-[70px] flex flex-col items-center gap-[8vw] px-[60px] justify-between">
        <div class="flex w-full gap-[45px] items-center justify-center">
          <div class="flex flex-col gap-[16px] w-[30%] items-center">
            <span class="teko font-[500] text-[32px]">Ricky Chen</span>
            <img class="w-[277px]" src="@/assets/img/ricky.png" alt="contact">
          </div>
          <div class="w-[45%] flex flex-col gap-[10px]">
            <span
              class="noto text-[15px] font-[400] text-center">Ricky先生曾经是中国青年艺术家，多次获过全国及国际书画艺术大奖，2015年还在华盛顿国会山庄获过艺术成就奖，并由国会议员、参众两院财政委员会主席：卡罗林-玛罗尼亲自颁奖。后来改行做为纹身艺术家，纹身作品又在纽约国际纹身博览会中多次获过纹身一等奖、二等奖、三等奖等等。
              擅长亚洲风格、写实风格、彩色黑白等等。他的独特构图和错综复杂的细节使得纹身作品与众不同，无论是从近看还是远观。
            </span>
            <br />
            <span class="tea text-[15px] font-[400] text-center">
              Mr. Ricky was once a prominent young Chinese artist celebrated for his exceptional calligraphy and
              painting
              skills, winning numerous national and international awards. In 2015, he received an Artistic Achievement
              Award
              at Capitol Hill in Washington, D.C., presented by Congresswoman Carolyn Maloney, highlighting his impact
              on
              the art community.
              Later, he transitioned to tattoo artistry, quickly gaining recognition for his work at the New York
              International Tattoo Expo, where he won multiple first, second, and third prizes. Mr. Ricky excels in
              various
              styles, including Asian, realistic, and both colored and black-and-white tattoos. His unique compositions
              and
              intricate details make his tattoos stand out, inviting admiration from both close up and afar. His journey
              reflects a remarkable evolution in his artistic expression, merging traditional techniques with modern
              aesthetics.
            </span>
          </div>
        </div>
        <div class="w-[65%] px-[40px]">
          <Carousel :snapAlign="'center'" :breakpoints="breakpoints" :wrapAround="true">
            <Slide v-for="r in 9" :key="r">
              <div class="carousel__item" @click="show('r', r)">
                <!-- <img :src="getAssetsFile(`carousel/c${slide}.png`)"
                  class="w-[220px] h-[281px] object-cover cursor-pointer"> -->
                <img :src="getAssetsImgFile('r', `r${r}.png`)" alt="" class="h-[157px] object-contain">
              </div>
            </Slide>
            <template #addons>
              <Navigation />
            </template>
          </Carousel>
        </div>
        <!-- <div class="flex flex-col items-center gap-[13px]">
          <span class="teko font-[500] text-[36px] mac:text-[24px] teko">Ricky Chen</span>
          <img class="w-[489px]" src="@/assets/img/ricky.png" alt="contact">
          <div class="w-[453px] text-[20px] font-[400] text-center mac:text-[15px] teko">多次获得“纽约国际纹身博览会”大奖的
            Ricky先生主导的纹身师团队。我们注重卫生和安全，为您提供高品质的纹身体验。我们会认真倾听你的想法和需求，并与你合作创作出独特而精美的纹身作品。
            Award-winning tattoo artist Mr. Ricky, renowned for his multiple accolades at the New York International
            Tattoo Expo.</div>
        </div>
        <div class="flex flex-wrap gap-[26px]">
          <img :src="getAssetsImgFile('r', `r${r}.png`)" alt="" v-for="r in 9" @click="show('r', r)">
        </div> -->
      </div>
    </div>
    <div class="px-[90px] mb-[119px] laptop:hidden tablet:hidden">
      <div class="w-full bg-[#EAEAEA] py-[70px] flex flex-col items-center gap-[8vw] px-[60px] justify-between">
        <div class="flex w-[70%] gap-[45px] items-center justify-center">
          <div class="w-[55%] flex flex-col gap-[10px]">
            <span class="noto text-[15px] font-[400] text-center">Danny 师傅从小喜欢艺术，现在已经是有多年年经验的纹身师。擅长亚洲风格，中国水彩纹身，
              细线纹身，细小纹身等等。他讲究细节，构图精致，都能体现他的坚实的艺术基础。
            </span>
            <br />
            <span class="tea text-[15px] font-[400] text-center">
              Master Danny has loved art since he was a child, and now he is a tattoo artist with many years of
              experience. He is good at Asian style, Chinese watercolor tattoos, fine line tattoos, small tattoos, etc.
              His attention to details and his composition is exquisite, which can reflect his solid artistic
              foundation.
            </span>
          </div>
          <div class="flex flex-col gap-[16px] w-[30%] items-center">
            <span class="teko font-[500] text-[32px]">Danny</span>
            <img class="w-[232px]" src="@/assets/img/danny.png" alt="contact">
          </div>
        </div>
        <div class="w-[65%] px-[40px]">
          <Carousel :snapAlign="'center'" :breakpoints="breakpoints" :wrapAround="true">
            <Slide v-for="d in 9" :key="d">
              <div class="carousel__item" @click="show2('d', d)">
                <!-- <img :src="getAssetsFile(`carousel/c${slide}.png`)"
                  class="w-[220px] h-[281px] object-cover cursor-pointer"> -->
                <img :src="getAssetsImgFile('d', `d${d}.png`)" alt="" class="h-[161px]">
              </div>
            </Slide>
            <template #addons>
              <Navigation />
            </template>
          </Carousel>
        </div>
        <!-- <div class="flex flex-wrap gap-[26px]">
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
        </div> -->
      </div>
    </div>
    <div class="px-[90px] laptop:hidden tablet:hidden">
      <div class="w-full bg-[#EAEAEA] px-[252px] flex items-center h-[905px]">
        <div class="flex flex-col items-center gap-[13px]">
          <span class="teko font-[500] text-[36px] mac:text-[24px]">Kimberly</span>
          <img src="@/assets/img/kimberly.png" alt="contact" class="w-[266px]">
        </div>
      </div>
    </div>
    <!-- 刺青師介紹 手機版 -->
    <div
      class="hidden laptop:flex tablet:flex flex-col bg-[#EAEAEA] pt-[84px] pb-[106px] px-[30px] justify-center mb-[54px]">
      <div class="flex flex-col items-center gap-[18px]">
        <span class="teko font-[400] text-[24px] mac:text-[24px]">Ricky Chen</span>
        <img src="@/assets/img/ricky.png" alt="contact" class="w-[80%]">
        <div class="text-[14px] teko flex flex-col gap-[5px] w-[80%]">
          <span
            class="noto">Ricky先生曾经是中国青年艺术家，多次获过全国及国际书画艺术大奖，2015年还在华盛顿国会山庄获过艺术成就奖，并由国会议员、参众两院财政委员会主席：卡罗林-玛罗尼亲自颁奖。后来改行做为纹身艺术家，纹身作品又在纽约国际纹身博览会中多次获过纹身一等奖、二等奖、三等奖等等。
            擅长亚洲风格、写实风格、彩色黑白等等。他的独特构图和错综复杂的细节使得纹身作品与众不同，无论是从近看还是远观。</span><br />
          <span class="tea">
            Mr. Ricky was once a prominent young Chinese artist celebrated for his exceptional calligraphy and painting
            skills, winning numerous national and international awards. In 2015, he received an Artistic Achievement
            Award
            at Capitol Hill in Washington, D.C., presented by Congresswoman Carolyn Maloney, highlighting his impact on
            the art community.
            Later, he transitioned to tattoo artistry, quickly gaining recognition for his work at the New York
            International Tattoo Expo, where he won multiple first, second, and third prizes. Mr. Ricky excels in
            various
            styles, including Asian, realistic, and both colored and black-and-white tattoos. His unique compositions
            and
            intricate details make his tattoos stand out, inviting admiration from both close up and afar. His journey
            reflects a remarkable evolution in his artistic expression, merging traditional techniques with modern
            aesthetics.</span>
        </div>
      </div>
      <!-- <div class="flex flex-wrap gap-x-[30px] gap-y-[17px] justify-center mt-[53px]">
        <img class="w-[30vw]" :src="getAssetsImgFile('rm', `r${r}.png`)" alt="" v-for="r in 8">
      </div> -->
      <div class="w-full flex justify-center">
        <div class="p-example__body mt-[36px] w-[60vw]">
          <div class="p-example__splide">
            <div class="splide" ref="splideRef">
              <div class="splide__track">
                <ul class="splide__list">
                  <li v-for="r in 8" :key="r" class="p-splide__slide splide__slide" @click="show('r', r)">
                    <img :src="getAssetsImgFile('r', `r${r}.png`)" alt="" class="object-cover">
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="hidden laptop:flex tablet:flex flex-col bg-[#EAEAEA] pt-[84px] pb-[106px] px-[30px] justify-center mb-[54px]">
      <div class="flex flex-col items-center gap-[18px]">
        <span class="teko font-[500] text-[24px] mac:text-[24px]">Danny</span>
        <img src="@/assets/img/danny.png" alt="contact" class="w-[80%]">
        <div class="text-[14px] teko flex flex-col gap-[5px] w-[80%]">
          <span class="noto">Danny 师傅从小喜欢艺术，现在已经是有多年年经验的纹身师。擅长亚洲风格，中国水彩纹身，
            细线纹身，细小纹身等等。他讲究细节，构图精致，都能体现他的坚实的艺术基础。</span><br />
          <span class="tea w-[90%]">
            Master Danny has loved art since he was a child, and now he is a tattoo artist with many years of
            experience. He is good at Asian style, Chinese watercolor tattoos, fine line tattoos, small tattoos, etc.
            His attention to details and his composition is exquisite, which can reflect his solid artistic
            foundation.</span>
        </div>
      </div>
      <!-- <div class="flex flex-wrap gap-x-[30px] gap-y-[17px] justify-center mt-[53px]">
        <img class="w-[30vw]" :src="getAssetsImgFile('d', `d${r}.png`)" alt="" v-for="r in 8">
      </div> -->
      <div class="w-full flex justify-center">
        <div class="p-example__body mt-[36px] w-[60vw]">
          <div class="p-example__splide">
            <div class="splide" ref="splideRef2">
              <div class="splide__track">
                <ul class="splide__list">
                  <li v-for="r in 8" :key="r" class="p-splide__slide splide__slide" @click="show2('d', r)">
                    <img class="w-[30vw]" :src="getAssetsImgFile('d', `d${r}.png`)" alt="">
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="hidden laptop:flex tablet:flex bg-[#EAEAEA] pt-[84px] pb-[106px] justify-center">
      <div class="flex flex-col items-center gap-[18px]">
        <span class="teko font-[500] text-[36px] mac:text-[24px]">Kimberly</span>
        <img src="@/assets/img/kimberly.png" alt="contact">
      </div>
    </div>
    <!-- contact 電腦版 -->
    <div class="w-full flex justify-center items-center py-[247px] laptop:hidden tablet:hidden">
      <div class="flex">
        <img src="@/assets/img/contactphoto.png" alt="" class="w-[410px]">
        <div
          class="w-[295px] h-[333px] bg-[#292929] translate-x-[-40px] translate-y-[71px] flex flex-col gap-[18px] justify-center">
          <div class="flex flex-col gap-[4px] items-center">
            <span class="text-[24px] font-[400] text-white teko mac:text-[24px] tracking-wide">CONTACT</span>
            <span class="text-[15px] font-[300] text-white teko text-center mac:text-[15px] tracking-widest">(646)
              379-9995</span>
          </div>
          <div class="flex flex-col gap-[4px] items-center">
            <span class="text-[24px] font-[400] text-white teko mac:text-[24px] tracking-wide">LOCATION</span>
            <span class="text-[15px] font-[300] text-white teko text-center mac:text-[15px] tracking-widest">133-55
              Roosevelt
              Ave<br />2nd fl, Flushing,
              NY
              11354</span>
          </div>
          <div class="flex flex-col gap-[4px] items-center">
            <span class="text-[24px] font-[400] text-white teko mac:text-[24px] tracking-wide">HOURS OF
              OPERATION</span>
            <span class="text-[15px] font-[300] text-white teko mac:text-[15px] tracking-widest">
              Mon - Sat ______ 12AM - 7PM</span>
            <span
              class="text-[15px] font-[300] text-white teko mac:text-[15px] tracking-widest">&nbsp;&nbsp;&nbsp;&nbsp;Sunday
              ______12AM
              -
              6PM</span>
          </div>
        </div>
      </div>
      <!-- <div class="w-fit h-fit relative">
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
      </div> -->
    </div>
    <!-- contact 手機版 -->
    <div
      class="hidden laptop:flex tablet:flex bg-[#292929] w-full pt-[191px] pb-[100px] justify-center relative mt-[200px] mb-[75px]">
      <img src="@/assets/img/mcontact.png" alt="" class="absolute top-[-100px]">
      <div class="flex flex-col justify-between gap-[46px]">
        <div class="flex flex-col gap-[4px] items-center">
          <span class="text-[24px] font-[400] text-white teko tracking-widest">CONTACT</span>
          <span class="text-[18px] font-[300] text-[#D3D3D3] teko tracking-widest">(646) 379-9995</span>
        </div>
        <div class="flex flex-col gap-[4px] items-center">
          <span class="text-[24px] font-[400] text-white teko tracking-widest">LOCATION</span>
          <span class="text-[18px] font-[300] text-[#D3D3D3] teko text-center tracking-widest">133-55 Roosevelt
            Ave<br />2nd fl, Flushing,
            NY
            11354</span>
        </div>
        <div class="flex flex-col gap-[4px] items-center">
          <span class="text-[24px] font-[400] text-white teko tracking-widest">HOURS OF OPERATION</span>
          <span class="text-[18px] font-[300] text-[#D3D3D3] teko tracking-widest">Mon - Sat --------- 12AM - 7PM</span>
          <span class="text-[18px] font-[300] text-[#D3D3D3] teko tracking-widest">Sunday --------- 12AM - 6PM</span>
        </div>
      </div>
    </div>
    <div id="CONTACT" class="mx-[20%] flex flex-col justify-center items-center tablet:hidden">
      <div
        class="text-[32px] mac:text-[32px] font-[500] tablet:leading-[2rem] tablet:text-[1.5rem] tablet:text-center teko tracking-wide">
        Professional Tattooing and Piercing</div>
      <div class="text-[15px] mac:text-[15px] font-[400] my-[2rem] tablet:text-[1rem] tea text-center w-[80%]">
        Led by award-winning tattoo artist Ricky, who has won multiple honors at the New York International Tattoo Expo,
        our team is dedicated to providing you with a high-quality tattoo experience in a safe and hygienic environment.
        We listen carefully to your ideas and work with you to create a unique, stunning tattoo.
      </div>
      <div class="text-[15px] mac:text-[15px] font-[400] tablet:text-[1rem] tea text-center w-[80%]">
        Our artists are skilled in a variety of styles, including Neo-traditional, Traditional, Japanese, Realistic,
        Fine Line, Portrait, Old School, and cover-up tattoos. Danny, another highly experienced artist on our team,
        specializes in Asian styles, Chinese watercolor, fine line, and small tattoos, with a keen eye for detail and
        refined compositions.
      </div>
      <div class="text-[20px] mac:text-[20px] font-[600] tablet:text-[1rem] tea mt-[10px]">Book your appointment
        today! </div>
      <div class="text-[20px] mac:text-[20px] font-[600] tablet:text-[1rem] tea">Call (646) 379-9995 for consultation.
      </div>
    </div>
    <div id="CONTACT" class="flex-col justify-center items-center hidden tablet:flex px-[15%]">
      <div
        class="text-[36px] mac:text-[28px] font-[500] tablet:leading-[2rem] tablet:text-[36px] tablet:text-center teko tracking-wide">
        Professional<br />Tattooing and Piercing</div>
      <div class="text-[15px] mac:text-[15px] font-[400] my-[2rem] tablet:text-[1rem] tea text-center">
        Led by award-winning tattoo artist Ricky, who has won multiple honors at the New York International Tattoo Expo,
        our team is dedicated to providing you with a high-quality tattoo experience in a safe and hygienic environment.
        We listen carefully to your ideas and work with you to create a unique, stunning tattoo.
      </div>
      <div class="text-[15px] mac:text-[15px] font-[400] tablet:text-[1rem] tea text-center">
        Our artists are skilled in a variety of styles, including Neo-traditional, Traditional, Japanese, Realistic,
        Fine Line, Portrait, Old School, and cover-up tattoos. Danny, another highly experienced artist on our team,
        specializes in Asian styles, Chinese watercolor, fine line, and small tattoos, with a keen eye for detail and
        refined compositions.
      </div>
      <div class="text-[15px] mac:text-[15px] font-[600] tablet:text-[1rem] tea mt-[40px]">Book your appointment
        today! </div>
      <div class="text-[15px] mac:text-[15px] font-[600] tablet:text-[1rem] tea">Call (646) 379-9995 for consultation.
      </div>
    </div>
    <div class="flex justify-center items-center gap-[2rem] my-[10rem] tablet:hidden ">
      <img src="@/assets/img/contactImg1.png" alt="" class="w-[300px] h-[412px] object-cover">
      <img src="@/assets/img/contactImg2.png" alt="" class="w-[300px] h-[412px] object-cover">
      <img src="@/assets/img/contactImg3.png" alt="" class="w-[300px] h-[412px] object-cover">
    </div>
    <div class="hidden flex-col justify-center items-center gap-[2rem] my-[5rem] px-[20px] tablet:flex">
      <img src="@/assets/img/contactImg3.png" alt="" class="w-[227px] h-[338px] object-cover">
      <img src="@/assets/img/contactImg1.png" alt="" class="w-[227px] h-[338px] object-cover">
      <img src="@/assets/img/contactImg2.png" alt="" class="w-[227px] h-[338px] object-cover">
    </div>
  </div>
  <div
    class="w-[53px] h-[53px] bg-[#D9D9D9] rounded-full fixed bottom-[24px] right-[20px] flex justify-center items-center">
    <img src="@/assets/icon/arrow.svg" alt="arrow" class="w-[40px] rotate-90" @click="goToTop()">
  </div>
  <div class="fixed top-0 left-0 w-screen h-screen flex items-center justify-center z-[1000]" v-if="showBigPhoto">
    <div class="w-full h-full pic absolute left-0 top-0 z-10" @click="showBigPhoto = false"></div>
    <div class="absolute right-10 top-5 text-xl font-semibold z-20 text-white cursor-pointer"
      @click="showBigPhoto = false">
      <img src="@/assets/icon/closewhite.svg" alt="">
    </div>
    <img src="@/assets/img/ca.png"
      class="rotate-180 w-[50px] absolute top-[50%] left-[20%] translate-y-[-50%] cursor-pointer tablet:left-0 z-20"
      @click="changePicIndex('back')">
    <img :src="nowPic"
      class="h-[80vh] object-contain absolute left-[50%] translate-x-[-50%] z-20 tablet:w-[70vw] tablet:h-auto">
    <img src="@/assets/img/ca.png"
      class="w-[50px] absolute top-[50%] right-[20%] translate-y-[-50%] cursor-pointer tablet:right-0 z-20"
      @click="changePicIndex('go')">
  </div>
  <div class="fixed top-0 left-0 w-screen h-screen flex items-center justify-center pic z-[1000]" v-if="showBigPhoto2">
    <div class="w-full h-full pic absolute left-0 top-0 z-10" @click="showBigPhoto2 = false"></div>
    <div class="absolute right-10 top-5 text-xl font-semibold z-20 text-white cursor-pointer"
      @click="showBigPhoto2 = false">
      <img src="@/assets/icon/closewhite.svg" alt="">
    </div>
    <img src="@/assets/img/ca.png"
      class="rotate-180 w-[50px] absolute top-[50%] left-[20%] translate-y-[-50%] cursor-pointer tablet:left-0 z-20"
      @click="changePicIndex2('back')">
    <img :src="nowPic2"
      class="h-[80vh] object-contain absolute left-[50%] translate-x-[-50%] z-20 tablet:w-[70vw] tablet:h-auto">
    <img src="@/assets/img/ca.png"
      class="w-[50px] absolute top-[50%] right-[20%] translate-y-[-50%] cursor-pointer tablet:right-0 z-20"
      @click="changePicIndex2('go')">
  </div>
</template>

<script setup>
import { ref, computed, onMounted } from 'vue'
import { getAssetsImgFile } from '../utils/commonUse'
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'
import 'vue3-carousel/dist/carousel.css'
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
  if (nowIndex.value == 9 && type == 'go') {
    nowIndex.value = 1
    return
  } else if ((nowIndex.value == 1 || nowIndex.value == 0) && type == 'back') {
    console.log('yoyoy', nowIndex.value)
    nowIndex.value = 9
    return
  }
  type == 'back' ? nowIndex.value -= 1 : nowIndex.value += 1
}
const changePicIndex2 = (type) => {
  if (nowIndex2.value == 9 && type == 'go') {
    nowIndex2.value = 1
    return
  } else if ((nowIndex2.value == 1 || nowIndex2.value == 0) && type == 'back') {
    console.log('yoyoy', nowIndex2.value)
    nowIndex2.value = 9
    return
  }
  type == 'back' ? nowIndex2.value -= 1 : nowIndex2.value += 1
}
const breakpoints = {
  // 700px and up
  700: {
    itemsToShow: 3,
    snapAlign: 'center',
  },
  // 1024 and up
  1290: {
    itemsToShow: 6,
    snapAlign: 'start',
  },
}

import '@splidejs/splide/dist/css/splide.min.css'
import Splide from '@splidejs/splide'
import { Grid } from '@splidejs/splide-extension-grid'

const splideRef = ref(null)
const splideRef2 = ref(null)

onMounted(() => {
  const splide = new Splide(splideRef.value, {
    type: 'loop',
    height: '400px',
    gap: '1em',
    perPage: 2,
    perMove: 1,
    grid: {
      dimensions: [[1, 1], [2, 2], [2, 1], [1, 2], [2, 2], [3, 2]],
      gap: {
        row: '1em',
        col: '1em'
      }
    },
    breakpoints: {
      600: {
        height: '300px',
        perPage: 1,
        grid: {
          dimensions: [[2, 2], [2, 2], [2, 2]],
          gap: {
            row: '13px',
            col: '13px'
          }
        }
      }
    }
  })
  const splide2 = new Splide(splideRef2.value, {
    type: 'loop',
    height: '400px',
    gap: '1em',
    perPage: 2,
    perMove: 1,
    grid: {
      dimensions: [[1, 1], [2, 2], [2, 1], [1, 2], [2, 2], [3, 2]],
      gap: {
        row: '1em',
        col: '1em'
      }
    },
    breakpoints: {
      600: {
        height: '300px',
        perPage: 1,
        grid: {
          dimensions: [[2, 2], [2, 2], [2, 2]],
          gap: {
            row: '13px',
            col: '13px'
          }
        }
      }
    }
  })

  splide.mount({ Grid })
  splide2.mount({ Grid })
})
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Teko:wght@300..700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&family=Teachers:ital,wght@0,400..800;1,400..800&display=swap');
.teko {
  font-family: "Teko", sans-serif;
}
.noto{
  font-family: "Noto Sans", sans-serif;
}
.tea{
  font-family: "Teachers", sans-serif;
}
.pic {
  background-color: rgba(0, 0, 0, 0.7);
}

:deep(.splide__arrow--prev) {
  transform: translate(-50px, -30px);
  width: 41px;
  height: 41px;
  background-image: url(@/assets/img/ev.svg);
  background-repeat: no-repeat;
  background-size: contain;
  background-color: transparent;

  >svg {
    display: none;
  }
}

:deep(.splide__arrow--next) {
  transform: translate(50px, -30px);
  width: 41px;
  height: 41px;
  background-image: url(@/assets/img/ev2.svg);
  background-repeat: no-repeat;
  background-size: contain;
  background-color: transparent;

  >svg {
    display: none;
  }
}

:deep(.carousel__next) {
  transform: translate(50px, -30px);
  width: 41px;
  height: 41px;
  background-image: url(@/assets/img/ev2.svg);
  background-repeat: no-repeat;
  background-size: contain;

  .carousel__icon {
    display: none;
  }
}

:deep(.carousel__prev) {
  transform: translate(-50px, -30px);
  width: 41px;
  height: 41px;
  background-image: url(@/assets/img/ev.svg);
  background-repeat: no-repeat;
  background-size: contain;

  .carousel__icon {
    display: none;
  }
}

:deep(.carousel__pagination) {
  .carousel__pagination-item {
    .carousel__pagination-button {
      &::after {
        width: 8px;
        height: 8px;
        border-radius: 50%;
      }
    }
  }
}

// .p-splide {
//   &__slide {
//     position: relative;
//     color: #fff;
//     border-radius: .5rem;
//     border: 3px solid #eef5ae;
//     background: #dceb5d;
//     overflow: hidden;
//     line-height: 1.5;
//     transition: border-color .15s cubic-bezier(.54, .01, .1, 1), background-color .15s cubic-bezier(.54, .01, .1, 1);
//   }

//   &__slide-number {
//     position: absolute;
//     bottom: .15em;
//     left: .5rem;
//     font-family: 'Lato', sans-serif;
//     font-size: 1.7rem;
//     line-height: .75;
//     font-weight: bold;

//     @media screen and (min-width: 768px) {
//       left: 1rem;
//       font-size: 3.2rem;
//     }
//   }
// }

// .splide {
//   &__slide {
//     &.is-active {
//       .p-splide__slide {
//         background: #13c59d;
//         border-color: #13c59d;
//       }
//     }
//   }

//   &__pagination {
//     bottom: -2.3rem;
//     left: 50%;
//     transform: translateX(-50%);

//     &__page {
//       padding: 0;
//       width: 10px;
//       height: 10px;
//       border-radius: 50%;
//       background: #93a313;
//       margin: .4em;
//       cursor: pointer;
//       display: block;
//     }
//   }
// }
</style>