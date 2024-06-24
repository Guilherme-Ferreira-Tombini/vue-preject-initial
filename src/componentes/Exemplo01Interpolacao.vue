<!-- SCRIPT -->
<script setup>
  let nome = 'Rebeca';
  let idade = 32;
  let numero1 = 20;
  let numero2 = 10;
</script>

<!-- HTML -->
 <template>
  <p>{{'Olá '+nome+", sua idade é "+idade}}</p>
  <p>{{ numero1+numero2 }}</p>
 </template>
