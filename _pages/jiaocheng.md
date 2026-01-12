---
layout: archive
title: "教程"
permalink: /jiaocheng/
author_profile: false
classes: wide
redirect_from:
  - /resume
---

<div class="custom-gallery">
  <!-- 第一排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/b6sdpACntc3I2EBpqT8IPh.jpg" alt="图片1">
      <p class="gallery-caption">这里写第一张图片的说明文字</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/yapBEzlIlef470QCUgtcyf.jpg" alt="图片2">
      <p class="gallery-caption">第二张图片的说明文字</p>
    </div>
  </div>

  <!-- 第二排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/li1jDb1CNDGxBliENgfgr1.jpg" alt="图片3">
      <p class="gallery-caption">第三张图片的说明文字</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/ecCpILN7q88mcouU9sTkc1.jpg" alt="图片4">
      <p class="gallery-caption">第四张图片的说明文字</p>
    </div>
  </div>

  <!-- 第三排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/L9I0mhZwe2YY3ZWmehivmT.jpg" alt="图片5">
      <p class="gallery-caption">第五张图片的说明文字</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/uGsEwBvEfnBYWMoZt5O4D5.jpg" alt="图片6">
      <p class="gallery-caption">第六张图片的说明文字</p>
    </div>
  </div>

  <!-- 第四排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/XLEIRVZEfli4V2LZOXqFJf.jpg" alt="图片7">
      <p class="gallery-caption">第七张图片的说明文字</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/qbkerHfgZc0fNVii0xTUpk.jpg" alt="图片8">
      <p class="gallery-caption">第八张图片的说明文字</p>
    </div>
  </div>

  <!-- 第五排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/LDeQWNjvVy45f9bwsu662Q.jpg" alt="图片9">
      <p class="gallery-caption">第九张图片的说明文字</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/RKKbUsSqiWIuqmEXbCqWNd.jpg" alt="图片10">
      <p class="gallery-caption">第十张图片的说明文字</p>
    </div>
  </div>

  <!-- 第六排（只有一张，右边留空） -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/nESbFdDoeImy5dyDHVSPJx.jpg" alt="图片11">
      <p class="gallery-caption">第十一张图片的说明文字</p>
    </div>
    <div class="gallery-item empty"></div> <!-- 占位，保持两列结构 -->
  </div>
</div>

<style>
  .custom-gallery {
    max-width: 1000px;
    margin: 0 auto 2em;
    padding: 0 1em;
  }

  .gallery-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5em 2em;
    margin-bottom: 3em;
  }

  .gallery-item {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .gallery-item img {
    width: 100%;
    height: auto;
    max-height: 350px;
    object-fit: contain;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }

  .gallery-caption {
    margin-top: 1em;
    font-size: 1em;
    line-height: 1.5;
    text-align: center;
    color: #444;
  }

  .gallery-item.empty {
    visibility: hidden;
  }

  @media (max-width: 768px) {
    .gallery-row {
      grid-template-columns: 1fr 1fr;
      gap: 1em 1.2em;
    }
  }
</style>
