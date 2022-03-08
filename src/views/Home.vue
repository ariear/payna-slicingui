<template>
  <div class="font-pupylinux lg:w-[94vw] xl:container mx-auto flex justify-between items-center py-20 md:py-36">
      <div class="w-[94vw] md:w-[443px] lg:w-[420px] xl:w-[443px] md:text-center lg:text-left md:mx-auto lg:mx-0 pl-5 md:pl-0">
          <p class="font-bold text-[40px] md:text-[55px] lg:text-[45px] xl:text-[55px]">{{ mainText }}</p>
          <p class="font-normal text-[#575455] py-8">{{ secondText }}</p>
          <button class="bg-[#1F7CFF] text-white font-semibold py-3 px-10 rounded-full">Get Started</button>
      </div>
      <img src="/asset/main-model.png" class="hidden md:hidden lg:block lg:w-[460px] xl:w-[785px]" alt="mbak mbak">
  </div>

  <div class="lg:w-[94vw] xl:container mx-auto flex flex-col md:flex-col lg:flex-row md:items-center md:justify-between">
      <p class="font-pupylinux font-semibold text-[#070F18] md:mb-8 lg:mb-0 ml-6 md:ml-6">Trusted by <span class="inline md:inline lg:block">Global Companies</span></p>
      <div class="flex items-center flex-wrap md:flex-nowrap">
          <img v-for="(image , index) in powered" :key="index" :src="image.url" class="mx-6 lg:w-[70px] xl:w-[88px] mt-5 md:mt-0" alt="">
      </div>
  </div>

  <Feature />
  <GetStart />
</template>

<script>
import Feature from "../components/Feature.vue";
import GetStart from "../components/GetStart.vue";
export default {
    data() {
        return {
            mainText: "Manage Payroll Like an Expert",
            secondText: "Payna is helping you to setting up the payroll without required any finance skills or knowledge before",
            powered: [
                {
                    url: "/asset/apple.png"
                },
                {
                    url: "/asset/adobe.png"
                },
                {
                    url: "/asset/slack.png"
                },
                {
                    url: "/asset/spotify.png"
                },
                {
                    url: "/asset/google.png"
                }
            ]
        };
    },
    components: { Feature, GetStart }
}
</script>