<template>
<div>
  <h2>Meu formulário</h2>
  <form action="">
    <div>
      <inputText/>
    </div>
    <div>
      <inputText/>
    </div>
    <div>
      <submitText/>
    </div>
  </form>
</div>
</template>

<script>
  import inputText from './inputs/inputText.vue';
  import submitText from './inputs/submitText.vue';

  export default {
    name: "formForm",
    components: {
      inputText,
      submitText
    }
  };
</script>