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
      <img src="/images/https://i.111666.best/image/b6sdpACntc3I2EBpqT8IPh.jpg="图片1">
      <p class="gallery-caption">首先</p>
    </div>
    <div class="gallery-item">
      <img src="/images/image2.jpg" alt="图片2">
      <p class="gallery-caption">第二张图片的说明文字</p>
    </div>
  </div>

  <!-- 第二排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/image3.jpg" alt="图片3">
      <p class="gallery-caption">第三张说明</p>
    </div>
    <div class="gallery-item">
      <img src="/images/image4.jpg" alt="图片4">
      <p class="gallery-caption">第四张说明</p>
    </div>
  </div>

  <!-- 第三排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/image5.jpg" alt="图片5">
      <p class="gallery-caption">第五张说明文字，可以写长一些</p>
    </div>
    <div class="gallery-item">
      <img src="/images/image6.jpg" alt="图片6">
      <p class="gallery-caption">第六张的文字描述</p>
    </div>
  </div>

  <!-- 第四排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/image7.jpg" alt="图片7">
      <p class="gallery-caption">第七张说明</p>
    </div>
    <div class="gallery-item">
      <img src="/images/image8.jpg" alt="图片8">
      <p class="gallery-caption">第八张说明</p>
    </div>
  </div>

  <!-- 第五排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/image9.jpg" alt="图片9">
      <p class="gallery-caption">第九张说明文字</p>
    </div>
    <div class="gallery-item">
      <img src="/images/image10.jpg" alt="图片10">
      <p class="gallery-caption">第十张说明</p>
    </div>
  </div>

  <!-- 第六排（最后一张单独放一排，或你自己调整） -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/image11.jpg" alt="图片11">
      <p class="gallery-caption">第十一张说明文字</p>
    </div>
    <!-- 如果没有第12张，可以留空或删掉这个 div.gallery-item -->
    <div class="gallery-item empty"></div>
  </div>
</div>

<style>
  .custom-gallery {
    max-width: 1000px;          /* 整体宽度，可调小一点如 900px */
    margin: 0 auto 2em;
    padding: 0 1em;
  }

  .gallery-row {
    display: grid;
    grid-template-columns: 1fr 1fr;     /* 固定两列 */
    gap: 1.5em 2em;                     /* 行间距 1.5em，列间距 2em（中间空隙更大） */
    margin-bottom: 3em;                 /* 每对图片组之间的垂直距离 */
  }

  .gallery-item {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .gallery-item img {
    width: 100%;
    height: auto;
    max-height: 350px;                  /* 限制高度，防止图片过大 */
    object-fit: contain;                /* 保持比例不裁剪 */
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
    visibility: hidden;                 /* 最后一排如果只有一张，用空位占位 */
  }

  /* 手机端保持两列（如果觉得挤，可改成 1fr） */
  @media (max-width: 768px) {
    .gallery-row {
      grid-template-columns: 1fr 1fr;
      gap: 1em 1.2em;
    }
  }
</style>
