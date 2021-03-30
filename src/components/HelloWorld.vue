<template>
  <div class="hello">
    <h1 class="text-center font-mono font-extrabold">{{ msg }}</h1>
  


<h3>
  <p class="text-center font-mono font-extrabold text--900 md:text-green-600 ...">ABOUT ME<br></p>
    <p class="text-center font-mono font-extrabold text-purple-900 md:text-green-600 ...">Name: Nur Barizah binti Khasfullah<br></p>
  <p class="text-center font-mono font-extrabold text-purple-900 md:text-green-600 ...">Student ID: 19FTT1186</p>
  <p class="text-center font-mono font-extrabold text-purple-900 md:text-green-600 ...">Group Code: DWDT05</p>
   </h3> 
   
  
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
