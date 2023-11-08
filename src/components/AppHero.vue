<template>
    <main>
    </main>
    <p>
        {{ hero }}
    </p>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                hero: 'Benvenuto'
            }
        }
    }
</script>

<style lang="css">
    main{
        background-image: url('/images/bg-img.jpg');
        width: 100vw;
        height: 500px;
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        filter: blur(3px);
    }
    p{
        background-color: #E9A6AC;
        color: #009BDA;
        padding: 15px;
        border-radius: 10px;
        font-size: 80px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>