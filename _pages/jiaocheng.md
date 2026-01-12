---
layout: archive
title: "教程"
permalink: /jiaocheng/
author_profile: false
classes: wide
redirect_from:
  - /resume
---
1
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
      <img src="https://i.111666.best/image/b6sdpACntc3I2EBpqT8IPh.jpg" alt="图片1">
      <p class="gallery-caption">打开10dianapi网站或软件，点击头像，再点击“令牌管理”</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/yapBEzlIlef470QCUgtcyf.jpg" alt="图片2">
      <p class="gallery-caption">点击“显示操作项”</p>
    </div>
  </div>

  <!-- 第二排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/li1jDb1CNDGxBliENgfgr1.jpg" alt="图片3">
      <p class="gallery-caption">点击“添加令牌”</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/ecCpILN7q88mcouU9sTkc1.jpg" alt="图片4">
      <p class="gallery-caption">随便输入一个名词，其他的不要点</p>
    </div>
  </div>

  <!-- 第三排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/L9I0mhZwe2YY3ZWmehivmT.jpg" alt="图片5">
      <p class="gallery-caption">打开Kelivo，注册/登录账户点击左上角的三条杠</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/uGsEwBvEfnBYWMoZt5O4D5.jpg" alt="图片6">
      <p class="gallery-caption">点击设置（图标很想齿轮）</p>
    </div>
  </div>

  <!-- 第四排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/XLEIRVZEfli4V2LZOXqFJf.jpg" alt="图片7">
      <p class="gallery-caption">点击“供应商”</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/qbkerHfgZc0fNVii0xTUpk.jpg" alt="图片8">
      <p class="gallery-caption">点击第一个“OpenAI</p>
    </div>
  </div>

  <!-- 第五排 -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/LDeQWNjvVy45f9bwsu662Q.jpg" alt="图片9">
      <p class="gallery-caption">输入刚才在10dianapi创建的令牌里的Key</p>
    </div>
    <div class="gallery-item">
      <img src="https://i.111666.best/image/RKKbUsSqiWIuqmEXbCqWNd.jpg" alt="图片10">
      <p class="gallery-caption">输入10dianapi的网址，后面必须加/v1，v是小写，符号一个都不能少！</p>
    </div>
  </div>

  <!-- 第六排（只有一张，右边留空） -->
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="https://i.111666.best/image/nESbFdDoeImy5dyDHVSPJx.jpg" alt="图片11">
      <p class="gallery-caption">全部完成后，再点击“模型”，这时候再点“获取”就会出现模型了，获取以使用吧~</p>
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
