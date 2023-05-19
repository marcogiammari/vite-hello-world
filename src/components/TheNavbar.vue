<script>
    export default {
        name: 'TheNavbar'
    }
</script>

<template>
    <nav>
        <div><a class="p-2 rounded-3" href="#">home</a></div>
        <div><a class="p-2 rounded-3" href="#">contatti</a></div>
    </nav>
</template>

<style scoped>
    nav {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size: 2rem;
        color: antiquewhite;
        background: linear-gradient(to right, #5f2c82, #49a09d);
        display: flex;
        justify-content: space-between;
        padding: 1rem 3rem;
    }

    a {
        all: unset;
        font-size: 1.5rem;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        border: 1px solid antiquewhite;
        cursor: pointer;
    }

    a:hover {
        background-color: rgb(255, 230, 0);
        box-shadow: 0 0 5px yellow;
        color: black;
    }
</style>