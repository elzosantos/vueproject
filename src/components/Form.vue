<template>
  <div>
    <form action="">
      <div><InputText /></div>
      <div><InputText /></div>
      <div><Submit /></div>
    </form>
  </div>
</template>
      
  <script>
import InputText from "./form/Input.vue";
import Submit from "./form/Submit.vue";
export default {
  name: "Form",
  components:{
    InputText,
    Submit
  }
};
</script>