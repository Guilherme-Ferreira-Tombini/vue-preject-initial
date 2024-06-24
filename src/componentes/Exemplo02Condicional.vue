<!-- SCRIPT -->
<script setup>
    let exibir = true;
    let media = 10;
</script>

<!-- HTML -->
 <template>
    <h1 v-if="exibir">Olá usuário</h1>

    <!-- Utilizando comandos de "if" e "else" para comparações -->
    <p v-if="media >= 7">Aprovado(a)</p>
    <p v-else-if="media < 7 && media >= 3">Em exame</p>
    <p v-else>Reprovado(a)</p>
 </template>