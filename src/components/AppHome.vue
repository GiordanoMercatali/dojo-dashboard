<template>
    <div class="home-wrapper">
        <HomeHeader />
        <!-- <header>Ciao</header> -->
    </div>
</template>

<script>
import HomeHeader from './HomeHeader.vue';
export default {
    data(){
        return{}
    },
    components: { HomeHeader }
}
</script>

<style lang="scss" scoped> 

    .home-wrapper{
        height: calc(100% - 0rem);
        width: 80%;
        background-color: red;
        display: inline-block;
    }
</style>