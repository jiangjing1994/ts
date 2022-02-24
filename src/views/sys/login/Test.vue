<template>
  <div>12334455 {{ loading }}</div>
  <div>12334455 {{ titile }}</div>
</template>
<script lang="ts" setup>
  import { computed } from 'vue';
  const props = defineProps({
    loading: {
      type: Boolean,
    },
  });
  const titile = computed(() => {
    return props.loading;
  });
</script>
