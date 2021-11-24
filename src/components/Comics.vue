<template>
  <div class="card">
    <div class="container-img">
      <img :src="url" :alt="title" />
    </div>
    <div class="title-comics">
      {{ title }}
    </div>
  </div>
</template>

<script>
export default {
  name: "Comics",
  props: {
    url: String,
    title: String,
  },
};
</script>

<style scoped lang="scss">
@import "@/styles/variables";
@import "@/styles/comics";
</style>
