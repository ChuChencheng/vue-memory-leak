<template>
  <div class="hello">
    <select>
      <option value="top">top</option>
      <option value="center">center</option>
      <option value="bottom">bottom</option>
    </select>
    <div v-for="item in 5000" :key="item">{{item}}</div>
  </div>
</template>

<script lang="ts">
export default {
  name: "SelectPage",
};
</script>
