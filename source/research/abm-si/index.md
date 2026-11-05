---
title: 基于 ABM-SI 模型的松材线虫病传播预测研究
date: 2026-01-01 00:00:00
comments: false
hideBanner: true
---

<div class="dog-research-page">

<p class="dog-research-back"><a href="/research/"><i class="fas fa-arrow-left" aria-hidden="true"></i> 返回科研项目</a></p>

<section class="dog-research-hero">
  <div class="dog-research-hero-meta">
    <span class="dog-research-badge">科研项目</span>
    <span class="dog-research-period">[进行中]</span>
    <span class="dog-research-focus">研究侧重：智能体建模 · 传播预测 · 仿真分析</span>
  </div>
  <h1>基于 ABM-SI 模型的松材线虫病传播预测研究</h1>
  <p class="dog-research-hero-desc">松材线虫病是一种严重危害森林生态系统的毁灭性病害。本研究基于智能体建模（Agent-Based Modeling）与 SI 流行病传播模型，结合 GIS 空间数据，构建松材线虫病在森林生态系统中的传播预测模型。</p>
  <div class="dog-research-tags">
    <span class="dog-tag dog-tag--on-dark">ABM</span>
    <span class="dog-tag dog-tag--on-dark">SI 模型</span>
    <span class="dog-tag dog-tag--on-dark">松材线虫病</span>
    <span class="dog-tag dog-tag--on-dark">智能体建模</span>
    <span class="dog-tag dog-tag--on-dark">MATLAB</span>
    <span class="dog-tag dog-tag--on-dark">仿真</span>
  </div>
</section>

<div class="dog-research-layout">

<article class="dog-research-main">

<section class="dog-research-section" id="background">
  <h2><span class="dog-research-num">01</span>研究背景与问题</h2>
  <p>松材线虫病由松材线虫（Bursaphelenchus xylophilus）引起，通过松墨天牛等媒介昆虫在松树林中传播，具有发病速度快、致死率高的特点。传统的监测和防控手段面临监测范围广、传播机制复杂等挑战，需要借助建模与仿真方法进行传播预测和风险评估。</p>
</section>

<section class="dog-research-section" id="method">
  <h2><span class="dog-research-num">02</span>研究方法</h2>
  <p class="dog-research-lead">本研究采用 ABM（Agent-Based Modeling）与 SI 流行病模型相结合的方法，从微观个体行为和宏观传播规律两个层面进行建模分析。</p>
  <div class="dog-work-grid">
    <div class="dog-work-card">
      <h3><i class="fas fa-cube" aria-hidden="true"></i>智能体建模（ABM）</h3>
      <ul class="dog-work-list">
        <li><span class="dog-work-label">思路</span><p>将松树、松墨天牛、松材线虫等分别建模为具有独立行为的智能体，通过 agent 间交互模拟病害传播过程。</p></li>
        <li><span class="dog-work-label">优势</span><p>能够捕捉空间异质性、个体行为差异和随机事件对传播的影响。</p></li>
      </ul>
    </div>
    <div class="dog-work-card">
      <h3><i class="fas fa-project-diagram" aria-hidden="true"></i>SI 流行病模型</h3>
      <ul class="dog-work-list">
        <li><span class="dog-work-label">思路</span><p>借鉴经典流行病传播模型，将松树划分为易感（Susceptible）和感染（Infected）状态，建立状态转移方程。</p></li>
        <li><span class="dog-work-label">优势</span><p>提供宏观层面的传播动力学分析框架，与 ABM 结合后可兼顾宏观规律与微观机制。</p></li>
      </ul>
    </div>
    <div class="dog-work-card">
      <h3><i class="fas fa-satellite" aria-hidden="true"></i>GIS 空间数据</h3>
      <ul class="dog-work-list">
        <li><span class="dog-work-label">思路</span><p>利用 GIS 数据构建森林空间分布，结合地形、气候等环境因子，为仿真提供真实的空间基础。</p></li>
        <li><span class="dog-work-label">优势</span><p>使模型能够模拟真实地理环境中的病害传播过程。</p></li>
      </ul>
    </div>
  </div>
</section>

