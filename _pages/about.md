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
      <p class="academic-hero__statement">Scaling decides how well a model renders. It cannot decide what was never specified.</p>
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

  <section class="academic-section academic-roadmap" id="roadmap" aria-labelledby="roadmap-title">
    <header class="academic-section__heading">
      <h2 id="roadmap-title">A Roadmap for Video Generation</h2>
      <p>Where the conditioning comes from — and who is responsible for writing it.</p>
    </header>

    <div class="academic-roadmap__intro">
      <p class="academic-roadmap__thesis">Scaling decides how well a model <em>renders</em>.<br>It cannot decide what was never <em>specified</em>.</p>
      <p class="academic-roadmap__lead">A prompt is a lossy description of a physical scene &mdash; on VideoPhy-2 even the best models clear only <span class="rm-stat">about a third</span> of joint physical accuracy. More compute sharpens the renderer; it cannot recover what the prompt never contained. So the thing that keeps moving is <strong>the conditioning, and who writes it</strong>.</p>
    </div>

    <ol class="academic-roadmap__levels">
      <li class="academic-level" id="level-1" data-level="1">
        <div class="academic-level__aside">
          <p class="academic-level__tag"><span class="academic-level__num">L1</span>Text condition</p>
          <p class="academic-level__who">written by <span>a human</span></p>
        </div>
        <div class="academic-level__body">
          <h3>Say it</h3>
          <p class="academic-level__sub">The prompt is the whole contract.</p>
          <p>One sentence has to specify a long, coherent, high-rate signal, and all of that difficulty lands on the decoder. <span class="rm-work">Siren</span> spreads the load across residual codebooks instead of asking one model to carry all twelve.</p>
          <ul class="academic-level__papers">
            <li>
              <h4>Language Model Based Text-to-Audio Generation: Anti-Causally Aligned Collaborative Residual Transformers</h4>
              <p><span class="academic-level__role">Architecture</span>EMNLP 2025 &#183; first author</p>
            </li>
          </ul>
        </div>
      </li>

      <li class="academic-level" id="level-2" data-level="2">
        <div class="academic-level__aside">
          <p class="academic-level__tag"><span class="academic-level__num">L2</span>Reference condition</p>
          <p class="academic-level__who">written by <span>a human, in pixels</span></p>
        </div>
        <div class="academic-level__body">
          <h3>Show it</h3>
          <p class="academic-level__sub">Point at what language cannot describe.</p>
          <p>Layout, timing, identity &mdash; easier to show than to say, so conditioning turns structural. <span class="rm-work">DenseControl</span> places every individual in a dense crowd; <span class="rm-work">MelQCD</span> takes the condition from another modality entirely. Precision rises, and a human still has to supply the reference.</p>
          <ul class="academic-level__papers">
            <li>
              <h4>DenseControl: Instance-Level Controllable Synthesis of Dense Crowd Image</h4>
              <p><span class="academic-level__role">Spatial control</span>IEEE TMM 2026 &#183; first author</p>
            </li>
            <li>
              <h4>Synchronized Video-to-Audio Generation via Mel Quantization-Continuum Decomposition</h4>
              <p><span class="academic-level__role">Cross-modal control</span>CVPR 2025 &#183; first author</p>
            </li>
          </ul>
        </div>
      </li>

      <li class="academic-level" id="level-3" data-level="3">
        <div class="academic-level__aside">
          <p class="academic-level__tag"><span class="academic-level__num">L3</span>Searched condition</p>
          <p class="academic-level__who">written by <span>search, at inference</span></p>
        </div>
        <div class="academic-level__body">
          <h3>Find it</h3>
          <p class="academic-level__sub">Buy the missing half with test-time compute.</p>
          <p>If the specification is incomplete, go looking for the rest. <span class="rm-ext">Gen-Searcher</span> retrieves external evidence before it draws; my own work spends the budget internally &mdash; <span class="rm-work">Guided by the Plan</span> steers decoding to stay faithful to a plan, <span class="rm-work">Think Before You Move</span> reasons in latent motion space before the first pose. The ceiling rises while the weights stay put.</p>
          <ul class="academic-level__papers">
            <li>
              <h4>Guided by the Plan: Enhancing Faithful Autoregressive Text-to-Audio Generation with Guided Decoding</h4>
              <p><span class="academic-level__role">Steered decoding</span>EACL 2026 &#183; first author</p>
            </li>
            <li>
              <h4>Think Before You Move: Latent Motion Reasoning for Text-to-Motion Generation</h4>
              <p><span class="academic-level__role">Latent reasoning</span>TPAMI, major revision &#183; co-first author</p>
            </li>
          </ul>
        </div>
      </li>

      <li class="academic-level" id="level-4" data-level="4">
        <div class="academic-level__aside">
          <p class="academic-level__tag"><span class="academic-level__num">L4</span>Composed condition</p>
          <p class="academic-level__who">written by <span>a fixed pipeline</span></p>
        </div>
        <div class="academic-level__body">
          <h3>Arrange it</h3>
          <p class="academic-level__sub">Orchestration becomes a component.</p>
          <p>Once text, images, audio and clips all condition one model, arrangement is the bottleneck &mdash; <span class="rm-ext">MiniMax H3</span> promotes it to its own module. But a loop cannot close on a metric it does not have: <span class="rm-work">Beyond Time Shifts</span> turns an omni-LLM into a reference-free critic for audio-visual quality and sync.</p>
          <ul class="academic-level__papers">
            <li>
              <h4>Beyond Time Shifts: Adapting Omni-LLM as a Reference-Free Evaluator for Generative Audio-Visual Models</h4>
              <p><span class="academic-level__role">The verifier</span>ECCV 2026 &#183; co-first author</p>
            </li>
          </ul>
        </div>
      </li>

      <li class="academic-level academic-level--ours" id="level-5" data-level="5">
        <div class="academic-level__aside">
          <p class="academic-level__tag"><span class="academic-level__num">L5</span>Self-improving condition</p>
          <p class="academic-level__who">written by <span>a trained planner</span></p>
        </div>
        <div class="academic-level__body">
          <h3>Learn to arrange it</h3>
          <p class="academic-level__sub">Give the orchestrator a gradient.</p>
          <p><span class="rm-work">NEWTON</span> demotes generation to one action in an agent&rsquo;s toolbox: a planner orchestrates physics-aware tools, a verifier closes the loop for re-planning. Only the planner trains &mdash; VideoPhy-2 joint accuracy <span class="rm-stat">21.4&#8202;&rarr;&#8202;29.7</span> on LTX-Video and <span class="rm-stat">30.7&#8202;&rarr;&#8202;37.4</span> on Veo-3.1, with both generators untouched. <span class="rm-work">ROC-Agent</span> runs the same loop one level up, on research itself. What improves is the harness, not the weights.</p>
          <ul class="academic-level__papers">
            <li>
              <h4>NEWTON: Agentic Planning for Physically Grounded Video Generation</h4>
              <p><span class="academic-level__role">Trainable orchestration</span>Preprint, under review &#183; co-first author</p>
            </li>
            <li>
              <h4>ROC-Agent: Research Orchestration via Cyclic Agents for Autonomous Deep Learning Experimentation</h4>
              <p><span class="academic-level__role">The loop, one level up</span>Under review &#183; first author</p>
            </li>
          </ul>
        </div>
      </li>
    </ol>

    <div class="academic-roadmap__closing">
      <p class="academic-roadmap__closing-lead">The next level gives the weights back what the harness learned.</p>
      <p>Levels 1&#8211;4 changed who writes the conditioning; L5 made that writer trainable. What is missing is internalization &mdash; folding verified harness improvements back into the generator, until the model no longer needs the scaffolding. That is where I am working now, and I would happily be argued out of it. <a href="mailto:wjc2830@gmail.com">Get in touch</a>.</p>
    </div>
  </section>

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
