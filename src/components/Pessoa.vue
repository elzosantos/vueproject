<template>
  <div>
    <p>Pessoa - Meu nome é {{ nome }}</p>
    <Info />
    <Form />
  </div>
</template>
  
  <script>
import Info from "./Info.vue";
import Form from "./Form.vue";
export default {
  name: "Pessoa",
  components: {
    Info,
    Form
  },
  data() {
    return {
      nome: "Elzo Santos",
    };
  },
};
</script>