<template>
    <div>
        <h1>{{ title }}</h1>
    </div>
</template>

<script>
    export default {
        name: 'TitleComponent',
        data(){
            return{
                title: 'La mia prima app con Vite!'
            }
        }
    }
</script>

<style scoped>
    h1{
        text-align: center;
    }
</style>