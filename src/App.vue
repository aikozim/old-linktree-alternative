<template>
  <Home />
</template>

<script>
import Home from '@/views/Home.vue';

export default {
  components: {
    Home,
  },
};
</script>

<style lang="scss">
  body {
    background: #4e54c8;
    background: -webkit-linear-gradient(to right, #4e54c8, #8f94fb);
    background: linear-gradient(to right, #4e54c8, #8f94fb);

    display: flex;
    justify-content: center;

    /* Blue Greenisch
    background: #11998e;
    background: -webkit-linear-gradient(to right, #38ef7d, #11998e);
    background: linear-gradient(to right, #38ef7d, #11998e);
    */
    /* Dark Blue
    background: #0f0c29;
    background: -webkit-linear-gradient(to right, #24243e, #302b63, #0f0c29);
    background: linear-gradient(to right, #24243e, #302b63, #0f0c29);
    */
  }
</style>
