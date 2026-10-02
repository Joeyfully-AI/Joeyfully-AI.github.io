---
layout: page
title: About
---

I am an undergraduate student in Artificial Intelligence at [Xiamen University](https://www.xmu.edu.cn/), advised by [Fei Chao](https://cogsci.xmu.edu.cn/info/1034/1249.htm).

I am broadly interested in robot learning and embodied AI. My research focuses on how pretrained robot policies can be steered, adapted, and improved through interaction, and how these capabilities can translate into reliable behavior in the physical world.

In the long run, I hope to develop embodied agents that can not only acquire broad capabilities from large-scale pretraining, but also refine them through feedback and experience — adapting to new situations, recovering from failures, and continuing to improve after deployment.


## News

* **[Sep, 2026]** Joined the **Embodied Robotics** course at Xiamen University as a Teaching Assistant, contributing to hands-on laboratory design and technical instruction.

* **[Jun, 2026]** One paper was accepted to **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2026)**.

## Selected Research

<style>
.research-item {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  margin-bottom: 34px;
}

/* Fixed research thumbnail */
.research-image {
  flex: 0 0 280px;
  width: 280px;
  aspect-ratio: 16 / 9;
  overflow: hidden;
  border-radius: 6px;
}

.research-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
  display: block;
}

.research-content {
  flex: 1;
  min-width: 0;
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
    gap: 14px;
    margin-bottom: 30px;
  }

  .research-image {
    flex: none;
    width: 100%;
    max-width: 520px;
    aspect-ratio: 16 / 9;
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


## Research Interests

Within robot learning and embodied AI, I am particularly interested in:

**Steering and post-training:** adapt and refine pretrained robot policies through reinforcement learning, feedback, and inference-time intervention, turning broad pretrained capabilities into controllable and effective behavior.

**Interactive robot learning:** enable robots to continue improving through experience, using interaction with the physical world to adapt to new tasks, environments, and failures.

**Reliable long-horizon behavior:** develop robot policies that remain physically grounded and coherent over extended tasks, with the ability to detect errors, recover from failures, and adapt their behavior as execution unfolds.

I am also curious about predictive world models, continual learning, and multi-agent interaction as possible mechanisms for building more adaptive embodied agents.

## Teaching and Mentoring

**Embodied Robotics**, Xiamen University — *Teaching Assistant, Fall 2026*  
Contributing to hands-on laboratory design and technical instruction in robot control, imitation learning, and Vision-Language-Action models.

## Misc

Outside research, I enjoy reading, wandering through cities, playing chess, and thinking about food that I may or may not ever cook. During my first year of college, I often spent weekends traveling alone without a fixed destination — hopping between streets, stations, neighborhoods, and quiet corners of a city simply to see where the day would take me.

I also have a soft spot for old books, from Chinese classical literature to medieval writings, and for being a bit of a “cloud foodie” and imaginary-kitchen chef whenever real cooking is temporarily unavailable. More generally, I enjoy the kind of small, unnecessary curiosities that are fun precisely because they do not need to become anything else.

<style>
.chess-story {
  font-size: 15.5px;
  line-height: 1.55;
  margin-top: 28px;
}

.chess-story-image {
  float: right;
  width: min(36%, 480px);
  margin: 4px 0 18px 30px;
}

.chess-story-image img {
  width: 100%;
  height: auto;
  max-height: 340px;
  object-fit: cover;
  border-radius: 10px;
  display: block;
}

.chess-story::after {
  content: "";
  display: block;
  clear: both;
}

@media (max-width: 800px) {
  .chess-story-image {
    float: none;
    width: 100%;
    margin: 20px 0;
  }

  .chess-story-image img {
    max-height: none;
  }
}
</style>

<div class="chess-story">
  <p>
    Chess is one of those interests I keep returning to. I occasionally
    spend time with a small group of fellow enthusiasts who enjoy
    building and experimenting with their own chess engines. Much of it
    is delightfully informal: strange moves, long games, broken ideas,
    unexpected successes, and plenty of complete nonsense.
  </p>

  <div class="chess-story-image">
    <img
      src="assets/img/misc/chess-engine.jpg"
      alt="A sunlit chessboard"
    >
  </div>

  <p>
    Every now and then, ideas from machine learning sneak into these
    experiments, such as questions about action sequences, state tracking,
    generative policies, or how small errors accumulate over time.
    But I mostly enjoy them for what they are: a chance to play with
    models, exchange half-formed ideas with friends, and explore
    something without needing it to become part of a research agenda.
  </p>

  <p>
    I like keeping a few things this way. Not every curiosity needs a
    problem statement, a benchmark, or a conclusion; sometimes it is
    enough to follow an idea for a while simply because it is interesting.
  </p>
</div>

## A Final Note

I still do not know exactly where research will take me, and I hope that remains true for a while. Some of the questions I care about today will probably disappear; others have not occurred to me yet.

What I hope to keep is the curiosity that made all of this interesting in the first place — the pleasure of finding something I do not understand, playing with it for a while, and occasionally watching an idea turn into something real.