<section class="dog-research-section" id="model">
  <h2><span class="dog-research-num">03</span>模型构建</h2>
  <ol class="dog-roadmap">
    <li>森林空间建模</li>
    <li>智能体行为规则定义</li>
    <li>SI 传播动力学方程</li>
    <li>GIS 空间数据集成</li>
    <li>仿真与参数校准</li>
  </ol>
  <p class="dog-research-note"><strong>数据说明：</strong>模型参数需要结合实际松材线虫病调查数据进行校准。具体模型结构和参数设置将在项目推进过程中逐步完善。</p>
</section>

<section class="dog-research-section" id="progress">
  <h2><span class="dog-research-num">04</span>研究进展</h2>
  <p class="dog-research-note"><strong>研究进行中：</strong>本研究为当前开展的方向，模型框架和仿真流程已初步搭建，正在进行参数校准和实验设计。研究进展将随工作推进持续更新。</p>
  <figure class="dog-figure">
    <div class="dog-figure-placeholder" data-code="ABM-SI-01" role="img" aria-label="模型示意图待补充">
      <i class="fas fa-hourglass-half" aria-hidden="true"></i>
      <span>研究进行中 · 图表待更新</span>
    </div>
    <figcaption>
      <strong>图 ABM-SI-01</strong> ABM-SI 模型框架示意图（研究进行中）
    </figcaption>
  </figure>
</section>

<section class="dog-research-section" id="tech">
  <h2><span class="dog-research-num">05</span>关键技术</h2>

  <h3>智能体建模核心要素</h3>
  <p>智能体建模的核心在于定义不同类型 agent 的状态、行为规则和交互机制。在松材线虫病传播场景中，主要包括松树 agent（健康/感染状态）、松墨天牛 agent（携带线虫传播）以及松材线虫 agent（寄生与移动）。</p>

  <h3>SI 模型在植物病害中的应用</h3>
  <p>经典的 SI 模型将种群划分为易感和感染两类，感染个体以一定传播率使易感个体变为感染个体。在植物病害场景下，还需要考虑媒介昆虫的传播特性、环境因子的影响等。</p>

  <h3>仿真流程</h3>
  <div class="dog-chain" aria-label="仿真流程">
    <span>GIS 数据输入</span><i class="fas fa-chevron-right" aria-hidden="true"></i>
    <span>初始化 agent 状态</span><i class="fas fa-chevron-right" aria-hidden="true"></i>
    <span>时间步进仿真</span><i class="fas fa-chevron-right" aria-hidden="true"></i>
    <span>agent 交互与状态更新</span><i class="fas fa-chevron-right" aria-hidden="true"></i>
    <span>传播结果输出</span>
  </div>
</section>

<section class="dog-research-section" id="outputs">
  <h2><span class="dog-research-num">06</span>预期成果与延伸</h2>
  <ul class="dog-output-list">
    <li>
      <strong>模型与仿真平台</strong>
      <p>基于 MATLAB 或 NetLogo 构建的 ABM-SI 松材线虫病传播仿真模型。</p>
    </li>
    <li>
      <strong>传播预测方法</strong>
      <p>结合 GIS 空间数据的病害传播风险评估与预测方法。</p>
    </li>
    <li>
      <strong>防控策略建议</strong>
      <p>基于仿真结果的松材线虫病防控策略分析。</p>
    </li>
  </ul>
  <p class="dog-research-note">本项目正在推进中，以上为预期研究内容，具体成果待项目完成后更新。</p>
</section>

<nav class="dog-research-nextprev" aria-label="项目导航">
  <a class="dog-research-nextprev-link dog-research-nextprev-link--prev" href="/research/">
    <span>返回</span>
    <strong>科研项目总览</strong>
  </a>
  <a class="dog-research-nextprev-link dog-research-nextprev-link--next" href="/research/remote-sensing-gis/">
    <span>下一个项目</span>
    <strong>遥感影像与 GIS 空间数据分析</strong>
  </a>
</nav>

</article>

<aside class="dog-research-toc" aria-label="章节导航">
  <p class="dog-research-toc-title">章节导航</p>
  <ol>
    <li><a href="#background">01 研究背景与问题</a></li>
    <li><a href="#method">02 研究方法</a></li>
    <li><a href="#model">03 模型构建</a></li>
    <li><a href="#progress">04 研究进展</a></li>
    <li><a href="#tech">05 关键技术</a></li>
    <li><a href="#outputs">06 预期成果与延伸</a></li>
  </ol>
</aside>

</div>

</div>

<script src="/js/dog-research.js"></script>
