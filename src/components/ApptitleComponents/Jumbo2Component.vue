<template>
    <img :src="jumboImage" alt="">
</template>

<script>
export default {
    name: 'Jumbo2Component',
    data() {
        return {
            jumboImage: '/img/jumbo.svg.png',
        }
    }
}
</script>

<style scoped>
h2 {
    text-align: center;
}

img {
    /* background-color: brown; */
    width: 100%;
}
</style>