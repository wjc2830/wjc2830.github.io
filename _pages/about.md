---
permalink: /
title: ""
excerpt: "Video foundation model researcher working on generation, planning, and multimodal evaluation."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="academic-home">
  <header class="academic-hero" id="about">
    <div class="academic-hero__copy">
      <p class="academic-eyebrow">Video Foundation Model Researcher</p>
      <h1>Juncheng Wang</h1>
      <p class="academic-hero__lead">I work on video foundation models, with a focus on large-scale training, agentic generation, and multimodal evaluation.</p>
      <p class="academic-hero__statement">I am interested in generative systems that improve not only their outputs, but the way they generate.</p>
      <p class="academic-hero__current">Currently researching next-generation video foundation models at <strong>Tencent Hunyuan</strong>. Previously at <strong>AMD</strong> and <strong>Alibaba Wan</strong>.</p>
      <nav class="academic-links" aria-label="Profile links">
        <a href="mailto:wjc2830@gmail.com">Email</a>
        <a href="https://github.com/wjc2830" target="_blank" rel="noopener noreferrer">GitHub</a>
        <a href="https://www.linkedin.com/in/juncheng-wang-85b449325/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      </nav>
    </div>
    <figure class="academic-portrait">
      <img src="{{ '/images/research/portrait.webp' | relative_url }}" width="640" height="760" alt="Juncheng Wang" fetchpriority="high">
      <figcaption>Ph.D. Candidate, The Hong Kong Polytechnic University</figcaption>
    </figure>
  </header>

  <section class="academic-section" id="research" aria-labelledby="research-title">
    <header class="academic-section__heading">
      <h2 id="research-title">Selected Work</h2>
      <p>Generation, planning, and feedback for multimodal systems.</p>
    </header>

    <div class="academic-projects">
      <article class="academic-project academic-project--newton">
        <figure class="academic-project__media academic-project__media--video">
          <video muted loop playsinline controls preload="metadata" poster="{{ '/images/research/newton-loop.webp' | relative_url }}" aria-label="NEWTON agentic video generation teaser">
            <source src="{{ '/images/research/newton-loop.mp4' | relative_url }}" type="video/mp4">
          </video>
          <figcaption>NEWTON: planning, tool use, generation, and verification in one loop.</figcaption>
        </figure>
        <div class="academic-project__content">
          <p class="academic-project__meta">Agentic video generation · Preprint, under review · Co-first author</p>
          <h3>NEWTON: Agentic Planning for Physically Grounded Video Generation</h3>
          <p>A plan–execute–verify system that treats video generation as one action inside a larger workflow, orchestrating physics-aware tools and critic feedback.</p>
          <p class="academic-project__links">
            <a href="https://arxiv.org/abs/2605.18396" target="_blank" rel="noopener noreferrer">Paper</a>
            <a href="https://newton026.github.io/newton/" target="_blank" rel="noopener noreferrer">Project</a>
            <a href="https://github.com/CUTEPKQ/NEWTON" target="_blank" rel="noopener noreferrer">Code</a>
          </p>
        </div>
      </article>

      <article class="academic-project">
        <figure class="academic-project__media">
          <img src="{{ '/images/research/beyond-time-shifts.webp' | relative_url }}" width="1600" height="853" alt="Training framework for a reference-free audio-visual evaluator" loading="lazy" decoding="async">
        </figure>
        <div class="academic-project__content">
          <p class="academic-project__meta">Multimodal evaluation · ECCV 2026 · Co-first author</p>
          <h3>Beyond Time Shifts: Adapting Omni-LLM as a Reference-Free Evaluator for Generative Audio-Visual Models</h3>
          <p>A learned critic for fine-grained audio-visual quality and synchronization, designed to turn generated outputs into useful feedback.</p>
          <p class="academic-project__links">
            <a href="https://arxiv.org/abs/2607.09091" target="_blank" rel="noopener noreferrer">Paper</a>
            <a href="https://chenhaoqcdyq.github.io/BeyondTimeShifts/" target="_blank" rel="noopener noreferrer">Project</a>
            <a href="https://github.com/chenhaoqcdyq/BeyondTimeShifts" target="_blank" rel="noopener noreferrer">Code</a>
          </p>
        </div>
      </article>

      <article class="academic-project">
        <figure class="academic-project__media">
          <img src="{{ '/images/research/melqcd.webp' | relative_url }}" width="1200" height="620" alt="MelQCD video-to-audio generation overview" loading="lazy" decoding="async">
        </figure>
        <div class="academic-project__content">
          <p class="academic-project__meta">Multimodal generation · CVPR 2025 · First author</p>
          <h3>Synchronized Video-to-Audio Generation via Mel Quantization-Continuum Decomposition</h3>
          <p>Decomposes audio into predictable discrete structure and expressive continuous detail for synchronized video-conditioned generation.</p>
          <p class="academic-project__links">
            <a href="https://arxiv.org/abs/2503.06984" target="_blank" rel="noopener noreferrer">Paper</a>
            <a href="https://wjc2830.github.io/MelQCD/" target="_blank" rel="noopener noreferrer">Project</a>
            <a href="https://github.com/wjc2830/MelQCD-main" target="_blank" rel="noopener noreferrer">Code</a>
          </p>
        </div>
      </article>

      <article class="academic-project">
        <figure class="academic-project__media">
          <img src="{{ '/images/research/siren.webp' | relative_url }}" width="1400" height="804" alt="Siren collaborative residual transformer pipeline for autoregressive text-to-audio generation" loading="lazy" decoding="async">
        </figure>
        <div class="academic-project__content">
          <p class="academic-project__meta">Autoregressive audio generation · EMNLP 2025 Oral · First author</p>
          <h3>Language Model Based Text-to-Audio Generation: Anti-Causally Aligned Collaborative Residual Transformers</h3>
          <p>Introduces Siren, a collaborative residual-transformer architecture that resolves imbalanced RVQ prediction difficulty and improves autoregressive text-to-audio generation.</p>
          <p class="academic-project__links">
            <a href="https://aclanthology.org/2025.emnlp-main.1322/" target="_blank" rel="noopener noreferrer">Paper</a>
          </p>
        </div>
      </article>
    </div>
  </section>

  <section class="academic-section" id="experience" aria-labelledby="experience-title">
    <header class="academic-section__heading">
      <h2 id="experience-title">Industry Experience</h2>
    </header>

    <div class="academic-experience__list">
      <article class="academic-experience__item">
        <p class="academic-experience__date">2026.06 — Present</p>
        <div>
          <h3>Tencent · Hunyuan-Video Group</h3>
          <p class="academic-experience__role">Qingyun (Project Up) Intern</p>
          <p>Pre-training research for the next generation of Hunyuan video foundation models.</p>
          <p class="academic-experience__mentor">Working with Dr. Jianwei Zhang</p>
        </div>
      </article>

      <article class="academic-experience__item">
        <p class="academic-experience__date">2026.01 — 2026.06</p>
        <div>
          <h3>Advanced Micro Devices (AMD)</h3>
          <p class="academic-experience__role">Student Research Fellow</p>
          <p>Efficient flow-model research for video generation.</p>
          <p class="academic-experience__mentor">Mentored by Dr. Tong Shen and Dr. Emad Barsoum</p>
        </div>
      </article>

      <article class="academic-experience__item">
        <p class="academic-experience__date">2023.09 — 2025.09</p>
        <div>
          <h3>Alibaba · Wan Group, Tongyi Lab</h3>
          <p class="academic-experience__role">Research Intern</p>
          <p>Post-training for foundational video generation and audio-centric generative modeling.</p>
          <p class="academic-experience__mentor">Mentored by Dr. Chao Xu, Lei Shang, and Dr. Liefeng Bo</p>
        </div>
      </article>
    </div>
  </section>

  <section class="academic-section" id="publications" aria-labelledby="publications-title">
    <header class="academic-section__heading">
      <h2 id="publications-title">Publications</h2>
      <p>† Equal contribution. * Junior student advisee.</p>
    </header>

    <ol class="academic-publication-list">
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>Under review</span></div>
        <div class="academic-publication__body"><h3>SphereFlow: Missing Modality Imputation via Geometric Transport on Hypersphere</h3><p><strong>Juncheng Wang</strong> et al.</p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>Under review</span></div>
        <div class="academic-publication__body"><h3>ROC-Agent: Research Orchestration via Cyclic Agents for Autonomous Deep Learning Experimentation</h3><p><strong>Juncheng Wang</strong> et al.</p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>ECCV 2026</span></div>
        <div class="academic-publication__body"><h3>Beyond Time Shifts: Adapting Omni-LLM as a Reference-Free Evaluator for Generative Audio-Visual Models</h3><p>Yijie Qian*†, <strong>Juncheng Wang†</strong>, Chao Xu, et al.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2607.09091" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>ECCV 2026</span></div>
        <div class="academic-publication__body"><h3>Progression as Latent Drift: Generative Forecasting of Slow-Evolving Pathologies</h3><p>Yuxiang Feng*†, <strong>Juncheng Wang†</strong>, Chao Xu, et al.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2607.08270" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>IEEE TMM 2026</span></div>
        <div class="academic-publication__body"><h3>DenseControl: Instance-Level Controllable Synthesis of Dense Crowd Image</h3><p><strong>Juncheng Wang</strong>, Lei Shang, Wang Lu, Baigui Sun, and Shujun Wang.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2606.15592" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>Preprint</span></div>
        <div class="academic-publication__body"><h3>NEWTON: Agentic Planning for Physically Grounded Video Generation</h3><p>Yuxiang Feng†, <strong>Juncheng Wang†</strong>, Chao Xu, et al.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2605.18396" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>ICLR 2026 Oral</span></div>
        <div class="academic-publication__body"><h3>Decentralized Attention Fails Centralized Signals: Rethinking Transformers for Medical Time Series</h3><p>Guoqi Yu*, <strong>Juncheng Wang</strong>, Chen Yang, Jing Qin, Angelica I. Aviles-Rivero, and Shujun Wang.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2602.18473" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>EACL 2026</span></div>
        <div class="academic-publication__body"><h3>Guided by the Plan: Enhancing Faithful Autoregressive Text-to-Audio Generation with Guided Decoding</h3><p><strong>Juncheng Wang</strong>, Zhe Hu, Chao Xu, Siyue Ren, Yuxiang Feng, Yang Liu, Baigui Sun, and Shujun Wang.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2601.14304" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>IJCV 2026</span></div>
        <div class="academic-publication__body"><h3>Exploring Scale Shift in Crowd Localization under the Context of Domain Generalization</h3><p><strong>Juncheng Wang</strong>, Lei Shang, Ziqi Liu, Wang Lu, Xixu Hu, Zhe Hu, Jindong Wang, and Shujun Wang.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2510.19330" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>TPAMI major revision</span></div>
        <div class="academic-publication__body"><h3>Think Before You Move: Latent Motion Reasoning for Text-to-Motion Generation</h3><p>Yijie Qian†, <strong>Juncheng Wang†</strong>, Yuxiang Feng, Chao Xu, et al.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2512.24100" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>EMNLP 2025 Oral</span></div>
        <div class="academic-publication__body"><h3>Language Model Based Text-to-Audio Generation: Anti-Causally Aligned Collaborative Residual Transformers</h3><p><strong>Juncheng Wang</strong>, Chao Xu, Cheng Yu, Zhe Hu, Haoyu Xie, Guoqi Yu, Lei Shang, and Shujun Wang.</p><p class="academic-publication__links"><a href="https://aclanthology.org/2025.emnlp-main.1322/" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>CVPR 2025</span></div>
        <div class="academic-publication__body"><h3>Synchronized Video-to-Audio Generation via Mel Quantization-Continuum Decomposition</h3><p><strong>Juncheng Wang</strong>, Chao Xu, Cheng Yu, Lei Shang, Zhe Hu, Shujun Wang, and Liefeng Bo.</p><p class="academic-publication__links"><a href="https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Synchronized_Video-to-Audio_Generation_via_Mel_Quantization-Continuum_Decomposition_CVPR_2025_paper.html" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
      <li class="academic-publication">
        <div class="academic-publication__meta"><span>IEEE TIP 2023</span></div>
        <div class="academic-publication__body"><h3>Crowd Localization from Gaussian Mixture Scoped Knowledge and Scoped Teacher</h3><p><strong>Juncheng Wang</strong>, Junyu Gao, Yuan Yuan, and Qi Wang.</p><p class="academic-publication__links"><a href="https://arxiv.org/abs/2206.05717" target="_blank" rel="noopener noreferrer">Paper</a></p></div>
      </li>
    </ol>
  </section>

  <footer class="academic-footer">
    <p>© 2026 Juncheng Wang</p>
    <nav aria-label="Footer links">
      <a href="mailto:wjc2830@gmail.com">Email</a>
      <a href="https://github.com/wjc2830" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a href="https://www.linkedin.com/in/juncheng-wang-85b449325/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
    </nav>
  </footer>

  <script>
    (function () {
      var reduceMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
      if (reduceMotion) {
        window.addEventListener('load', function () {
          if (window.jQuery) window.jQuery('a').off('click.smoothscroll');
        });
      }
      var video = document.querySelector('.academic-project--newton video');
      if (!video || !('IntersectionObserver' in window) || reduceMotion) return;
      var observer = new IntersectionObserver(function (entries) {
        entries.forEach(function (entry) {
          if (entry.isIntersecting) {
            video.play().catch(function () {});
          } else {
            video.pause();
          }
        });
      }, { threshold: 0.35 });
      observer.observe(video);
    }());
  </script>
</div>
