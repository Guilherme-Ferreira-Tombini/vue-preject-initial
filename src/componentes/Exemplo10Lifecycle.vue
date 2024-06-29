<!-- SCRIPT -->
<script setup>
    import { onMounted, ref } from 'vue'; 

    let texto = ref('Hello world!'); // o ref faz nossa variavel ser reativa, ou seja, mudar a cada caractere digitado.

    //Lifecycle onMounted
    onMounted(()=>{
        setTimeout(() => {
            texto.value = 'Alterando texto';
        }, 3000);
    })
</script>

<!-- HTML -->
 <template>
    <h1>{{ texto }}</h1>
 </template>