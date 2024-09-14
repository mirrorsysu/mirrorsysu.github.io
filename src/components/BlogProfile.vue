<script setup lang="ts">
</script>

<template>
  <div class="profile-card">
    <img src="@/assets/avatar_300_300.jpg" alt="头像" class="avatar">
    <h2 class="name">Mirrorhye</h2>
    <p class="job-title">Fresh Software Engineer</p>
    <p class="location">
      <i class="location-icon"></i>
      Guangzhou
    </p>
    <div class="stats">
      <div class="stat-item">
        <span class="stat-value">16</span>
        <span class="stat-label">文章</span>
      </div>
      <div class="stat-item">
        <span class="stat-value">0</span>
        <span class="stat-label">分类</span>
      </div>
      <div class="stat-item">
        <span class="stat-value">9</span>
        <span class="stat-label">标签</span>
      </div>
    </div>
    <button class="follow-button">关注我</button>
    <div class="social-links">
      <a href="#" class="social-icon github"></a>
      <a href="#" class="social-icon facebook"></a>
      <a href="#" class="social-icon twitter"></a>
      <a href="#" class="social-icon weibo"></a>
      <a href="#" class="social-icon rss"></a>
    </div>
  </div>
</template>

<style scoped>
.profile-card {
  width: 300px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.avatar {
  width: 100px;
  height: 100px;
  border-radius: 3px;
  object-fit: cover;
  margin-bottom: 15px;
}

.name {
  font-size: 1.5em;
  margin-bottom: 5px;
}

.job-title {
  color: #666;
  margin-bottom: 10px;
}

.location {
  color: #666;
  margin-bottom: 15px;
}

.stats {
  display: flex;
  justify-content: space-around;
  margin-bottom: 20px;
}

.stat-item {
  display: flex;
  flex-direction: column;
}

.stat-value {
  font-size: 1.2em;
  font-weight: bold;
}

.stat-label {
  font-size: 0.8em;
  color: #666;
}

.follow-button {
  background-color: #1da1f2;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 20px;
  cursor: pointer;
  margin-bottom: 15px;
}

.social-links {
  display: flex;
  justify-content: center;
}

.social-icon {
  width: 24px;
  height: 24px;
  margin: 0 5px;
  background-size: cover;
}

.github { background-image: url('path/to/github-icon.png'); }
.facebook { background-image: url('path/to/facebook-icon.png'); }
.twitter { background-image: url('path/to/twitter-icon.png'); }
.weibo { background-image: url('path/to/weibo-icon.png'); }
.rss { background-image: url('path/to/rss-icon.png'); }
</style>
