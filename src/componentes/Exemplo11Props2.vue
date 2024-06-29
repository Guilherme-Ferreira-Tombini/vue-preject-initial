<!-- SCRIPT -->
<script setup>
    const props = defineProps(['nome', 'idade', 'cidade', 'cidades', 'funcao']);
</script>

<!-- HTML -->
<template>
    <h1>{{ nome }}</h1>
    <h1>{{ idade }}</h1>
    <h1>{{ cidade }}</h1>

    <ul>
        <li v-for="v of cidades">{{ v }}</li>
    </ul>

    <button @click="funcao">Clique aqui</button>
</template>