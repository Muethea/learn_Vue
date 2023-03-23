<template>
  <div>
  <h1>Metodos</h1>

 
   <p><input type="text" placeholder="Seu nome" v-model="nome"></p> 
   <p>

     <input type="email" placeholder="youremail@email.com" v-model="email">
   </p>

   <p><input type="password" placeholder="password" v-model="password"></p>

   <button @click="enviar">Clique</button>

   <p>{{ mostrar }}</p>

  </div>
</template>

<script>
export default {
  data(){
    return {
      nome:'',
      email:'ewwe',
      password:'',
      mostrar:'',
    }

  },

  methods:{

    enviar(){
      if(this.nome !=='' || this.email !==''){
     this.mostrar = this.nome
          // this.mostrar = this.email
      }else{
        alert("Please enter your name and email")
      }
     
    }

  }

}
</script>

<style>

</style>