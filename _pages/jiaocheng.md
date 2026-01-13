---
layout: archive
title: "教程"
permalink: /jiaocheng/
author_profile: false
classes: wide
redirect_from:
  - /resume
hide_title_underline: true
---
## 对于Kelivo使用10dianapi模型的教程

**帮助您快速在Kelivo应用中使用10dianapi核心功能的完整流程**

为什么选择 Kelivo 集成 10dianapi 模型? Kelivo 平台将**10dianapi**强大的人工智能模型无缝集成到您的手机中，提供以下优势： 

1.开箱即用的体验:无需复杂配置，直接在 Kelivo 工作区调用 10dianapi 的多种AI能力 

2.统一的环境:在同一平台完成从模型调用到应用 部署的完整流程 

3简化的认证管理:集中管理的密钥和权限控制，保障使用安全

<div class="tutorial-gallery">
  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-27-21-030_mark.via_1768196137864edit.jpg" alt="步骤1">
      <p class="caption">打开10dianapi网站或软件, 点击头像, 再点击“令牌管理”</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-27-37-960_mark.via_1768196236111edit.jpg" alt="步骤2">
      <p class="caption">点击“显示操作项”</p>
    </div>
  </div>

  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-27-48-517_mark.via_1768196324183edit.jpg" alt="步骤3">
      <p class="caption">点击“添加令牌”</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-28-59-439_mark.via_1768196576300edit.jpg" alt="步骤4">
      <p class="caption">输入名称，其他的不要点</p>
    </div>
  </div>

  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-18-921_com.psyche.kelivo_1768196651328edit.jpg" alt="步骤5">
      <p class="caption">打开Kelivo, 注册/登录账户点击左上角的三条杠</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-25-754_com.psyche.kelivo_1768196695329edit.jpg" alt="步骤6">
      <p class="caption">点击设置 (图标很像齿轮)</p>
    </div>
  </div>

  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-36-990_com.psyche.kelivo_1768196729865edit.jpg" alt="步骤7">
      <p class="caption">点击“供应商”</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-29-48-178_com.psyche.kelivo_1768196765483edit.jpg" alt="步骤8">
      <p class="caption">点击第一个“OpenAI”</p>
    </div>
  </div>

  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-30-09-153_com.psyche.kelivo_1768196935689edit.jpg" alt="步骤9">
      <p class="caption">输入刚才在10dianapi创建的令牌里的Key（密钥）</p>
    </div>
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-49-34-093_com.psyche.kelivo_1768197027681edit.jpg" alt="步骤10">
      <p class="caption">输入10dianapi的网址，后面必须加/v1，v是小写，符号一个都不能少!</p>
    </div>
  </div>

  <div class="gallery-row">
    <div class="gallery-item">
      <img src="/images/Screenshot_2026-01-12-13-49-44-808_com.psyche.kelivo_1768278720513edit.jpg" alt="步骤11">
      <p class="caption">全部完成后，再点击“模型”，这时候再点“获取”就会出现模型了，获取以使用吧~</p>
    </div>
    <div class="gallery-item empty"></div>
  </div>
</div>

<style>
  .tutorial-gallery {
    max-width: 1200px !important;
    margin: 0 auto 4em !important;
    padding: 0 1em !important;
  }

  .tutorial-gallery .gallery-row {
    display: grid !important;
    grid-template-columns: 1fr 1fr !important;
    gap: 3em 5em !important; /* 水平间隙大，中间空旷 */
    margin-bottom: 6em !important;
  }

  .tutorial-gallery .gallery-item {
    display: flex !important;
    flex-direction: column !important;
    align-items: center !important;
    background: none !important;
    padding: 0 !important;
    margin: 0 !important;
    border: none !important;
    box-shadow: none !important;
  }

  .tutorial-gallery .gallery-item img {
    width: 100% !important;
    height: auto !important;
    max-height: 550px !important; /* 控制图片最大高度，避免太大 */
    object-fit: contain !important; /* 保持原比例，不拉伸 */
    border-radius: 16px !important; /* 圆角 */
    box-shadow: 0 8px 25px rgba(0,0,0,0.3) !important; /* 轻微阴影 */
    margin: 0 !important;
    display: block !important;
  }

  .tutorial-gallery .caption {
    margin-top: 1.8em !important;
    margin-bottom: 0 !important;
    font-size: 1.25em !important; /* 文字加大 */
    line-height: 1.6 !important;
    text-align: center !important;
    color: #f0f0f0 !important; /* 更亮可见 */
    background: none !important;
    padding: 0 !important;
  }

  .tutorial-gallery .gallery-item.empty {
    visibility: hidden !important;
  }

  @media (max-width: 768px) {
    .tutorial-gallery .gallery-row {
      grid-template-columns: 1fr 1fr !important;
      gap: 2em 3em !important;
    }
    .tutorial-gallery .gallery-item img {
      max-height: 400px !important; /* 手机上图片稍小 */
    }
    .tutorial-gallery .caption {
      font-size: 1.1em !important;
    }
  }
</style>
