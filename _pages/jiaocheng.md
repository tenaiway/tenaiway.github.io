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

<style>
:root{
  --bg-main:#f4f8ff;
  --section-bg:#ffffff;
  --text-main:#0f172a;
  --text-secondary:#475569;
  --primary:#2563eb;
  --accent:#38bdf8;
  --border-soft:rgba(0,0,0,.06);
}

body{
  margin:0;
  font-family: Inter, system-ui, -apple-system, "Segoe UI", sans-serif;
  background:var(--bg-main);
  color:var(--text-main);
  line-height:1.55;
  overflow-x:hidden; /* 防止视差效果导致的横向滚动 */
}

section{
  padding:4rem 1.5rem;
}

.container{
  max-width:1100px;
  margin:0 auto;
}

@media (min-width:1440px){
  .container{ max-width:1200px; }
}

@media (max-width:640px){
  .block-title{ font-size:1.6rem; }
  .block-subtitle{ font-size:1rem; }
  .card{ padding:1.4rem; }
}

/* Animations */
@keyframes fadeUp{
  to{
    opacity:1;
    transform:translateY(0);
  }
}

@keyframes gradientMove{
  0%{background-position:0% 50%;}
  50%{background-position:100% 50%;}
  100%{background-position:0% 50%;}
}

/* Hero */
.hero{
  padding-top:5rem;
  text-align:center;
  position:relative;
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  overflow:hidden;
}

.hero::before{
  content:"";
  position:absolute;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background:linear-gradient(135deg, #e0f2fe 0%, #f0f9ff 100%);
  z-index:-1;
  transform:translateZ(-1px) scale(2); /* 视差背景层 */
  transform-origin:0 0;
}

.hero-content{
  transform:translateZ(0); /* 正常滚动层 */
  z-index:2;
}

.logo-text{
  font-size:2.6rem;
  font-weight:700;
  background:linear-gradient(90deg,#7dd3fc,#60a5fa,#7dd3fc);
  background-size:200% 200%;
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  margin-bottom:1.2rem;
  opacity:0;
  transform:translateY(8px);
  animation:fadeUp 0.7s ease forwards, gradientMove 12s linear infinite;
}

.hero h1{
  font-size:2.2rem;
  font-weight:700;
  margin-bottom:.6rem;
  opacity:0;
  transform:translateY(8px);
}

.hero p{
  font-size:1.15rem;
  color:var(--text-secondary);
  max-width:720px;
  margin:0 auto;
  opacity:0;
  transform:translateY(8px);
}

/* 板块容器添加视差效果 */
.parallax-section{
  position:relative;
  transform-style:preserve-3d;
  perspective:1px;
}

.parallax-element{
  transform:translateZ(-0.5px) scale(1.5);
}

.parallax-element.reverse{
  transform:translateZ(-1px) scale(2);
}

.parallax-element.normal{
  transform:translateZ(0);
}

/* Titles */
.block-title{
  font-size:1.85rem;
  font-weight:650;
  margin-bottom:.6rem;
  opacity:0;
  transform:translateY(12px);
}

.block-subtitle{
  font-size:1.1rem;
  color:var(--text-secondary);
  max-width:860px;
  opacity:0;
  transform:translateY(12px);
  margin-bottom:2rem;
}

/* Grid / Card */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:1.6rem;
}

.card{
  background:var(--section-bg);
  border:1px solid var(--border-soft);
  border-radius:14px;
  padding:1.8rem;
  opacity:0;
  transform:translateY(12px);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  position:relative;
  z-index:1;
}

.card h3{
  font-size:1.15rem;
  margin-bottom:.4rem;
}

.card p{
  font-size:.95rem;
  color:var(--text-secondary);
}

/* Card hover effect */
.card:hover{
  transform:translateY(-4px);
  box-shadow:0 12px 24px rgba(56,189,248,0.25);
}

/* Stats */
.stats{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:1.6rem;
}

.stat{
  background:var(--section-bg);
  border:1px solid var(--border-soft);
  border-radius:14px;
  padding:1.6rem;
  display:flex;
  justify-content:space-between;
  align-items:center;
  opacity:0;
  transform:translateY(12px);
  position:relative;
  z-index:1;
}

.stat strong{
  font-size:1.7rem;
  color:var(--primary);
}

.stat span{
  font-size:.95rem;
  color:var(--text-secondary);
}

.stat svg{
  width:26px;
  height:26px;
  color:var(--accent);
}

/* Community */
.community{
  background:var(--section-bg);
  border-top:1px solid var(--border-soft);
  border-bottom:1px solid var(--border-soft);
  text-align:center;
  padding:3rem 1.5rem;
  position:relative;
  transform-style:preserve-3d;
  perspective:1px;
}

.community::before{
  content:"";
  position:absolute;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background:linear-gradient(135deg, #dbeafe 0%, #e0f2fe 100%);
  z-index:-1;
  transform:translateZ(-0.5px) scale(1.5);
}

.community h2{
  font-size:1.9rem;
  margin-bottom:.8rem;
  transform:translateZ(0);
}

.community p{
  font-size:1.1rem;
  color:var(--text-secondary);
  transform:translateZ(0);
}

.group-id{
  margin-top:1rem;
  font-size:1.4rem;
  font-weight:600;
  color:var(--primary);
  transform:translateZ(0);
}

footer{
  padding:3rem 1.5rem;
  text-align:center;
  font-size:.85rem;
  color:var(--text-secondary);
  position:relative;
  transform-style:preserve-3d;
  perspective:1px;
}

.footer-content{
  transform:translateZ(0);
}

/* 视差效果在移动设备上的适配 */
@media (max-width: 768px) {
  .hero {
    height: auto;
    min-height: 80vh;
    padding: 3rem 1.5rem;
  }
  
  .hero::before {
    transform: translateZ(-1px) scale(1.5); /* 移动端调整视差强度 */
  }
  
  .parallax-element {
    transform: translateZ(0) scale(1); /* 移动端禁用视差效果以提升性能 */
  }
  
  .parallax-element.reverse {
    transform: translateZ(0) scale(1);
  }
  
  .community::before {
    transform: translateZ(-0.3px) scale(1.3); /* 移动端调整视差强度 */
  }
  
  /* 禁用视差相关的transform-style和perspective */
  .parallax-section,
  .community,
  footer {
    transform-style: flat;
    perspective: none;
  }
}

/* 高性能设备增强体验 */
@media (min-width: 769px) and (min-height: 600px) {
  .hero {
    height: 100vh;
  }
  
  .parallax-section,
  .community,
  footer {
    transform-style: preserve-3d;
    perspective: 1px;
  }
  
  .parallax-element {
    transform: translateZ(-0.5px) scale(1.5);
  }
  
  .parallax-element.reverse {
    transform: translateZ(-1px) scale(2);
  }
  
  .parallax-element.normal {
    transform: translateZ(0);
  }
}

/* 降低动画效果的设备适配 */
@media (prefers-reduced-motion: reduce) {
  .hero::before,
  .parallax-element,
  .community::before {
    transform: translateZ(0) scale(1);
    animation: none;
  }
  
  .parallax-section,
  .community,
  footer {
    transform-style: flat;
    perspective: none;
  }
}
</style>
