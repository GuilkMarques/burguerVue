<template>
  <h1>Olá Vue!</h1>
  <p>Meu nome é {{ nome }} e trabalho como {{ profissao }}</p>
</template>

<script>
  export default {
    name: "firstComponent",
    data() {
      return {
        nome: "Guilherme",
        profissao: "Programador"
      };
    },
    
  };
</script>