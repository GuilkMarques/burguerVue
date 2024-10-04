<template>
  <first-component-vue/>
  <life-cycle-vue/>
  <pessoaPrimeira/>
</template>

<script>
  import firstComponentVue from './components/firstComponent.vue';
  import lifeCycleVue from './components/lifeCycle.vue';
  import pessoaPrimeira from './components/pessoaPrimeira.vue';

  export default {
    name: "App",
    components: {
      firstComponentVue,
      lifeCycleVue,
      pessoaPrimeira
    }
  };
</script>