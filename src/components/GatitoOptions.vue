<template>
    <h1>Este es mi gatito</h1>
    <div>
        <img :src="imagen" :class="clases">
    </div>

</template>

<script>

import { ref } from 'vue'

export default {

    data(){
        const imagen = ref('/src/assets/IMG_2181.JPG');
        const clases = ['img-size'];
        return {
            imagen, clases
        }
    }
};

</script>

<style scoped>
.img-size{
    width: 200px;
}

</style>