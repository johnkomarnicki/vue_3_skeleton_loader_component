<template>
  <div class="user-card">
    <div class="card-avatar">
      <AnimatedPlaceholder
        height="100px"
        width="100px"
        borderRadius="50%"
      />
    </div>
    <div class="card-info">
      <AnimatedPlaceholder height="36px" width="200px" />
      <div class="summary-placeholder">
        <AnimatedPlaceholder height="16px" />
        <AnimatedPlaceholder height="16px" />
        <AnimatedPlaceholder height="16px" />
      </div>
    </div>
  </div>
</template>

<script setup>
import AnimatedPlaceholder from "./AnimatedPlaceholder.vue";
</script>

<style scoped>
.summary-placeholder {
  display: flex;
  flex-direction: column;
  gap: 8px;
  width: 100%;
}
</style>
