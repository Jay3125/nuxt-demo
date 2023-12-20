<template>
      <div>
    <h1>Hello,{{ userName }}</h1>
  </div>
  <br/>
  <h4>Go to 
      <NuxtLink to="/dashboard">dashboard</NuxtLink>
  </h4>
</template>
<script setup>
const userName = 'Chiku'
</script>