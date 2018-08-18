<template>
    <div>
        <div class="title">周末去哪儿</div>
        <ul>
            <li class="item border-bottom" v-for="item of recommendList" :key="item.id">
                 <div class="item-img-wrapper">
                     <img class="item-img" :src="item.imgUrl"/>
                 </div>
                

                <div class="item-info">
                    <p class="item-title">{{item.title}}</p>
                    <p class="item-desc">{{item.desc}}</p>
           
                </div>
            </li>
        </ul>
    </div>
</template>


<script>
    export default {
        name:'HomeRecommend',
        data() {
            return{
                recommendList: [{
                id:'0001',
                imgUrl: '//10.url.cn/qqcourse_logo_ng/ajNVdqHZLLCdNBr520kvPNGcNy5abHtFGrib57XbXBzJC0erlj61zlYF99iat74wyU4ZlibC630eTY/356',
                title:'大连圣亚海洋世界',
                desc:'浪漫大连首站，浪漫的海洋主题乐园',
            },
            {
                id:'0002',
                imgUrl: '//10.url.cn/qqcourse_logo_ng/ajNVdqHZLLCEI9hElN4IyWE69OnqGQZHHsV3WBn0nz1sVUwIT2McZbESgCZo5QZSZ9YjEqolzxI/356',
                title:'大连圣亚海洋世界',
                desc:'浪漫大连首站，浪漫的海洋主题乐园',
            },

              {
                id:'0003',
                imgUrl: '//10.url.cn/qqcourse_logo_ng/ajNVdqHZLLCEI9hElN4IyWE69OnqGQZHHsV3WBn0nz1sVUwIT2McZbESgCZo5QZSZ9YjEqolzxI/356',
                title:'大连圣亚海洋世界',
                desc:'浪漫大连首站，浪漫的海洋主题乐园',
            },
            ]

        }
            
        }
    }
</script>

<style lang="stylus" scoped>
    .title
        margin-top :.2rem
        line-height:.8rem
        background:#eee
        text-indent:.2rem
    
    .item-img-wrapper
        overflow:hidden
        height:0
        padding-bottom:33.9%
        .item-img
            width:100%
        .item-info
            flex:1
            padding:.1rem
            .item-title
                line-height:.54rem
                font-size:.32rem
            .item-desc
                line-height:.4rem
                color:#ccc
             
</style>
