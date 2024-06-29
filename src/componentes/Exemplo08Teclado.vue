<!-- SCRIPT -->
<script setup>
    function mensagem(){
        alert('Executando a função');
    }
</script>

 <!-- HTML -->
<template>
    <!-- Só mostrará a mensagem se depois da digitação apertar a tecla 'Enter' -->
    <input type="text" @keyup.enter="mensagem">
</template>