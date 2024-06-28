<!-- SCRIPT -->
<script setup>
    import { ref } from 'vue'; 

    let texto = ref(''); // o ref faz nossa variavel ser reativa, ou seja, mudar a cada caractere digitado.
</script>

<!-- HTML -->
 <template>
    <input type="text" v-model="texto">
    <p>{{ texto }}</p>
 </template>