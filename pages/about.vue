<script setup>
function enableCustomLayout() {
  setPageLayout('custom');
}
// definePageMeta({
//   layout: false,
// });
</script>
<template>
  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>