<script>
    export default {
        name: 'AppJumbo'
    }
</script>

<template>
    <section class="jumbo border border-2 border-danger">
        <img class="img-fluid" src="../assets/vite.jpg" alt="">
        <div>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Architecto illo nihil nulla quis voluptate consequuntur minus accusantium deserunt soluta aliquid cupiditate eo!</div>
    </section>
</template>

<style scoped>

.jumbo {
    width: 50%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    place-items: center;
    padding: 2rem;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 1.5rem;
    border-radius: 2rem;
}

</style>