<template>
    <div>
        <div class="title">{{title}}</div>
        <ul>
            <li class="re border-bottom" v-for="(item,key) in ReList" :key="item.id">
                <div class="item-img">
                    <img class="re-img" :src="item.imgUrl" />
                </div>
                <div class="desc">
                    <h2 class="re-title">{{item.ReTitle}}</h2>
                    <p class="re-desc">{{item.desc}}</p>
                </div>
            </li>
        </ul>
    </div>
</template>
<script>
export default {
    data(){
        return{
            title:'周末去哪儿',
            ReList:[
                {
                    id:'0001',
                    imgUrl:'http://img1.qunarzz.com/sight/source/1505/85/708da4ab8dba17.jpg_r_640x214_d3d8cfa5.jpg',
                    ReTitle:'极地海洋世界',
                    desc:'青岛海昌极地海洋世界海上乐园',
                },
                {
                    id:'0002',
                    imgUrl:'http://img1.qunarzz.com/sight/source/1505/d2/bde427ee954da9.jpg_r_640x214_ae0ab333.jpg',
                    ReTitle:'青岛海泉湾度假区',
                    desc:'青岛即墨市海泉湾度假旅游区',
                },
                {
                    id:'0003',
                    imgUrl:'http://img1.qunarzz.com/sight/source/1505/94/f48c88a43966be.jpg_r_640x214_629e5387.jpg',
                    ReTitle:'青岛海泉湾度假区',
                    desc:'青岛即墨市海泉湾度假旅游区',
                }
                
            ]
            
        }
    }
}
</script>
<style lang="stylus" scoped>
.item-img
    height :0
    padding-bottom :37%
    overflow :hidden
.title
    margin-top:.2rem
    background:#eee
    line-height .8rem
    text-indent:.2rem
.desc
    padding:.1rem
.re-img
    width:100%
.re-title
    margin-bottom:.1rem
    font-size:.32rem
.desc
    margin-left:.22rem
    overflow :hidden
    
    .re-desc
        margin-bottom:.1rem
        color:#ccc
    .re-more
        padding:0 .1rem
        border-radius:.06rem
        background:#ff9300
        color:#fff
</style>
