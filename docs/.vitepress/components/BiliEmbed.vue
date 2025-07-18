<template>
  <div style="position: relative; padding-bottom: 56.25%; height: 0">
    <iframe
      :src="`//player.bilibili.com/player.html?isOutside=true&bvid=${bvId}`"
      scrolling="no"
      border="0"
      frameborder="no"
      framespacing="0"
      allowfullscreen="true"
      style="
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
      "></iframe>
  </div>
</template>

<script setup>
defineProps({
  bvId: String,
});
</script>
