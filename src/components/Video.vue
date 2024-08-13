<template>
  <video class="video_background" src="../assets/video/3051492-hd_1920_1080_25fps.mp4" autoplay loop muted></video>
</template>

<script setup>

</script>

<style scoped>
    .video_background {
      height: 100vh;
      width: 100vw;
      object-fit: cover;
      position: fixed;
      left: 0;
      right: 0;
      top: 0;
      bottom: 0;
      z-index: -1;
    }
</style>