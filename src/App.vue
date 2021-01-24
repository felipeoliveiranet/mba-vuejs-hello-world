<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" aria-hidden="true">
    <HelloWorld msg="Welcome to My Very First Vue.js Application"/>
    <FooterDefault :studentID="student.id" :studentName="student.name"></FooterDefault>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FooterDefault from './components/FooterDefault.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    FooterDefault
  },
  data() { 
    return {
      student: {
        id: '338405',
        name: 'Felipe Pereira Oliveira'
      }
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
