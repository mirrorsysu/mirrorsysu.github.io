<script setup lang="ts">
import BlogProfile from '@/components/BlogProfile.vue'
</script>

<template>
  <div class="blog-container">
    <aside class="sidebar">
        <div class="profile-container"><BlogProfile /></div>
    </aside>
    <main class="content">
      <article>
        <h1>博客文章</h1>
        <section id="article1">
          <h2>文章一</h2>
          <p>这里是文章一的内容...</p>
        </section>
        <section id="article2">
          <h2>文章二</h2>
          <p>这里是文章二的内容...</p>
        </section>
        <section id="article3">
          <h2>文章三</h2>
          <p>这里是文章三的内容...</p>
        </section>
      </article>
    </main>
  </div>
</template>

<style scoped>
.blog-container {
    display: flex;
    flex-direction: row;
    width: 100%;
    min-height: 100%;
}

.sidebar {
    flex: 0 0 350px;
    height: 100%;
    background-color: #f0f0f0;
}

.profile-container {
    width: 300px;
    margin: auto;
}

.content {
    flex: 1; 
    overflow-y: auto;
}


</style>
