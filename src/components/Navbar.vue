<template>
  <nav class="flex items-center justify-between px-5 md:px-7 lg:px-7 xl:px-24 py-8">
      <div class="flex items-center">
          <img src="/asset/logo.png" alt="">
          <p class="font-pupylinux font-semibold text-2xl ml-5">Payna</p>
      </div>
      <div class="items-center font-pupylinux text-base hidden md:hidden lg:flex">
          <p class="mx-7 font-semibold relative group cursor-pointer">
              Home
              <span class="w-0 h-[3px] bg-[#63a1f8] absolute left-0 -bottom-1 group-hover:w-full transition-all"></span>
          </p>
          <p class="mx-7 relative group cursor-pointer">
              Features
              <span class="w-0 h-[3px] bg-[#63a1f8] absolute left-0 -bottom-1 group-hover:w-full transition-all"></span>
          </p>
          <p class="mx-7 relative group cursor-pointer">
              Showcase
              <span class="w-0 h-[3px] bg-[#63a1f8] absolute left-0 -bottom-1 group-hover:w-full transition-all"></span>
          </p>
          <p class="mx-7 relative group cursor-pointer">
              pricing
              <span class="w-0 h-[3px] bg-[#63a1f8] absolute left-0 -bottom-1 group-hover:w-full transition-all"></span>
          </p>
      </div>

      <button class="py-3 px-10 rounded-full bg-[#F5F6FB] font-pupylinux hidden md:block">Sign In</button>
  </nav>
</template>

<script>
export default {

}
</script>