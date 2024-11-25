<template>
  <NuxtLayout>
    <section>
      {{ error }}
    </section>
  </NuxtLayout>
</template>

<script setup>
defineProps({ error: Object });
</script>
