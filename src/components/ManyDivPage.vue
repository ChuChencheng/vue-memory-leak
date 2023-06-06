<template>
  <div class="hello">
    <div v-for="item in 50000" :key="item">{{item}}</div>
  </div>
</template>

<script lang="ts">
export default {
  name: "ManyDivPage",
};
</script>
