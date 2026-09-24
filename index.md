---
layout: default
title: "Xinyan Li — LLM Research Engineer"
description: "Xinyan Li is an LLM research engineer working on post-training, tool-integrated mathematical reasoning, and efficient inference."
---

<section class="hero" aria-labelledby="hero-title">
  <div class="hero-copy">
    <p class="eyebrow">LLM Research Engineer <span aria-hidden="true">·</span> Hong Kong</p>
    <h1 id="hero-title">Building reasoning models that are capable, reliable, and efficient.</h1>
    <p class="hero-lede">
      I post-train 30B+ language models for tool-integrated mathematical reasoning and token-efficient inference, spanning data construction, SFT and reinforcement learning, distributed rollout, and evaluation.
    </p>
    <div class="hero-actions" aria-label="Primary links">
      <a class="button button-primary" href="{{ '/resume.pdf' | relative_url }}" target="_blank" rel="noopener">View résumé <span aria-hidden="true">↗</span></a>
      <a class="button button-secondary" href="#work">Explore my work <span aria-hidden="true">↓</span></a>
    </div>
  </div>

  <aside class="hero-card" aria-label="At a glance">
    <p class="card-label">Currently</p>
    <p class="hero-role">Senior Research Engineer</p>
    <p class="hero-org">Huawei Hong Kong Research Center</p>
    <dl class="quick-facts">
      <div>
        <dt>Focus</dt>
        <dd>LLM post-training</dd>
      </div>
      <div>
        <dt>Scale</dt>
        <dd>30B+ models</dd>
      </div>
      <div>
        <dt>Background</dt>
        <dd>Ph.D. in Computer Science</dd>
      </div>
    </dl>
  </aside>
</section>

<section class="section intro-section" id="about" aria-labelledby="about-title">
  <div class="section-heading">
    <p class="section-number">01</p>
    <h2 id="about-title">About</h2>
  </div>
  <div class="intro-copy">
    <p class="large-copy">
      I am a research engineer specializing in post-training large language models, with a particular interest in models that can use tools, reason mathematically, and solve problems with fewer tokens.
    </p>
    <p>
      At Huawei Hong Kong Research Center, I work across the full training pipeline—from data processing and SFT/RL to distributed rollout and evaluation. I received my Ph.D. from City University of Hong Kong, where I studied privacy leakage and mitigation in encrypted search systems. That security background continues to shape how I think about reliable and trustworthy AI systems.
    </p>
  </div>
</section>

<section class="section" id="work" aria-labelledby="work-title">
  <div class="section-heading">
    <p class="section-number">02</p>
    <h2 id="work-title">Selected work</h2>
  </div>
  <div class="focus-grid">
    <article class="focus-card">
      <p class="card-index">01 / Reasoning</p>
      <h3>Tool-integrated mathematical reasoning</h3>
      <p>Training language models with SFT and multi-stage RL to use Python and Wolfram/Mathematica for reliable mathematical problem solving.</p>
      <ul class="compact-list">
        <li>Teacher-trajectory construction</li>
        <li>Tool-call filtering and data cleaning</li>
        <li>Capability-specific training and evaluation</li>
      </ul>
    </article>

    <article class="focus-card">
      <p class="card-index">02 / Efficiency</p>
      <h3>Token-efficient reasoning</h3>
      <p>Using Long-to-Short RL to transfer reasoning capability from a model with a 32K context budget into an 8K-budget model while preserving answer accuracy.</p>
      <ul class="compact-list">
        <li>RL algorithm and reward design</li>
        <li>Length penalties and termination control</li>
        <li>Accuracy–efficiency trade-off analysis</li>
      </ul>
    </article>

    <article class="focus-card">
      <p class="card-index">03 / Agents</p>
      <h3>Agentic model training</h3>
      <p>Studying practical training pipelines for lightweight agents that learn from tool-use trajectories, environment feedback, and verifiable rewards.</p>
      <ul class="compact-list">
        <li>Multi-turn SFT and RL</li>
        <li>Tool-use trajectory curation</li>
        <li>Environment and reward design</li>
      </ul>
    </article>
  </div>
</section>

<section class="section" id="experience" aria-labelledby="experience-title">
  <div class="section-heading">
    <p class="section-number">03</p>
    <h2 id="experience-title">Experience</h2>
  </div>
  <div class="timeline">
    <article class="timeline-item">
      <p class="timeline-date">Jun 2025 — Present</p>
      <div>
        <h3>Senior Research Engineer</h3>
        <p class="timeline-org">Huawei Hong Kong Research Center · Hong Kong</p>
        <p>Lead end-to-end post-training of 30B+ LLMs, with a focus on tool-integrated reasoning and token-efficient inference.</p>
      </div>
    </article>
    <article class="timeline-item">
      <p class="timeline-date">Dec 2024 — May 2025</p>
      <div>
        <h3>Research Intern</h3>
        <p class="timeline-org">Huawei Hong Kong Research Center · Hong Kong</p>
        <p>Explored RAG architectures and input-attribution methods, analyzed production failure cases, and evaluated retrieval-based mitigations.</p>
      </div>
    </article>
    <article class="timeline-item">
      <p class="timeline-date">Dec 2020 — Jun 2021</p>
      <div>
        <h3>Research Assistant</h3>
        <p class="timeline-org">City University of Hong Kong · Hong Kong</p>
      </div>
    </article>
  </div>
