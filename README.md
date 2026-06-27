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

<div class="research-item">
  <div class="research-image">
    <img src="IMAGE_PLACEHOLDER_IROS" alt="PhysReflect-VLA project thumbnail">
  </div>
  <div class="research-content">
    <p><strong>PhysReflect-VLA: Physical Feasibility and Self-Reflective Regulation for Reliable Vision-Language-Action Policies</strong></p>
    <p>Reliable VLA control for long-horizon robot manipulation through physical feasibility evaluation and self-reflective failure recovery.</p>
    <p>
      <a href="https://arxiv.org/abs/2606.27146">Paper</a> /
      <details class="bibtex-details">
        <summary>Bibitex</summary>
        <pre><code>@inproceedings{yang2026physreflectvla,
  title     = {PhysReflect-VLA: Physical Feasibility and Self-Reflective Regulation for Reliable Vision-Language-Action Policies},
  author    = {Yang, Jiayu and Yang, Tao and Li, Weijun and Chang, Xiang and Chao, Fei and Shang, Changjing and Shen, Qiang},
  booktitle = {Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year      = {2026},
  eprint    = {2606.27146},
  archivePrefix = {arXiv},
  primaryClass  = {cs.RO}
}</code></pre>
      </details>
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="IMAGE_PLACEHOLDER_SMC" alt="PAMAE project thumbnail">
  </div>
  <div class="research-content">
    <p><strong>PAMAE: Phase-Aware-MoE Action Experts Towards Reliable Flow-Matching Vision-Language-Action Policies</strong></p>
    <p>Phase-aware mixture-of-experts action generation for more reliable flow-matching VLA policies in multi-stage robot manipulation.</p>
    <p>
      <a href="https://arxiv.org/abs/2606.27144">Paper</a> /
      <details class="bibtex-details">
        <summary>Bibitex</summary>
        <pre><code>@inproceedings{yang2026pamae,
  title     = {PAMAE: Phase-Aware-MoE Action Experts Towards Reliable Flow-Matching Vision-Language-Action Policies},
  author    = {Yang, Jiayu and Yang, Tao and Chang, Xiang and Chao, Fei and Shang, Changjing and Shen, Qiang},
  booktitle = {Proceedings of the IEEE International Conference on Systems, Man, and Cybernetics (SMC)},
  year      = {2026},
  eprint    = {2606.27144},
  archivePrefix = {arXiv},
  primaryClass  = {cs.RO}
}</code></pre>
      </details>
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="IMAGE_PLACEHOLDER_RLT" alt="RLT-style VLA reproduction thumbnail">
  </div>
  <div class="research-content">
    <p><strong>RL Token Reproduction</strong></p>
    <p>A low-resource RLT-style reproduction for VLA control with SmolVLA, LeRobot, and LIBERO.</p>
    <p>
      <a href="https://huggingface.co/Joeyfully/smolvla_rlt_libero_10">Model</a> /
      <a href="https://huggingface.co/Joeyfully/smolvla_rlt_libero_10/resolve/main/RL%20Token%20Reproduction_Efficient%20and%20Accurate%20VLA%20Control%20via%20RL%20Token%20Representations%E2%80%93ppt.pptx?download=true">Slides</a> /
      <a href="https://huggingface.co/Joeyfully/smolvla_rlt_libero_10/tree/main/videos">Video</a> /
      <details class="bibtex-details">
        <summary>Bibitex</summary>
        <pre><code>@misc{young2026rltreproduction,
  title        = {RL Token Reproduction: Efficient and Accurate VLA Control via RL Token Representations},
  author       = {Young, Joey},
  year         = {2026},
  howpublished = {\url{https://huggingface.co/Joeyfully/smolvla_rlt_libero_10}},
  note         = {A low-resource RLT-style reproduction for VLA control with SmolVLA, LeRobot, and LIBERO}
}</code></pre>
      </details>
    </p>
  </div>
</div>


## Research Interests

- Embodied AI
- Robot Learning
- Vision-Language-Action Models
- Reliable robotic manipulation
- Reinforcement learning for robot control
- Physical consistency and failure-aware policy improvement
