<template>
  <div id="carta">
    <img
        :src="card.thumb"
        :alt="card.type"
      >
      <h2>{{ card.series }}</h2>
  </div>
</template>

<!-- Script -->
<script>
export default {
  name: 'CardFilm',
  props: {
    card: Object,
  }
}
</script>

<!-- CSS -->
<style scoped lang="scss">
.card > img{
  width: 192px;
  height: 220px;
  object-fit: cover;
}

h2{
  color: white;
}
</style>