<template>
    <div class="header">
        <div class="header-left"><div class="iconfont back-arrow">&#xe624;</div></div>
        <div class="header-input">
            <span class="iconfont">&#xe632;</span>输入城市/景点/游玩主题
        </div>
        <div class="header-right">
            城市
            <span class="iconfont city">&#xe64a;</span>
        </div>
    </div>
</template>
<script>
export default {
    //name:'Headers',
    data(){
        return{
            
        }
    }
}
</script>
<style lang="stylus" scoped>
.header
    display :flex
    line-height :.86rem
    background :#00bcd4;
    .header-left
        float :left
        width :.86rem
        color:#fff
        .back-arrow
            font-size .4rem
            text-align:center

    .header-input
        flex:1
        background :#fff;
        height :.64rem
        line-height :.64rem
        border-radius:.1rem
        margin-top:.12rem
        padding-left:.2rem
        color:#ccc
        
    .header-right
        float:right
        width :1.24rem
        text-align:center
        color:#fff
        .city
            font-size:.24rem
</style>

