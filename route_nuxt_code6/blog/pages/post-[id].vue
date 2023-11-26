<template>
    <h2>This is a POST page</h2>
    {{ $route.params.id }}

</template>
<script setup>
const route = useRoute();
console.log(route.params.id);
definePageMeta({
    validate: async(route) =>{
        return /^\d+$/.test(route.params.id);
    }
})
</script>