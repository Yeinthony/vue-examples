<template>
  <div class="post-card">
    <h3>Titulo</h3>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam laboriosam natus recusandae impedit exercitationem aliquam sunt dolores quaerat quas, officia nulla obcaecati, voluptatibus mollitia inventore debitis dolore corrupti amet! Voluptatem.</p>
    <PostButton />
  </div>
</template>

<script lang="ts" setup>
  import PostButton from './PostButton.vue';
</script>

<style scoped>
  .post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
  }
</style>