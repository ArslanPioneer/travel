<template>
 <div class="wrapper"> 
    <swiper :options="swiperOption">
    <!-- slides -->
    <swiper-slide v-for="item of swiperList" :key="item.id">
        <img  class="swiper-img"  :src="item.imgUrl"  />
    </swiper-slide>
    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
 </div>
</template>

<script>
  export default {
      name:'HomeSwiper',
      data() {
          return {
              swiperOption: {
                  pagination: '.swiper-pagination',
                  loop: true
              },
              swiperList: [{
                  id: '0001',
                  imgUrl: 'https://dimg04.c-ctrip.com/images/70070q000000go6y6B9EF_1920_340_17.jpg'
              },
              {
                  id: '0002',
                  imgUrl: 'https://dimg04.c-ctrip.com/images/700b0u000000jfd8t8637_1920_340_17.jpg'
              },
              {
                  id:'0003',
                  imgUrl: 'https://imgs.qunarzz.com/p/tts3/201408/09/8fc8e0f20aa09868c8d65eac.jpg_r_390x260x90_cc544545.jpg'
              }]
          }
      }
  }  
</script>

<style lang="stylus" scoped>
    .wrapper >>> .swiper-pagination-bullet-active
        background: #fff  
    .wrapper
        overflow:hidden
        width:100%
        height:0
        padding-bottom:31.25%
        background:#eee
        .swiper-img 
             width:100%
             
</style>
