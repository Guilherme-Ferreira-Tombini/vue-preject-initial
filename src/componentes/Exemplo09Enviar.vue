<!-- SCRIPT -->
<script setup>
    function validaFormulario(){
        alert('Formulario enviado');
    }
</script>

 <!-- HTML -->
<template>
    <form @submit="validaFormulario">
        <input type="submit" value="Enviar formulario">
    </form>
</template>