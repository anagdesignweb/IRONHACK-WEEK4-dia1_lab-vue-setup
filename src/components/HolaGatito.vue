<template>
    <h1>Este es mi gatito</h1>
    <div>
        <img :src="imagen" :class="clases">
    </div>

</template>

<script setup>

const imagen = '/src/assets/IMG_2181.JPG';
const clases = ['img-size'];

</script>

<style scoped>
.img-size{
    width: 200px;
}

</style>
