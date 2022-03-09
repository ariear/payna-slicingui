<template>
  <div class="container mx-auto flex flex-col md:flex-col lg:flex-row justify-center items-center pb-16 font-pupylinux text-center md:text-center lg:text-left">
      <img src="/asset/fek-video.png" alt="" class="w-[93vw] md:w-[500px] lg:w-[400px] xl:w-[636px]">
      <div class="w-[94vw] md:w-[422px] md:ml-0 lg:ml-16 mt-7 md:mt-10 lg:mt-0">
          <p class="font-bold text-[#F75C4E]">SAVE MORE TIME</p>
          <p class="font-bold text-3xl md:text-4xl mt-3">And Boost Productifity</p>
          <p class="font-normal text-[#575455] py-8">
              Your employees can bring any success into your business, so we need to take care of them
          </p>
          <div class="relative hidden md:block">
              <input type="email" placeholder="Email Address" class="bg-[#F5F6FB] rounded-full py-3 px-7 w-full">
              <button class="font-semibold bg-[#1F7CFF] py-3 px-10 text-white rounded-full absolute right-0 hover:opacity-90 transition-all">Get Started</button>
          </div>

          <!-- mobile input -->
          <div class="block md:hidden">
              <input type="email" placeholder="Email Address" class="bg-[#F5F6FB] rounded-full py-3 px-7 w-full">
              <button class="font-semibold bg-[#1F7CFF] py-3 text-white rounded-full w-full mt-4">Get Started</button>
          </div>          
          <!-- end mobile input -->

      </div>
  </div>
</template>

<script>
export default {

}
</script>