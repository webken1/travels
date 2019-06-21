<template>
    <div class="home">
        <headers></headers>
        <swiper></swiper>
    </div>
</template>
<script>
import Header from '@/pages/Home/components/Header.vue'
import HomeSwiper from '@/pages/Home/components/Swiper.vue'
export default {
    data(){
        return{

        }
    },components:{
      'headers':Header,
      'swiper':HomeSwiper
    }
}
</script>