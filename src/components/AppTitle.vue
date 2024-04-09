<template>
    <div>
        <header>
            <h1>{{ myTitle }}</h1>
        </header>
    </div>
</template>

<script>
    export default {
        name: 'AppTitle',
        data(){
            return {
                myTitle : 'La mia prima app con Vite!'
            }
        }
    }
</script>

<style scoped>

</style>