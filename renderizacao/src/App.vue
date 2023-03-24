<template>

<RenderView/>
</template>

<script>
import RenderView from './components/RenderView.vue';


export default {
    name: "App",
    components: { RenderView }
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
