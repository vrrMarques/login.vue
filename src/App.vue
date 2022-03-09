<template>
  <div class="a"> 
    <navBar/>
    <div class="container w-25 p-3 bg-light mx-auto opacity-75" style="margin-top: 120px;">
      <div>
        <login/>
      </div>
    </div>
  </div>
  
  
</template>

<script>
import navBar from './components/navBar.vue'
import login from './components/login.vue'

export default {
  name: 'App',
  components: {
    login,
    navBar
  }
}
</script>

<style>
html,body{
background: url('http://www.osmais.com/wallpapers/201410/grande-lago-azul-wallpaper.jpg');
background-repeat: no-repeat;
background-size: cover;


}

</style>
