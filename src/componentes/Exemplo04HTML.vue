<!-- SCRIPT -->
<script setup>
    let texto = '<h1>Aprendendo a diretiva v-html!</h1>';
</script>

<!-- HTML -->
 <template>
    <!-- Foco em estruturas html, no caso uma estrutura que tera o texto -->
    <div v-html="texto"></div> 
    
    <!-- No caso a interpolação de texto não converte em uma estrutura HTML -->
    <div>{{ texto }}</div>
 </template>