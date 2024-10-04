<template>
  <h1>Meu nome é {{ nome }}</h1>
</template>

<script>
  export default {
    name: "lifeCycle",
   data() {
     return {
       nome: "Ainda não sei",
     };
   },
   created() {
    setTimeout(() => {
        this.nome = "Sabrina";
      }, 2000);
    },
    mounted() {
      setTimeout(() => {
        this.nome = "Guilherme";
      }, 4000);
    }
  };
</script>