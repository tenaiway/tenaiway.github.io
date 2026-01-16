---
layout: archive
title: "教程"
permalink: /jiaocheng/
author_profile: false
classes: wide
redirect_from:
  - /resume
---

{% include base_path %}
## 对于Kelivo使用10dianapi模型的教程

**帮助您快速在Kelivo应用中使用10dianapi核心功能的完整流程**

为什么选择 Kelivo 集成 10dianapi 模型? Kelivo 平台将**10dianapi**强大的人工智能模型无缝集成到您的手机中，提供以下优势： 

1.开箱即用的体验:无需复杂配置，直接在 Kelivo 工作区调用 10dianapi 的多种AI能力 

2.统一的环境:在同一平台完成从模型调用到应用 部署的完整流程 

3简化的认证管理:集中管理的密钥和权限控制，保障使用安全

<div class="custom-gallery">
  <!-- 第一排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-27-21-030_mark.via_1768196137864edit.jpg" alt="步骤1">
      <p class="gallery-caption">打开10dianapi网站或软件, 点击头像, 再点击“令牌管理”</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-27-37-960_mark.via_1768196236111edit.jpg" alt="步骤2">
      <p class="gallery-caption">点击“显示操作项”</p>
    </div>
  </div>

  <!-- 第二排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-27-48-517_mark.via_1768196324183edit.jpg" alt="步骤3">
      <p class="gallery-caption">点击“添加令牌”</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-28-59-439_mark.via_1768196576300edit.jpg" alt="步骤4">
      <p class="gallery-caption">输入名称，其他的不要点</p>
    </div>
  </div>

  <!-- 第三排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-18-921_com.psyche.kelivo_1768196651328edit.jpg" alt="步骤5">
      <p class="gallery-caption">打开Kelivo, 注册/登录账户点击左上角的三条杠</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-25-754_com.psyche.kelivo_1768196695329edit.jpg" alt="步骤6">
      <p class="gallery-caption">点击设置 (图标很像齿轮)</p>
    </div>
  </div>

  <!-- 第四排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-36-990_com.psyche.kelivo_1768196729865edit.jpg" alt="步骤7">
      <p class="gallery-caption">点击“供应商”</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-48-178_com.psyche.kelivo_1768196765483edit.jpg" alt="步骤8">
      <p class="gallery-caption">点击第一个“OpenAI”</p>
    </div>
  </div>

  <!-- 第五排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-30-09-153_com.psyche.kelivo_1768196935689edit.jpg" alt="步骤9">
      <p class="gallery-caption">输入刚才在10dianapi创建的令牌里的Key（密钥）</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-49-34-093_com.psyche.kelivo_1768197027681edit.jpg" alt="步骤10">
      <p class="gallery-caption">输入10dianapi的网址，后面必须加/v1，v是小写，符号一个都不能少!</p>
    </div>
  </div>

  <!-- 第六排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-49-44-808_com.psyche.kelivo_1768278720513edit.jpg" alt="步骤11">
      <p class="gallery-caption">全部完成后，再点击“模型”，这时候再点“获取”就会出现模型了，获取以使用吧~</p>
    </div>
    <div class="gallery-item empty"></div>
  </div>
</div>

<style>
  .custom-gallery {
    max-width: 1100px;
    margin: 0 auto 3em;
    padding: 0 1em;
  }

  .gallery-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2.5em 4em; /* 加大水平间隙，让中间更空旷 */
    margin-bottom: 5em; /* 排与排之间更大距离 */
  }

  .gallery-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    /* 完全去掉背景、内边距、圆角、阴影，让框贴合图片大小 */
    background: none;
    padding: 0;
    border-radius: 0;
    box-shadow: none;
  }

  .gallery-item img {
    width: 100%;
    height: auto;
    max-height: 450px; /* 稍加大高度限制，避免图片过小 */
    object-fit: contain;
    border-radius: 12px;
    box-shadow: 0 6px 18px rgba(0,0,0,0.25); /* 只给图片加更明显的阴影 */
  }

  .gallery-caption {
    margin-top: 1.5em; /* 文字和图片之间距离 */
    font-size: 1.1em;
    line-height: 1.6;
    text-align: center;
    color: #ddd;
    background: none; /* 文字无背景 */
    padding: 0;
  }

  .gallery-item.empty {
    visibility: hidden;
  }

  @media (max-width: 768px) {
    .gallery-row {
      grid-template-columns: 1fr 1fr;
      gap: 1.8em 2.5em;
    }
  }
</style>
<style>
  body {
    background: linear-gradient(to bottom, #0f0c29, #3a1c5c, #4a148c) !important;
    background-attachment: fixed !important;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const elements = document.querySelectorAll("h1, h2, p, .custom-gallery");

    const observer = new IntersectionObserver((entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          // 每次进入视口都重新触发动画
          entry.target.classList.remove("visible");
          // 强制浏览器重绘，让 transition 能重新开始
          void entry.target.offsetWidth;
          entry.target.classList.add("visible");
        } else {
          // 离开视口时移除类，下次进入再动画
          entry.target.classList.remove("visible");
        }
      });
    }, { threshold: 0.1 });

    elements.forEach((el) => {
      observer.observe(el);
    });
  });
</script>

<style>
  /* 滑动淡入效果 */
  h1, h2, p, .custom-gallery {
    opacity: 0;
    transform: translateY(40px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }

  h1.visible, h2.visible, p.visible, .custom-gallery.visible {
    opacity: 1;
    transform: translateY(0);
  }
</style>
