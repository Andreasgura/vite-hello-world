<template>
    <div>
        <main>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, tempore quibusdam fugit repellendus veniam earum neque expedita tenetur ab dicta?
            </p>
            <h2>{{ imgTitle }}</h2>
            <img :src="img" alt="avatar">
        </main>
    </div>
</template>

<script>
    export default {
        name : 'AppMain',
        props: ['imgTitle'],
        data(){
            return {
                img : './images/avatar_1.jpg'
            }
        }
    }
</script>

<style  scoped>

</style>