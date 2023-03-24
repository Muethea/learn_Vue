<template>
  <h1>Mult Eventos</h1>

  <button @click="primeiro()">Activar Eventos</button>
</template>

<script>
export default {

  data(){
    return{

      multEventos:''
    }
  },

  methods:{
    primeiro() {
      this.multEventos = "Primeiro evento ativado"

    }
  }

}
</script>

<style>

</style>