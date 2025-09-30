---
layout: page
permalink: /group/
title: Trustworthy Robotics Lab
description:
nav: true
nav_order: 1
---

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600;700&family=Rajdhani:wght@500;700&display=swap" rel="stylesheet">

<style>
:root{
  --trl-primary:#1e90ff;
  --trl-secondary:#00bfff;
  --trl-accent:#7a88ff;
  --trl-text:#222;
  --trl-muted:#6b7280;
  --trl-bg:#ffffff;
  --trl-card:#f8fafc;
}

/* 标题样式 */
.trl-title{
  font-family: "Orbitron", sans-serif;
  font-size: clamp(36px, 6vw, 56px);
  background: linear-gradient(90deg,var(--trl-primary),var(--trl-secondary));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: glow 2.4s ease-in-out infinite alternate;
}
@keyframes glow {
  from { text-shadow: 0 0 8px rgba(30,144,255,.3); }
  to { text-shadow: 0 0 16px rgba(0,191,255,.6); }
}

/* 内容卡片 */
.trl-card{
  background: var(--trl-card);
  padding: 22px;
  border-radius: 14px;
  box-shadow: 0 6px 20px rgba(2,8,23,.08);
  margin: 18px 0;
  transition: transform .25s ease;
}
.trl-card:hover{
  transform: translateY(-4px);
}

/* 成员列表 */
.trl-list{
  list-style: none;
  padding-left: 0;
}
.trl-list li{
  padding: 8px 0;
  font-size: 17px;
  border-bottom: 1px dashed #d1d5db;
}
.trl-name{
  font-weight: 600;
  color: var(--trl-primary);
}
.trl-role{
  font-size: 14px;
  color: var(--trl-muted);
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
      <li>
        <span class="trl-name"><a href="https://mrjunhuizhang.github.io/">Junhui Zhang</a></span><br>
        <span class="trl-role">Principal Investigator</span>
      </li>
    </ul>

    <h3>Postdoctoral Researchers</h3>
    <ul class="trl-list">
      <li><span class="trl-name">TBD</span></li>
    </ul>

    <h3>Ph.D. Students</h3>
    <ul class="trl-list">
      <li>
        <span class="trl-name">Jiaxuan Li</span><br>
        <span class="trl-role">2026.9–</span>
      </li>
      <li>
        <span class="trl-name">Yunlin Wei</span><br>
        <span class="trl-role">2026.9–</span>
      </li>
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
