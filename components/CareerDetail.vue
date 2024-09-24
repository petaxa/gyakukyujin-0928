<script setup lang="ts">
const props = defineProps<{
  title: string;
  detailTitle: string;
  details: string[];
}>();
</script>

<template>
  <h1>キャリアビジョン</h1>
  <h2>{{ props.title }}</h2>
  <div class="detail">
    <h3>{{ props.detailTitle }}</h3>
    <p v-for="detail in props.details">{{ detail }}</p>
  </div>
</template>

<style scoped>
.detail {
  margin-top: 3em;
}
</style>
