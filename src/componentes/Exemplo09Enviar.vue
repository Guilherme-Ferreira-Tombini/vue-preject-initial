<!-- SCRIPT -->
<script setup>
    function validaFormulario(event){
        alert('Formulario enviado');

        event.preventDefault(); // evita ser redirecionado para outra pagina
    }
</script>

 <!-- HTML -->
<template>
    <form action="www.google.com" @submit="validaFormulario">
        <input type="submit" value="Enviar formulario">
    </form>
</template>