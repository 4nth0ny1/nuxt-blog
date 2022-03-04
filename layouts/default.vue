<template>
    <div class="container">
        <AppHeader />
        <nuxt/>
    </div>
</template>

<script>
    import AppHeader from "../components/AppHeader"
    export default {
        components: {
            AppHeader
        }
    }
</script>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    h1, h2, h3, p, li {
        font-family: 'Poppins', sans-serif;
    }
</style>