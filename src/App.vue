<template>
  <div id="app">
  {{ message }}
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello World',
    };
  },
};
</script>
<style>
div{
  background-color: blue;
}
</style>
