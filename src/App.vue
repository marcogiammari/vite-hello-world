<script>
import TheNavbar from './components/TheNavbar.vue';
import AppTitle from './components/AppTitle.vue'; 
import AppJumbo from './components/AppJumbo.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    TheNavbar,
    AppTitle,
    AppJumbo,
    AppFooter
  }

}
</script>


<template>
  <header>
    <TheNavbar />
    <AppTitle />
    <AppJumbo />
  </header>

  <main class="fs-5 p-5 rounded-4">
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
    gap: 3rem;
  }

  main {
    width: 70%;
    margin: 0 auto;
    background: #9198e5;
  }

</style>
