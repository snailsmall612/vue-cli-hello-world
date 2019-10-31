<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <router-link to="/">首頁</router-link>
      <router-link to="/hello2">連結二</router-link>
    </div>
    <router-view />
    <SiteFooter></SiteFooter>
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <button class="btn btn-primary">bootstrap按鈕</button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import SiteFooter from '@/components/SiteFooter'
export default {
  name: 'App',
  components: {
    SiteFooter
  }
}
$(function () {
  alert('jquery test')
})
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
