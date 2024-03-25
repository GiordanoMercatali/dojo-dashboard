<template>
  <div class="container">
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
  
  .container{
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: start;
  }

  *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>