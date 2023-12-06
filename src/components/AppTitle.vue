<script>
export default {
  name: 'AppTitle',
  data() {
    return {
      titolo: 'La mia prima app con Vite!',
    };
  },
};
</script>

<template>
  <h2>{{ titolo }}</h2>
</template>

<style scoped>
h2 {
  font-size: 50px;
  color: goldenrod;
}
</style>
