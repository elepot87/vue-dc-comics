<template>
  <div>
    <img :src="thumb" :alt="series" />
    <div class="title-comics">
      {{ series }}
    </div>
  </div>
</template>

<script>
export default {
  name: "Comics",
  props: {
    thumb: String,
    series: String,
  },
};
</script>

<style scoped lang="scss"></style>
