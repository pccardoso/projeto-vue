<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Estou nessa branch feature/teste3"/>

  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates officiis minus cum totam veritatis commodi eius! Quasi aliquid earum sit, tempore harum obcaecati cupiditate quae, reprehenderit soluta, commodi recusandae facilis! </p>
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
