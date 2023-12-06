<script>
export default {
  name: 'AppHero',
  data() {
    return {
      testo: 'Ciao, sono un jumbotron!',
    };
  },
};
</script>

<template>
  <div class="jumbotron">
    <h1>{{ testo }}</h1>
  </div>
</template>

<style scoped>
.jumbotron {
  background-color: greenyellow;
  padding: 20px;
  border-radius: 10px;
}

h1 {
  font-size: 36px;
  color: green;
}
</style>
