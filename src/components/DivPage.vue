<template>
  <div class="hello">
    <div v-for="item in 5000" :key="item">{{item}}</div>
  </div>
</template>

<script lang="ts">
export default {
  name: "DivPage",
};
</script>
