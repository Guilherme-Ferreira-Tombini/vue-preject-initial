<!-- SCRIPT -->
<script setup>
    import Exemplo11Props2 from './Exemplo11Props2.vue';

    // VARIAVEL QUE PASSARA DE FORMA DINAMICA
    let cidade = "São Paulo";
    let cidades =["Curitiba", "Florianopolis", "Rio de Janeiro"];

    function mensagem(){
        alert("Função criada para exemplo de props")
    }
</script>

<!-- HTML -->
<template>
    <Exemplo11Props2 nome="Ralf" idade="33" :cidade="cidade" :cidades="cidades" :funcao="mensagem"/>
</template>