</section>

<section class="section" id="publications" aria-labelledby="publications-title">
  <div class="section-heading section-heading-with-link">
    <div>
      <p class="section-number">04</p>
      <h2 id="publications-title">Selected publications</h2>
    </div>
    <a class="text-link" href="{{ site.google_scholar }}" target="_blank" rel="noopener">Google Scholar <span aria-hidden="true">↗</span></a>
  </div>
  <div class="publication-list">
    <article class="publication">
      <div class="publication-meta">
        <span>IEEE TSC</span>
        <span>2025</span>
      </div>
      <h3><a href="https://doi.org/10.1109/TSC.2024.3517316" target="_blank" rel="noopener">When Differential Privacy Meets Query Control: A Hybrid Framework for Practical Range Query Leakage Quantification and Mitigation <span aria-hidden="true">↗</span></a></h3>
      <p><strong>Xinyan Li</strong>, Yuefeng Du, and Cong Wang</p>
    </article>
    <article class="publication">
      <div class="publication-meta">
        <span>IEEE ICDCS</span>
        <span>2023</span>
      </div>
      <h3><a href="https://doi.org/10.1109/ICDCS57875.2023.00017" target="_blank" rel="noopener">RangeQC: A Query Control Framework for Range Query Leakage Quantification and Mitigation <span aria-hidden="true">↗</span></a></h3>
      <p><strong>Xinyan Li</strong>, Yuefeng Du, and Cong Wang</p>
    </article>
    <article class="publication">
      <div class="publication-meta">
        <span>IEEE Network</span>
        <span>2021</span>
      </div>
      <h3><a href="https://doi.org/10.1109/MNET.001.2100256" target="_blank" rel="noopener">When Deep Learning Meets Differential Privacy: Privacy, Security, and More <span aria-hidden="true">↗</span></a></h3>
      <p><strong>Xinyan Li</strong>, Yufei Chen, Cong Wang, and Chao Shen</p>
    </article>
  </div>
</section>

<section class="section split-section" id="background" aria-labelledby="background-title">
  <div>
    <div class="section-heading compact-heading">
      <p class="section-number">05</p>
      <h2 id="background-title">Education</h2>
    </div>
    <div class="education-list">
      <article>
        <p class="education-date">2021 — 2025</p>
        <h3>Ph.D. in Computer Science</h3>
        <p>City University of Hong Kong</p>
        <p class="detail">GPA 3.87/4.0 · Institutional Research Tuition Scholarship</p>
      </article>
      <article>
        <p class="education-date">2019 — 2020</p>
        <h3>M.Sc. in Computer Science, with Distinction</h3>
        <p>City University of Hong Kong</p>
      </article>
      <article>
        <p class="education-date">2015 — 2019</p>
        <h3>B.Eng. in Computer Science and Technology</h3>
        <p>South China University of Technology</p>
        <p class="detail">Academic exchanges at Tianjin University and ITMO University</p>
      </article>
    </div>
  </div>

  <div>
    <div class="section-heading compact-heading">
      <p class="section-number">06</p>
      <h2>Skills</h2>
    </div>
    <div class="skill-group">
      <h3>Post-training</h3>
      <p>SFT · Reinforcement learning · Multi-stage RL · Long-to-Short RL</p>
    </div>
    <div class="skill-group">
      <h3>Reasoning</h3>
      <p>Tool-integrated reasoning · Tool calling · Mathematical and physics reasoning</p>
    </div>
    <div class="skill-group">
      <h3>Frameworks & systems</h3>
      <p>verl · TRL · Slurm · Distributed training, rollout, and evaluation</p>
    </div>
    <div class="skill-group">
      <h3>Programming</h3>
      <p>Python · C/C++ · Java · Shell · SQL</p>
    </div>
  </div>
</section>

<section class="contact-cta" id="contact" aria-labelledby="contact-title">
  <p class="eyebrow">Let’s connect</p>
  <h2 id="contact-title">Interested in LLM training, reasoning, and efficient inference.</h2>
  <p>I am based in Hong Kong and open to relocation.</p>
  <div class="hero-actions">
    <a class="button button-light" href="mailto:{{ site.email }}">Email me <span aria-hidden="true">↗</span></a>
    <a class="button button-ghost" href="{{ site.github }}" target="_blank" rel="noopener">GitHub <span aria-hidden="true">↗</span></a>
  </div>
</section>
