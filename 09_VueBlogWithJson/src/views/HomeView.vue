<script setup>
    import TheWelcome from '@/components/home/TheWelcome.vue';
</script>

<template>
    <main>
        <TheWelcome/>
    </main>
</template>

<style scoped>
  main{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 70%;
    margin-top: 5%;
    margin-left: auto;
    margin-right: auto;
    border-style:double;
  }
</style>