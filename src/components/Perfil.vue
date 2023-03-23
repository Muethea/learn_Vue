<template>
  <img :src="perfil" :alt="detail" srcset="">
</template>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"Perfil",

    data(){
      return{

        perfil:"/src/assets/logo.png",
        detail:"Logo de Vue"
      }
    }
}
</script>

<style>

</style>