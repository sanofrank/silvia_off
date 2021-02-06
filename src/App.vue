<template>
  <div id="app">
    <Title msg="Hi! Nice to meet you :)"/>
    <div>
      <img alt="Vue logo" src="./assets/animation.gif">
    </div>    
    <description></description>
    <footer-social></footer-social>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Description from './components/Description'
import FooterSocial from './components/FooterSocial'

export default {
  name: 'App',
  components: {
    Title,
    Description,
    FooterSocial
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
  margin-top: 60px;
  display: contents;
}

img{
  height: auto;
  width: 400px;
  max-width: 100%;
  }
</style>
