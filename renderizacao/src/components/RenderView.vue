<template>
  <div>

    <h1>BackEnd</h1>
    <ul>
        <li v-for="(tecnology, indix) in backendTecnology" v-bind:key="indix">{{ tecnology }}</li>
    </ul>

      <h1>FrontEnd</h1>
      <ul>
          <li v-for="(tecnology) in frontTecoology" :key="tecnology.id">{{ tecnology.language }}</li>
      </ul>
  </div>
</template>

<script>
export default {

  data(){
    return {
      frontTecoology:[
      
    {id: 1, language:'Html'},
    {id: 2, language: 'CSS' },
    { id: 2, language: 'Javascript' },
    {id: 3, language: 'Vue' },


      
      
      ],
      backendTecnology:['NodeJS', 'PHP', 'JavaScript']

    }
  }

}
</script>

<style>

    ul{
      list-style: none;
    }


</style>