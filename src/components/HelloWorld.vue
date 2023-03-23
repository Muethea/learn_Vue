<template>
  <div>
    <h1>Esta é a descrição da pessoa: {{ nome }}</h1>
   <Info/>


     
  </div>
</template>

<script>
import Info from './Info.vue'

export default {
  components: { Info },
  name: 'HelloWorld',

  data(){
    return {
        nome:"Fernando dos Santos"
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
