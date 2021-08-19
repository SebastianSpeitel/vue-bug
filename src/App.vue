<template>
  <div>
    <span v-for="s in ['a', 'b']" v-text="s"></span>
  </div>
</template>

<script setup lang="ts">
const message = "Hello Vue!";
</script>

<!-- Works with:   
<script lang="ts">
export default {
  setup() {
    return {};
  }
};
</script>
-->
