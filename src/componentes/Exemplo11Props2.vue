<!-- SCRIPT -->
<script setup>
    const props = defineProps(['nome', 'idade']);
</script>

<!-- HTML -->
<template>
    <h1>{{ nome }}</h1>
    <h1>{{ idade }}</h1>
</template>