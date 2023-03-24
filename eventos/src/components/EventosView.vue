<template>
  <h1>Eventos</h1>

  <form action="" @submit.prevent="enviar">
  <p><input type="text" placeholder="nome" v-model="name"></p>
  <p><input type="email" placeholder="email" v-model="email"></p>
  <p><input type="password" placeholder="password" v-model="password"></p>

  <button >Enviar</button>

  <h1>{{ informacao }}</h1>
  </form>
</template>

<script>
export default {

  data(){
    return{
      name:'',
      email:'',
      password:'',
      informacao:'',
    }
  },

  methods:{
    enviar(){

      this.informacao = this.name+" "+this.email+" "+this.password;

      
    }
  }


}
</script>

<style>

</style>