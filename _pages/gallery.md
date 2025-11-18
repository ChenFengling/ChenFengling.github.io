---
layout: single
title: "Lab Activities"
permalink: /gallery/
author_profile: true
---

📸 Welcome to our lab activities gallery! Here we capture the joyful moments of our team building activities, including delicious dinners and exciting hiking adventures around Beijing.

*2025.11 Happy Autumn out in Xiang Shan!*

<div class="image-gallery">
  <div class="image-row">
    <img src="https://ChenFengling.github.io/_pages/images/dinner-Autumn.jpg" alt="实验室聚餐">
    <img src="https://ChenFengling.github.io/_pages/images/hiking-xiangshan2.jpg" alt="香山爬山">
  </div>
</div>

<video controls width="100%">
  <source src="https://ChenFengling.github.io/_pages/images/hiking-xiangshan2.mp4" type="video/mp4">
</video>

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
  /* 确保图片保持原始比例 */
  object-fit: contain;
  /* 移除任何可能限制比例的属性 */
  max-height: none;
  width: auto;
}

.image-row img:hover {
  transform: scale(1.02);
}

@media (max-width: 768px) {
  .image-row {
    flex-direction: column;
    align-items: center;
  }
  
  .image-row img {
    max-width: 90%;
    margin-bottom: 15px;
    /* 移动端也保持比例 */
    width: 100%;
    height: auto;
  }
}
</style>
