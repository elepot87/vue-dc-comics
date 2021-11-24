<template>
  <div>
    <img :src="url" :alt="title" />
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

<style scoped lang="scss"></style>
