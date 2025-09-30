---
layout: page
permalink: /group/
title: Trustworthy Robotics Lab
description:
nav: true
nav_order: 1
---

<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

<style>
/* ① 如主题自动渲染了页面标题，隐藏它（避免双标题+多余留白） */
.page-title, .page__title, .post-title { display: none; } /* 你的主题只会命中其中一个 */

/* ② 压缩标题与段落间距 */
h1.trl-title{ margin: 6px 0 8px; font-size: 36px; }      /* 原来太大 */
h2{ margin: 12px 0 8px; font-size: 22px; }
h3{ margin: 10px 0 6px;  font-size: 18px; }
p { line-height: 1.55; margin: 6px 0 10px; }

/* ③ 卡片更紧凑：减 padding / margin / 阴影 */
.trl-card{
  padding: 14px 16px;
  margin: 12px 0;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,.05);
}

/* ④ 成员：每人一行但更紧凑 */
.trl-list { margin: 4px 0 0; }
.trl-list li{
  padding: 4px 0;
  line-height: 1.6;
  border-bottom: 1px solid #eef1f4;
}
.trl-role{ margin-left: 6px; color:#6b7280; }

/* ⑤ 卡片之间的“大片留白”通常来自容器左右留白，适度收窄整体宽度 */
.trl-wrap{ max-width: 820px; margin: 0 auto; } /* 原900→820，更集中视线 */

/* ⑥ 大屏进一步压缩 */
@media (min-width: 1100px){
  h1.trl-title{ font-size: 34px; }
  .trl-card{ padding: 12px 14px; margin: 10px 0; }
}

/* ⑦ 移动端保持可读性（不再额外放大） */
@media (max-width: 640px){
  h1.trl-title{ font-size: 28px; }
  h2{ font-size: 20px; } h3{ font-size: 17px; }
}
</style>

<div class="trl-wrap">

  <h1 class="trl-title">Trustworthy Robotics Lab</h1>

  <p>
    Welcome to the <strong>Trustworthy Robotics Lab (TRL)</strong> in the 
    <strong>School of Robotics and Automation</strong> at <strong>Nanjing University</strong>, 
    directed by <a href="https://mrjunhuizhang.github.io/"><strong>Dr. Junhui Zhang</strong></a>.
  </p>

  <div class="trl-card">
    <h2>🚀 Research Vision</h2>
    <p>
      Our mission is to develop <strong>safe, reliable, and intelligent robotic systems</strong> 
      that can operate <strong>autonomously in complex, uncertain, and dynamic environments</strong>. 
      By integrating <strong>control theory, machine learning, and formal methods</strong>, 
      we aim to design <strong>next-generation trustworthy robotic technologies</strong> that 
      significantly advance the capabilities of autonomous systems and enable their deployment 
      in <strong>real-world applications</strong>.
    </p>
  </div>

  <div class="trl-card">
    <h2>👥 Members</h2>

    <h3>Principal Investigator (PI)</h3>
    <ul class="trl-list">
      <li><span class="trl-name"><a href="https://mrjunhuizhang.github.io/">Junhui Zhang</a></span> <span class="trl-role"></span></li>
    </ul>

    <h3>Postdoctoral Researchers</h3>
    <ul class="trl-list">
      <li><span class="trl-name">TBD</span></li>
    </ul>

    <h3>Ph.D. Students</h3>
    <ul class="trl-list">
      <li><span class="trl-name">Jiaxuan Li</span> <span class="trl-role">(2026.9–)</span></li>
      <li><span class="trl-name">Yunlin Wei</span> <span class="trl-role">(2026.9–)</span></li>
    </ul>

    <h3>Master’s Students</h3>
    <ul class="trl-list">
      <li><span class="trl-name">TBD</span></li>
    </ul>

    <h3>Alumni</h3>
    <ul class="trl-list">
      <li><span class="trl-name">TBD</span></li>
    </ul>
  </div>

</div>
