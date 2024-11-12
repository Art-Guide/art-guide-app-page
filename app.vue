<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup>
import { onMounted } from "vue";
import { useFlowbite } from "~/composables/useFlowbite";
onMounted(() => {
  useFlowbite(() => {
    initFlowbite();
  });
});
</script>