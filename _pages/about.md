---
permalink: /
title: ""
excerpt: "Video foundation model researcher working across data, training, post-training, efficiency, and evaluation."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="vfm-home">
  <header class="vfm-hero" id="about">
    <div class="vfm-hero__copy">
      <p class="vfm-kicker"><span aria-hidden="true"></span> Video foundation model researcher</p>
      <h1>I build generative systems that <em>plan, create, and improve.</em></h1>
      <p class="vfm-hero__lead">My work spans the full foundation-model lifecycle—from data and tokenization to large-scale training, post-training, efficient generation, and multimodal evaluation.</p>
      <p class="vfm-hero__now">Currently researching next-generation video foundation models at <strong>Tencent Hunyuan</strong>. Previously at <strong>AMD</strong> and <strong>Alibaba Wan</strong>.</p>
      <div class="vfm-actions" aria-label="Primary links">
        <a class="vfm-button vfm-button--primary" href="#research">Explore selected work</a>
        <a class="vfm-button" href="https://github.com/wjc2830" target="_blank" rel="noopener noreferrer">GitHub <span aria-hidden="true">↗</span></a>
        <a class="vfm-button" href="mailto:wjc2830@gmail.com">Email</a>
      </div>
    </div>
    <figure class="vfm-portrait">
      <div class="vfm-portrait__frame">
        <img src="{{ '/images/research/portrait.webp' | relative_url }}" width="640" height="760" alt="Portrait of Juncheng Wang" fetchpriority="high">
        <span class="vfm-timecode" aria-hidden="true">JCW · 2026</span>
      </div>
      <figcaption><strong>Juncheng Wang</strong><br>Ph.D. Candidate · The Hong Kong Polytechnic University</figcaption>
    </figure>
  </header>

  <section class="vfm-proof" aria-label="Research profile at a glance">
    <div class="vfm-proof__item">
      <span class="vfm-proof__value">Full stack</span>
      <span class="vfm-proof__label">Data → Evaluation</span>
    </div>
    <div class="vfm-proof__item">
      <span class="vfm-proof__value">Large scale</span>
      <span class="vfm-proof__label">Distributed foundation-model training</span>
    </div>
    <div class="vfm-proof__item">
      <span class="vfm-proof__value">3 labs</span>
      <span class="vfm-proof__label">Tencent · AMD · Alibaba</span>
    </div>
    <div class="vfm-proof__item">
      <span class="vfm-proof__value">CVPR · ECCV · ICLR</span>
      <span class="vfm-proof__label">Video, multimodal, and generative research</span>
    </div>
  </section>

  <section class="vfm-section" id="research" aria-labelledby="research-title">
    <div class="vfm-section__heading">
      <div>
        <p class="vfm-kicker">Selected work</p>
        <h2 id="research-title">Research that closes the generation loop.</h2>
      </div>
      <p>From agentic planning to learned evaluators, I build systems that reason about generation—not only larger generators.</p>
    </div>

    <div class="vfm-research-grid">
      <article class="vfm-project vfm-project--lead">
        <a class="vfm-project__visual" href="https://newton026.github.io/newton/" target="_blank" rel="noopener noreferrer" aria-label="Open the NEWTON project page">
          <img src="{{ '/images/research/newton.webp' | relative_url }}" width="1600" height="586" alt="NEWTON plan-execute-verify framework with a cyclic planner, executor, verifier, and memory pool" loading="lazy" decoding="async">
          <span class="vfm-project__index">01 / AGENTIC VIDEO</span>
        </a>
        <div class="vfm-project__body">
          <div class="vfm-project__meta"><span>Co-first author</span><span>Preprint · Under review</span></div>
          <h3>NEWTON: Agentic Planning for Physically Grounded Video Generation</h3>
          <p>A self-evolving plan–execute–verify workflow that scales reasoning around a video generator, with reinforcement learning from critic feedback.</p>
          <ul class="vfm-tags" aria-label="NEWTON topics"><li>Agentic AIGC</li><li>Video generation</li><li>RL</li><li>Test-time scaling</li></ul>
          <div class="vfm-project__links">
            <a href="https://arxiv.org/abs/2605.18396" target="_blank" rel="noopener noreferrer">Paper ↗</a>
            <a href="https://newton026.github.io/newton/" target="_blank" rel="noopener noreferrer">Project ↗</a>
            <a href="https://github.com/CUTEPKQ/NEWTON" target="_blank" rel="noopener noreferrer">Code ↗</a>
          </div>
        </div>
      </article>

      <article class="vfm-project">
        <a class="vfm-project__visual" href="https://chenhaoqcdyq.github.io/BeyondTimeShifts/" target="_blank" rel="noopener noreferrer" aria-label="Open the Beyond Time Shifts project page">
          <img src="{{ '/images/research/beyond-time-shifts.webp' | relative_url }}" width="1600" height="853" alt="Training framework for a reference-free audio-visual evaluator using preference alignment and R-GRPO" loading="lazy" decoding="async">
          <span class="vfm-project__index">02 / EVALUATION</span>
        </a>
        <div class="vfm-project__body">
          <div class="vfm-project__meta"><span>Co-first author</span><span>ECCV 2026</span></div>
          <h3>Beyond Time Shifts: A Reference-Free Evaluator for Generative Audio-Visual Models</h3>
          <p>Adapts an Omni-LLM into a fine-grained learned critic for audio-visual quality and synchronization, enabling feedback-driven model iteration.</p>
          <ul class="vfm-tags" aria-label="Beyond Time Shifts topics"><li>Omni-LLM</li><li>Evaluator</li><li>R-GRPO</li></ul>
          <div class="vfm-project__links">
            <a href="https://arxiv.org/abs/2607.09091" target="_blank" rel="noopener noreferrer">Paper ↗</a>
            <a href="https://chenhaoqcdyq.github.io/BeyondTimeShifts/" target="_blank" rel="noopener noreferrer">Project ↗</a>
            <a href="https://github.com/chenhaoqcdyq/BeyondTimeShifts" target="_blank" rel="noopener noreferrer">Code ↗</a>
          </div>
        </div>
      </article>

      <article class="vfm-project">
        <a class="vfm-project__visual" href="https://wjc2830.github.io/MelQCD/" target="_blank" rel="noopener noreferrer" aria-label="Open the MelQCD project page">
          <img src="{{ '/images/research/melqcd.webp' | relative_url }}" width="1200" height="620" alt="MelQCD overview comparing conventional video-to-audio control with quantization-continuum decomposition" loading="lazy" decoding="async">
          <span class="vfm-project__index">03 / VIDEO–AUDIO</span>
        </a>
        <div class="vfm-project__body">
          <div class="vfm-project__meta"><span>First author</span><span>CVPR 2025</span></div>
          <h3>Synchronized Video-to-Audio Generation via Mel Quantization-Continuum Decomposition</h3>
          <p>Decomposes synchronized audio into predictable discrete structure and expressive continuous detail for precise, high-quality video-conditioned generation.</p>
          <ul class="vfm-tags" aria-label="MelQCD topics"><li>Video-to-audio</li><li>Tokenizer</li><li>Diffusion</li></ul>
          <div class="vfm-project__links">
            <a href="https://arxiv.org/abs/2503.06984" target="_blank" rel="noopener noreferrer">Paper ↗</a>
            <a href="https://wjc2830.github.io/MelQCD/" target="_blank" rel="noopener noreferrer">Project ↗</a>
            <a href="https://github.com/wjc2830/MelQCD-main" target="_blank" rel="noopener noreferrer">Code ↗</a>
          </div>
        </div>
      </article>

      <article class="vfm-project">
        <a class="vfm-project__visual" href="https://chenhaoqcdyq.github.io/LMR/" target="_blank" rel="noopener noreferrer" aria-label="Open the Latent Motion Reasoning project page">
          <img src="{{ '/images/research/lmr.webp' | relative_url }}" width="1386" height="1098" alt="Comparison of direct, language-reasoned, and latent-motion-reasoned text-to-motion generation" loading="lazy" decoding="async">
          <span class="vfm-project__index">04 / MOTION</span>
        </a>
        <div class="vfm-project__body">
          <div class="vfm-project__meta"><span>Co-first author</span><span>TPAMI · Major revision</span></div>
          <h3>Think Before You Move: Latent Motion Reasoning for Text-to-Motion Generation</h3>
          <p>Moves reasoning into the motion latent space to preserve kinematics and semantics without forcing motion through a lossy text chain of thought.</p>
          <ul class="vfm-tags" aria-label="Latent Motion Reasoning topics"><li>Motion generation</li><li>Latent reasoning</li><li>RL feedback</li></ul>
          <div class="vfm-project__links">
            <a href="https://arxiv.org/abs/2512.24100" target="_blank" rel="noopener noreferrer">Paper ↗</a>
            <a href="https://chenhaoqcdyq.github.io/LMR/" target="_blank" rel="noopener noreferrer">Project ↗</a>
            <a href="https://github.com/chenhaoqcdyq/lmr-codes" target="_blank" rel="noopener noreferrer">Code ↗</a>
          </div>
        </div>
      </article>
    </div>
  </section>

  <section class="vfm-section vfm-stack" id="stack" aria-labelledby="stack-title">
    <div class="vfm-section__heading">
      <div>
        <p class="vfm-kicker">Foundation-model stack</p>
        <h2 id="stack-title">Hands-on across the lifecycle.</h2>
      </div>
      <p>I connect model design to the data, systems, feedback, and evaluation loops required to make it work at scale.</p>
    </div>
    <ol class="vfm-pipeline">
      <li><span>01</span><h3>Data</h3><p>Corpus mining, human annotation, training ingestion, and feedback-driven iteration.</p><small>PRE-TRAINING DATA</small></li>
      <li><span>02</span><h3>Tokenize</h3><p>Image, video, audio, and motion representations for generative modeling.</p><small>VAE · RVQ · DISCRETE TOKENS</small></li>
      <li><span>03</span><h3>Pre-train</h3><p>Large-scale diffusion, flow, and autoregressive foundation-model training.</p><small>DISTRIBUTED SYSTEMS</small></li>
      <li><span>04</span><h3>Post-train</h3><p>Supervised fine-tuning, reinforcement learning, and generator-specific planning.</p><small>SFT · RL · AGENTS</small></li>
      <li><span>05</span><h3>Accelerate</h3><p>Distribution matching and efficient flow models for interactive generation.</p><small>DISTILLATION · EFFICIENCY</small></li>
      <li><span>06</span><h3>Evaluate</h3><p>Learned multimodal critics and reference-free quality evaluation.</p><small>CRITICS · BENCHMARKS</small></li>
    </ol>
  </section>

  <section class="vfm-section" id="experience" aria-labelledby="experience-title">
    <div class="vfm-section__heading">
      <div>
        <p class="vfm-kicker">Industry research</p>
        <h2 id="experience-title">Training models where research meets scale.</h2>
      </div>
    </div>
    <div class="vfm-timeline">
      <article>
        <div class="vfm-timeline__date">2026.06 — PRESENT</div>
        <div><p class="vfm-timeline__org">Tencent · Hunyuan-Video Group</p><h3>Qingyun (Project Up) Intern</h3><p>Pre-training research for the next generation of Hunyuan video foundation models.</p><small>Working with Dr. Jianwei Zhang</small></div>
      </article>
      <article>
        <div class="vfm-timeline__date">2026.01 — 2026.06</div>
        <div><p class="vfm-timeline__org">Advanced Micro Devices (AMD)</p><h3>Student Research Fellow</h3><p>Efficient flow-model research for video generation.</p><small>Mentored by Dr. Tong Shen and Dr. Emad Barsoum</small></div>
      </article>
      <article>
        <div class="vfm-timeline__date">2023.09 — 2025.09</div>
        <div><p class="vfm-timeline__org">Alibaba · Wan Group, Tongyi Lab</p><h3>Research Intern</h3><p>Post-training for foundational video generation and audio-centric generative modeling.</p><small>Mentored by Dr. Chao Xu, Lei Shang, and Dr. Liefeng Bo</small></div>
      </article>
    </div>
  </section>

  <section class="vfm-section" id="publications" aria-labelledby="publications-title">
    <div class="vfm-section__heading">
      <div>
        <p class="vfm-kicker">Selected publications</p>
        <h2 id="publications-title">Video, audio, motion, and generative systems.</h2>
      </div>
      <p>† denotes equal contribution. * denotes a junior student advisee.</p>
    </div>
    <div class="vfm-publications">
      <article><div><span class="vfm-status vfm-status--review">Under review</span><span class="vfm-pub__year">2026</span></div><h3>NEWTON: Agentic Planning for Physically Grounded Video Generation</h3><p>Yuxiang Feng†, <strong>Juncheng Wang†</strong>, Chao Xu, et al.</p><a href="https://arxiv.org/abs/2605.18396" target="_blank" rel="noopener noreferrer" aria-label="Read NEWTON on arXiv">↗</a></article>
      <article><div><span class="vfm-status vfm-status--published">ECCV</span><span class="vfm-pub__year">2026</span></div><h3>Beyond Time Shifts: Adapting Omni-LLM as a Reference-Free Evaluator for Generative Audio-Visual Models</h3><p>Yijie Qian*†, <strong>Juncheng Wang†</strong>, Chao Xu, et al.</p><a href="https://arxiv.org/abs/2607.09091" target="_blank" rel="noopener noreferrer" aria-label="Read Beyond Time Shifts on arXiv">↗</a></article>
      <article><div><span class="vfm-status vfm-status--published">EACL</span><span class="vfm-pub__year">2026</span></div><h3>Guided by the Plan: Enhancing Faithful Autoregressive Text-to-Audio Generation with Guided Decoding</h3><p><strong>Juncheng Wang</strong>, Zhe Hu, Chao Xu, et al.</p><a href="https://arxiv.org/abs/2601.14304" target="_blank" rel="noopener noreferrer" aria-label="Read Guided by the Plan on arXiv">↗</a></article>
      <article><div><span class="vfm-status vfm-status--published">EMNLP Oral</span><span class="vfm-pub__year">2025</span></div><h3>Language Model Based Text-to-Audio Generation: Anti-Causally Aligned Collaborative Residual Transformers</h3><p><strong>Juncheng Wang</strong>, Chao Xu, Cheng Yu, et al.</p><a href="https://aclanthology.org/2025.emnlp-main.1322/" target="_blank" rel="noopener noreferrer" aria-label="Read the Siren paper in ACL Anthology">↗</a></article>
      <article><div><span class="vfm-status vfm-status--published">CVPR</span><span class="vfm-pub__year">2025</span></div><h3>Synchronized Video-to-Audio Generation via Mel Quantization-Continuum Decomposition</h3><p><strong>Juncheng Wang</strong>, Chao Xu, Cheng Yu, et al.</p><a href="https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Synchronized_Video-to-Audio_Generation_via_Mel_Quantization-Continuum_Decomposition_CVPR_2025_paper.html" target="_blank" rel="noopener noreferrer" aria-label="Read MelQCD in the CVF Open Access archive">↗</a></article>
      <article><div><span class="vfm-status vfm-status--published">ICLR Oral</span><span class="vfm-pub__year">2026</span></div><h3>Decentralized Attention Fails Centralized Signals: Rethinking Transformers for Medical Time Series</h3><p>Guoqi Yu*, <strong>Juncheng Wang</strong>, Chen Yang, et al.</p></article>
    </div>
  </section>

  <section class="vfm-section vfm-credentials" id="background" aria-labelledby="background-title">
    <div class="vfm-section__heading">
      <div>
        <p class="vfm-kicker">Background</p>
        <h2 id="background-title">Research with engineering depth.</h2>
      </div>
    </div>
    <div class="vfm-credentials__grid">
      <article><p class="vfm-credential__label">Education</p><h3>The Hong Kong Polytechnic University</h3><p>Ph.D. Candidate · 2024–2027 (expected)<br>Advisor: Prof. Emma Shujun Wang</p><h3>Northwestern Polytechnical University</h3><p>B.Sc., School of Automation · 2018–2022</p></article>
      <article><p class="vfm-credential__label">Selected recognition</p><h3>Research venues</h3><p>ECCV 2026 ×2 · ICLR 2026 Oral · EACL 2026 · EMNLP 2025 Oral · CVPR 2025 · IJCV · IEEE TMM · IEEE TIP</p><h3>Awards</h3><p>National Scholarship · Excellent Bachelor Thesis (2/239) · China Robot Contest First Prize</p></article>
      <article><p class="vfm-credential__label">Academic service</p><h3>Conference reviewer</h3><p>CVPR · ICCV · NeurIPS · ICLR · ACL Rolling Review</p><h3>Journal reviewer</h3><p>IEEE TPAMI · IJCV · IEEE TIP · IEEE TMM · IEEE TNNLS</p></article>
    </div>
  </section>

  <footer class="vfm-footer">
    <div><p class="vfm-kicker">Let’s build what comes next.</p><h2>Open to conversations about video foundation models and generative systems.</h2></div>
    <div class="vfm-footer__links">
      <a href="mailto:wjc2830@gmail.com">wjc2830@gmail.com</a>
      <a href="https://github.com/wjc2830" target="_blank" rel="noopener noreferrer">GitHub ↗</a>
      <a href="https://www.linkedin.com/in/juncheng-wang-85b449325/" target="_blank" rel="noopener noreferrer">LinkedIn ↗</a>
    </div>
    <p class="vfm-footer__note">Juncheng Wang · Hong Kong · Updated August 2026</p>
  </footer>
</div>
