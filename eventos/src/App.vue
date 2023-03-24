<template>
<div>
  <EventosView/>
</div>
</template>

<script>

import EventosView from './components/EventosView.vue';


export default {
    name: "App",
    components: { EventosView }
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
