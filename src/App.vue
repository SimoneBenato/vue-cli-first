<template>

  <div>
    <Title />
    <Jumbotron />
  </div>

</template>

<script>
import Jumbotron from './components/Jumbotron.vue'
import Title from './components/Title.vue'
export default {
  name: 'App',
  components: {
    Title,
    Jumbotron,
  },
};
</script>

<style lang="scss"> 

</style>