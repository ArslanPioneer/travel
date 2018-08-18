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
                  imgUrl: '//p.qpic.cn/qqconadmin/0/cf8bf6aac09445e9beb92363e4a0323a/0'
              },
              {
                  id: '0002',
                  imgUrl: '//p.qpic.cn/qqconadmin/0/84b4107c553c4000b90048e67483f298/0'
              },
              {
                  id:'0003',
                  imgUrl: 'https://10.url.cn/qqcourse_logo_ng/ajNVdqHZLLB5kjkWicXnjhjPxyDbZK9pEZgUcKoIeGagRGiaX6luBXxBVcFBunic9nccBnmQLzOTd4/510?tp=webp'
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
