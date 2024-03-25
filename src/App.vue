<template>
  <div class="d-flex justify-content-center">
    <SideBar />
    <AppHome />
  </div>
</template>

<script>
// import axios from 'axios';
import AppHome from './components/AppHome.vue';
import SideBar from './components/SideBar.vue';

export default {
  data(){
    return{}
  },
  components: { AppHome, SideBar }
}
</script>

<style lang="scss">
  *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>