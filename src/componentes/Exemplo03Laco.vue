<!-- SCRIPT -->
<script setup>
    let nomes = ['Alice', 'Bruna', 'Caio', 'Daniel', 'Ellen'];
</script>

<!-- HTML -->
 <template>
    <ul>
        <!-- Utilização de um v-for para apresentar um vetor de nomes -->
        <li v-for="i in nomes">{{ i }}</li>
    </ul>
 </template>