<template>
  <div>
     <p v-if="trabalhando">Estou trabalhando no momento</p>
     <p v-else>Em busca de novas oportunidades</p>
        <p>Utilizo as seguintes tecnologias:</p>
        <ul>
          <li>React</li>
          <li>Vue JS</li>
          <li>Javascript</li>
        </ul>

        <p v-show="mostraremail">Mande uma mensagem para: {{ email }}</p>
  </div>
</template>

<script>

export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Info',

    data(){
      return {
        trabalhando:true, 
        mostraremail:false,
          email:"email@email.com"
      }
    }
}
</script>

<style>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>