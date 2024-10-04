<template>
  <div>
    <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
    <p>Estou trabalhando na area de {{ area }}</p>
    <infoPessoa/>
    <formForm/>
  </div>
</template>

<script>
  import infoPessoa from './infoPessoa.vue';
  import formForm from './formForm.vue';

  export default {
    name: "pessoaPrimeira",

    components: {
      infoPessoa,
      formForm
    },

    data() {
      return {
        nome: "Guilherme",
        area: "Programação",
      };
    },
  };
</script>