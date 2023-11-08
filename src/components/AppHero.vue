<template>
    <main>
    </main>
    <div>
        <h3>{{ hero }}</h3>
    </div>
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
    h3{
        background-color: white;
        padding: 10px;
        border-radius: 10px;
        font-size: 100px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>