<script setup>

const props = defineProps(['src', 'alt'])

</script>

<template>
  <div>
    <img :src="props.src" :alt="props.alt">
  </div>
</template>

<style lang="scss" scoped>
div {
  background-color: white;
  box-shadow: 1px 1px 12px #555;
  margin: 5px;
  text-align: center;

  img {
    max-width: 100%;
  }
}
</style>