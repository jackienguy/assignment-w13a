vbody<template>
    <nav>
        <a href="">Home</a>
        <a href="">About</a>
        <a href="">Contact</a>
    </nav>
</template>

<script>
    export default {
        name: "VueHeader"
    }
</script>

<style scoped>
    nav {
        background-color: teal;
        height: 8vh;
    }

    nav a {
        color: white;
        padding: 20px; 
    }
</style>