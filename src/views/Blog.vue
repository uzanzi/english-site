<script setup>
</script>

<template>
  <div class="container">
    <div class="video">
      <iframe title="YouTube video player" src="https://www.youtube.com/embed/cEmucD8K50Q"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        frameborder="0" allowfullscreen></iframe>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;

  .video {
    text-align: center;
    margin: 120px 0;
  }

  iframe {
    width: 560px;
    height: 315px;
  }
}
</style>