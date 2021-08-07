vbody<template>
    <div>
        <h1>Welcome to My First Vue Assignment!</h1>
        <img src="https://images.unsplash.com/photo-1518247213313-0a400b4936e4?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Happy Face">
    </div>
</template>

<script>
    export default {
        name: "VueBody"
    }
</script>

<style scoped>
    h1 {
        color: darkcyan;
    }
    img {
        border-radius: 5px;
        border: 3px solid greenyellow;
    }
</style>