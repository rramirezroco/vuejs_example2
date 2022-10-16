<template>
  <h2>Películas</h2>
  <Form msg="Hello Vue 3 in CodeSandbox!" />
</template>

<script>
import Form from "./components/Form.vue";
export default {
  name: "App",
  components: {
    Form: Form,
  },
};
</script>

<style lang="scss">
@import "./styles/_variables.sccs";

html,
body {
  background: $bg;
  color: $color;
  margin: 0;
  font-family: sans-serif;
}
h2 {
  border-bottom: 1px solid $color;
  padding-bottom: 10px;
}
</style>
