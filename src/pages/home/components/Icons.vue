<template>
   <div class="icons">
      
           
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>
        

                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>


                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>


                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>


                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>


                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>

                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>


                 
             <div class="icon">

                <div class="icon-img">
                    <img class="icon-img-content" src=" " alt="">
                </div>
           
                 <p class="icon-desc">热门景点</p>
            </div>


            

   </div>
</template>

<script>
export default {
     name: 'HomeIcons'
}
</script>

<style lang="stylus" scoped>
    @import '~@/assets/styles/varibles.styl'
    .icons
        width:100%
        overflow:hidden
        height:0
        padding-bottom:50%
        background:green
        .icon
            overflow:hidden
            float:left
            width:25%
            padding-bottom:25%
            background:red
            position:relative
            .icon-img
                position:absolute
                top:0
                left:0
                right:0
                bottom: 0.44rem
                box-sizing:border-box
                padding:.1rem
                background:blue
                .icon-img-content
                    display:block
                    margin:0 auto
            .icon-desc
                position:absolute
                left:0
                right:0
                bottom:0
                height: 0.44rem
                line-height:.44rem
                text-align:center
                color:$darkTextColor


</style>

