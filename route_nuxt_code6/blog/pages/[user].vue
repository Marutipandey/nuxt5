<template>
    <h2>This is a USER page</h2>
    {{ $route.params.user}}

</template>
<script setup>
const route =useRoute();
console.log(route.params.user);


</script>