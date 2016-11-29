<template>
 
  <div id="app">
   <img src="../img/logo.png" alt="">
<h1>this takes too long</h1>  
   <special-div message="Hello"></special-div>
   <special-div message="from"></special-div>
   <special-div message="XPage"></special-div>
  
   <div> {{msg}}</div>
</template>

<script>
import specDiv from './components/Div.vue'
export default {
  components: {
    specialDiv: specDiv 
  },
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Vue'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
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
