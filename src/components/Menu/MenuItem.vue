<script setup>
const props = defineProps (["title"])
</script>

<template>
    <a href="#"> {{ props.title }}</a>
</template>

<style scoped> 
a {
    margin: 0 20px; 
    padding: 8px 20px;
    background-color:brown;

}
</style>