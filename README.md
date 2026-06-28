---
layout: page
title: About
---

I am an undergraduate student in Artificial Intelligence at [Xiamen University](https://www.xmu.edu.cn/), advised by [Fei Chao](https://cogsci.xmu.edu.cn/info/1034/1249.htm).

I am broadly interested in robot learning and embodied AI. My current research focuses on Vision-Language-Action models, long-horizon manipulation, and reliable robot control. I am especially interested in what happens after a robot understands a task: how it can produce actions that are physically feasible, precise, and recoverable when execution does not go as planned.

In the long run, I hope to help build general-purpose robots that can work reliably in everyday environments, from homes to factories, handling tasks that are tedious, delicate, or dangerous. I hope my work can contribute to a growing effort toward robot intelligence that is not only expressive, but also dependable in the physical world.

## News

* **[Jun, 2026]** One paper was accepted to **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2026)**.

* **[Jun, 2026]** One paper was accepted to **IEEE International Conference on Systems, Man, and Cybernetics (SMC 2026)**.

* **[May, 2026]** I released a low-resource **RLT-style reproduction for VLA control**, built on **SmolVLA**, **LeRobot**, and **LIBERO**.

## Selected Research

<style>
.research-item {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  margin-bottom: 34px;
}

.research-image {
  flex: 0 0 280px;
  max-width: 280px;
}

.research-image img {
  width: 100%;
  max-height: 150px;
  object-fit: contain;
  border-radius: 6px;
  display: block;
}

.research-content {
  flex: 1;
  font-size: 15.5px;
  line-height: 1.45;
}

.research-title {
  font-size: 18px;
  font-weight: 700;
  line-height: 1.28;
  margin: 0 0 5px 0;
}

.research-authors {
  font-size: 15.5px;
  line-height: 1.4;
  margin: 0 0 3px 0;
}

.research-venue {
  font-size: 15.5px;
  font-style: italic;
  line-height: 1.4;
  margin: 0 0 6px 0;
}

.research-links {
  font-size: 15.5px;
  line-height: 1.4;
  margin: 0 0 10px 0;
}

.research-links a {
  margin-right: 12px;
  text-decoration: none;
  border-bottom: 1px solid currentColor;
}

.research-links a::after {
  content: none !important;
  display: none !important;
}

.research-desc {
  font-size: 15.5px;
  line-height: 1.45;
  margin: 0;
}

@media (max-width: 800px) {
  .research-item {
    flex-direction: column;
    gap: 12px;
    margin-bottom: 30px;
  }

  .research-image {
    flex: none;
    max-width: 100%;
  }

  .research-image img {
    max-height: none;
  }

  .research-title {
    font-size: 17px;
  }
}
</style>

<div class="research-item">
  <div class="research-image">
    <img src="assets/img/research/physreflect-vla.png" alt="PhysReflect-VLA project thumbnail">
  </div>
  <div class="research-content">
    <p class="research-title">PhysReflect-VLA: Physical Feasibility and Self-Reflective Regulation for Reliable Vision-Language-Action Policies</p>
    <p class="research-authors"><strong>Jiayu Yang</strong>, Tao Yang, Weijun Li, Xiang Chang, Fei Chao, Changjing Shang, Qiang Shen</p>
    <p class="research-venue">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026</p>
    <p class="research-links">
      <a href="https://arxiv.org/abs/2606.27146">paper</a>
    </p>
    <p class="research-desc">PhysReflect-VLA improves long-horizon VLA control through physical feasibility evaluation and self-reflective failure recovery.</p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="assets/img/research/pamae.png" alt="PAMAE project thumbnail">
  </div>
  <div class="research-content">
    <p class="research-title">PAMAE: Phase-Aware-MoE Action Experts Towards Reliable Flow-Matching Vision-Language-Action Policies</p>
    <p class="research-authors"><strong>Jiayu Yang</strong>, Tao Yang, Xiang Chang, Fei Chao, Changjing Shang, Qiang Shen</p>
    <p class="research-venue">IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2026</p>
    <p class="research-links">
      <a href="https://arxiv.org/abs/2606.27144">paper</a>
    </p>
    <p class="research-desc">PAMAE introduces phase-aware mixture-of-experts action generation for more reliable flow-matching VLA policies in multi-stage manipulation.</p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="assets/img/research/rlt-reproduction.png" alt="RLT-style VLA reproduction thumbnail">
  </div>
  <div class="research-content">
    <p class="research-title">RL Token Reproduction</p>
    <p class="research-authors"><strong>Jiayu Yang</strong></p>
    <p class="research-venue">Open-source reproduction, 2026</p>
    <p class="research-links">
      <a href="https://huggingface.co/Joeyfully/smolvla_rlt_libero_10">model</a> /
      <a href="https://huggingface.co/Joeyfully/smolvla_rlt_libero_10/resolve/main/RL%20Token%20Reproduction_Efficient%20and%20Accurate%20VLA%20Control%20via%20RL%20Token%20Representations%E2%80%93ppt.pptx?download=true">slides</a> /
      <a href="https://huggingface.co/Joeyfully/smolvla_rlt_libero_10/tree/main/videos">video</a>
    </p>
    <p class="research-desc">A low-resource RLT-style reproduction for VLA control with SmolVLA, LeRobot, and LIBERO.</p>
  </div>
</div>


## Research Interests

Within robot learning, deep reinforcement learning, and embodied AI, I am particularly interested in:

**Robotics RL for foundation policies:** improve pretrained robot policies, especially Vision-Language-Action models, through reinforcement learning, value learning, and online/post-training adaptation, while preserving their semantic and behavioral priors.

**World models and physical consistency:** build internal models, verifiers, and self-consistency objectives that help robots predict the physical consequences of their actions, evaluate feasibility, and recover from execution failures.

**Hierarchical and phase-aware manipulation:** enable reliable long-horizon robot manipulation through temporal abstraction, skill-level control, and phase-aware refinement, especially for precise and contact-rich tasks.

A sample of other topics that I am also curious about: cross-embodiment generalization, generative models for robot behavior, and efficient adaptation of large robot foundation models.

I owe so much to the people who have generously mentored me, encouraged me, and inspired me with their vision and passion.

## Misc


