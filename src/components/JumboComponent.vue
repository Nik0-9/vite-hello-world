<template>
    <h2>{{ thisIsJumbo }}</h2>
    <img :src="jumboImage" alt="">
</template>

<script>
    export default {
        name: 'JumboComponent',
        data(){
            return{
                thisIsJumbo: 'JUMBO',
                jumboImage: '/img/jumbo.svg.png',
            }
        }
    }
</script>

<style scoped>
    h2{
        text-align: center;
    }
    img{
        width: 100%;
    }
    
</style>