<script setup>
import AppNavbar from './components/AppNavbar.vue';
import AppTitle from './components/AppTitle.vue'; 
import AppJumbo from './components/AppJumbo.vue';
import AppFooter from './components/AppFooter.vue';
</script>

<template>
  <header>
    <AppNavbar />
    <AppTitle />
    <AppJumbo />
  </header>

  <main>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro possimus commodi, aut est aliquid saepe sequi minima cumque unde temporibus impedit obcaecati doloremque soluta fugiat delectus non maxime rem magni.
    Vero quaerat voluptates odio perspiciatis illo assumenda natus reiciendis pariatur consequuntur mollitia veniam, dicta enim quod. Est veritatis maiores nihil, illum excepturi officiis natus. Praesentium fugiat quaerat incidunt nostrum aliquid!
    Quam qui odit facere sint ullam dolorem quod ad labore deleniti quae ratione quo vel praesentium voluptate minima impedit, totam ducimus pariatur non consequuntur accusantium incidunt perferendis nihil! Suscipit, ipsum!
    Tenetur, asperiores possimus? Similique recusandae ipsum fuga repellendus, inventore aut veritatis eum dolore esse libero nisi impedit hic? Debitis, distinctio fugiat nostrum ex sed molestias recusandae consectetur numquam porro quisquam.
    Commodi inventore earum quis cupiditate cumque possimus est, temporibus neque? Dolor ducimus, consectetur numquam nulla nam iusto eum? Id aperiam placeat iusto tempore repudiandae officia nam unde nisi atque adipisci?
  </main>

  <AppFooter />

</template>

<style scoped>
  header {
    display: flex;
    flex-direction: column;
    gap: 5rem;
  }

  main {
    width: 70%;
    font-size: 2rem;
    margin: 0 auto;
  }
</style>
