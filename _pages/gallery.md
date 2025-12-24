---
layout: single
title: "Lab Activities"
permalink: /gallery/
author_profile: true
---

📸 Welcome to our lab activities gallery! Here we capture the joyful moments of our team building activities, including delicious dinners and exciting hiking adventures around Beijing.

*2025.12 Weekly badminton in the lab!*

<div class="image-gallery">
  <div class="image-row">
    <img src="https://ChenFengling.github.io/_pages/images/badminton.jpg" alt="hiking">
  </div>
</div>


*2025.11 Happy Autumn out in Xiang Shan and China National Botanical Garden!*


<div class="image-gallery">
  <div class="image-row">
    <img src="https://ChenFengling.github.io/_pages/images/hiking-xiangshan2.jpg" alt="hiking">
    <img src="https://ChenFengling.github.io/_pages/images/20251111-lunch.jpg" alt="happy lunch">   
  </div>
</div>

<div class="video-container">
  <video controls>
    <source src="https://ChenFengling.github.io/_pages/images/hiking-xiangshan.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>


*Last updated: {{ site.time | date: '%B %d, %Y' }}*

<style>
.image-gallery {
  margin: 2rem 0;
}

.image-row {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.image-row img {
  max-width: 45%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
  object-fit: contain;
  max-height: none;
  width: auto;
}

.image-row img:hover {
  transform: scale(1.02);
}

/* 视频容器样式 */
.video-container {
  margin: 2rem auto;
  text-align: center;
  max-width: 400px; /* 限制竖版视频的最大宽度 */
  width: 100%;
}

.video-container video {
  width: 100%;
  height: auto;
  max-height: 600px; /* 限制竖版视频的最大高度 */
  border-radius: 12px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.15);
  background: #000;
}

.video-caption {
  margin-top: 12px;
  font-style: italic;
  color: #666;
  font-size: 0.95rem;
  text-align: center;
}

/* 平板设备适配 */
@media (max-width: 1024px) {
  .video-container {
    max-width: 350px;
  }
}

@media (max-width: 768px) {
  .image-row {
    flex-direction: column;
    align-items: center;
  }
  
  .image-row img {
    max-width: 90%;
    margin-bottom: 15px;
    width: 100%;
    height: auto;
  }
  
  .video-container {
    max-width: 300px;
    margin: 1.5rem auto;
  }
  
  .video-container video {
    max-height: 500px;
  }
}

/* 小屏手机适配 */
@media (max-width: 480px) {
  .video-container {
    max-width: 280px;
  }
  
  .video-container video {
    max-height: 450px;
    border-radius: 8px;
  }
  
  .video-caption {
    font-size: 0.9rem;
    margin-top: 8px;
  }
}
</style>
