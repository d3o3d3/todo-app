<template>
  <div id="app">
    {{ message }}
    <h3>Bye Everybody</h3>
    <Comp1></Comp1>
  </div>
</template>

<script>
import Comp1 from './components/comp1.vue'

export default {
  name: 'App',
  data() {
    return {
      message: 'Hello World',
    };
  components: {
    Comp1,
  },
};
</script>
<style>
div{
  background-color: blue;
}
</style>
