<template>
  <div class="font-pupylinux py-20 md:py-36">
      <div class="w-[94vw] md:w-[386px] mx-auto text-center">
          <p class="font-bold text-[#F75C4E]">WORK BETTER</p>
          <p class="font-bold text-4xl mt-3 mb-6">For Your Bussines</p>
          <p class="font-normal text-[#575455]">
            We did research what your company needs and here we are providing all of them just for you              
          </p>
      </div>

      <div class="container mx-auto grid md:grid-cols-2 lg:grid-cols-3 gap-y-12 justify-items-center mt-20">
          <div v-for="(fiturs , index) in fitur" :key="index" class="w-[300px] flex">
              <img :src="fiturs.img" alt="" class="w-max h-max">
              <div class="ml-6">
                  <p class="font-semibold text-xl text-[#070F18]">{{ fiturs.namefitur }}</p>
                  <p class="font-normal text-[#575455] mt-3">{{ fiturs.detailfitur }}</p>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            fitur: [
                {
                    img: '/asset/koper-icon.png',
                    namefitur: 'Share Insights',
                    detailfitur: 'Working together with your team to make decisions'
                },
                {
                    img: '/asset/track-icon.png',
                    namefitur: 'Track Leads',
                    detailfitur: 'See where your money goes and comes in business'
                },
                {
                    img: '/asset/nointernet-icon.png',
                    namefitur: 'Offline Mode',
                    detailfitur: 'Use the feature while off from internet? sure can'
                },
                {
                    img: '/asset/kanban-icon.png',
                    namefitur: 'kanban Mode',
                    detailfitur: 'Organize the report that easy to be understand'
                },
                {
                    img: '/asset/gift-icon.png',
                    namefitur: 'Reward System',
                    detailfitur: 'Motivate your team working harder and receive a gift'
                },
                {
                    img: '/asset/world-icon.png',
                    namefitur: '169 Country',
                    detailfitur: 'Working together worldwide people from anywhere'
                }
            ]
        }
    },
}
</script>