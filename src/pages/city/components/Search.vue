<template>
     <div class="search">
         <input class="search-input" type="text" placeholder="输入城市名或拼音">
     </div>
</template>

<script>
export default {
    name: 'CitySearch'
}
</script>

<style lang="stylus" scoped>
    @import '~@/assets/styles/varibles.styl'
    .search
        height: 0.72rem
        padding: 0.1rem
        background:$bgColor
        .search-input
            box-sizing:border-box
            padding: 0 0.1rem
            height:.62rem
            line-height:.62rem
            width:100%
            text-align:center
            border-radius:.06rem


       
</style>
