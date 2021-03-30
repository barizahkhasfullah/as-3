<template>

  <div class="object-center" id="app">
     
    <img id="img" class=" object-center w-40 md:w-32 lg:w-48 " alt="Bari" src="./assets/RDP01352.jpg">
   <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}

</script>

<style>
#img {
  margin-top: 80px;
  position: center;
  margin-left: auto;
  margin-right: auto;
}
</style>

