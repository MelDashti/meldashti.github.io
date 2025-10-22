---
layout: single
permalink: /
title: "Meelad Dashti"
excerpt: "AI/ML engineer and researcher crafting agentic, multimodal systems that bridge research and production."
author_profile: false
classes: landing-page
header:
  overlay_color: "#070B1A"
---

<div class="hero-panel">
  <div class="hero-content">
    <p class="hero-kicker">AI/ML Engineer · Vision-Language Researcher · Agentic Systems Builder</p>
    <h1>Meelad Dashti</h1>
    <p class="hero-lede">
      I design and ship intelligent products that blend cutting-edge research with production-grade engineering.
      My current focus is on hyperbolic compositionality in vision-language models, real-time meeting intelligence,
      and robust RAG pipelines that keep humans in the loop without slowing them down.
    </p>
    <div class="hero-cta">
      <a class="btn btn--primary" href="/files/Meelad_Dashti_CV.pdf" target="_blank" rel="noopener">Download CV</a>
      <a class="btn btn--outline" href="#contact">Let’s Connect</a>
    </div>
    <ul class="hero-meta">
      <li><i class="fas fa-map-marker-alt" aria-hidden="true"></i> Enschede, Netherlands · Turin, Italy</li>
      <li><i class="fas fa-phone-alt" aria-hidden="true"></i> +39 351 528 1830</li>
      <li><i class="fas fa-envelope" aria-hidden="true"></i> <a href="mailto:meeladd7@gmail.com">meeladd7@gmail.com</a></li>
      <li><i class="fab fa-linkedin" aria-hidden="true"></i> <a href="https://linkedin.com/in/MeeladDashti" target="_blank" rel="noopener">linkedin.com/in/MeeladDashti</a></li>
      <li><i class="fab fa-github" aria-hidden="true"></i> <a href="https://github.com/meldashti" target="_blank" rel="noopener">github.com/meldashti</a></li>
    </ul>
  </div>
  <div class="hero-highlight">
    <div class="stat-card">
      <span class="stat-value">&lt;2 s</span>
      <span class="stat-label">Latency achieved for dual transcription pipelines</span>
    </div>
    <div class="stat-card">
      <span class="stat-value">80%</span>
      <span class="stat-label">Reduction in hallucinations via custom meeting intelligence stack</span>
    </div>
    <div class="stat-card">
      <span class="stat-value">9-stage</span>
      <span class="stat-label">LangGraph agentic workflow with human-in-the-loop refinement</span>
    </div>
  </div>
</div>

<section class="section" id="experience">
  <div class="section-heading">
    <h2>Experience</h2>
    <p>Building production-ready AI that fuses RAG, streaming, and agentic reasoning.</p>
  </div>
  <div class="timeline">
    <article class="timeline-item">
      <header>
        <h3>Zirak srl</h3>
        <div class="item-meta">AI/ML Engineer (Hybrid) · Apr 2025 – Present · Turin, Italy</div>
      </header>
      <ul>
        <li>Engineered a real-time AI meeting platform using WhisperX and Faster-Whisper with VAD filtering, sliding-window buffers, and custom deduplication, delivering &lt;2 s latency.</li>
        <li>Built an end-to-end RAG system with ChromaDB, BGE-M3 embeddings, cross-encoder reranking, and score-based augmentation to maximize context relevance.</li>
        <li>Architected LangGraph agent workflows with human-in-the-loop refinement across nine stages, using structured prompting and scope-aware logic for automated meeting intelligence.</li>
        <li>Developed Python FastAPI microservices with async WebSocket streaming, singleton model orchestration, and multi-provider LLM integration (LMStudio, Groq) powering Electron/React clients.</li>
        <li>Deployed TalkToSQL, a safeguarded natural-language-to-SQL assistant leveraging Qwen-3-14B, multi-state validation, and human approval.</li>
      </ul>
    </article>
    <article class="timeline-item">
      <header>
        <h3>AROL Group &amp; Politecnico di Torino</h3>
        <div class="item-meta">AI/ML Engineer (Course Project) &amp; Lab Assistant · Jun 2024 – Jul 2025 · Turin, Italy</div>
      </header>
      <ul>
        <li>Fine-tuned LLaMA 3.2 with LoRA on a domain Q&amp;A corpus, applying 4/8-bit quantization to reduce memory and latency for deployment.</li>
        <li>Implemented a RAG pipeline with Pinecone vector search and deployed the chatbot on Hugging Face Spaces for stakeholder demos.</li>
        <li>Guided students in C/C++ optimization, memory management, and performance debugging as a System and Device Programming lab assistant.</li>
      </ul>
    </article>
    <article class="timeline-item">
      <header>
        <h3>Pishgaman Innovation Accelerator</h3>
        <div class="item-meta">Android Developer · May 2022 – Feb 2023 · Yazd, Iran</div>
      </header>
      <ul>
        <li>Delivered a city-wide complaint management app using MVVM and RESTful APIs, streamlining citizen reporting workflows.</li>
      </ul>
    </article>
  </div>
</section>

<section class="section" id="education">
  <div class="section-heading">
    <h2>Education</h2>
    <p>Blending AI research rigor with software engineering fundamentals.</p>
  </div>
  <div class="card-grid">
    <article class="info-card">
      <h3>University of Twente</h3>
      <p class="info-meta">Master Thesis · Jul 2025 – Apr 2026 · Enschede, Netherlands</p>
      <p>Hyperbolic compositionality in vision-language models, focusing on multimodal safety representations and task-vector experiments.</p>
    </article>
    <article class="info-card">
      <h3>Politecnico di Torino</h3>
      <p class="info-meta">M.Sc. Computer Engineering (AI &amp; Data Analytics) · 2023 – Apr 2026 · Turin, Italy · 104/110 (expected)</p>
      <p>Specialising in AI, data analytics, and agentic systems with hands-on lab leadership.</p>
    </article>
    <article class="info-card">
      <h3>Yazd University</h3>
      <p class="info-meta">B.Sc. Computer Engineering (Software) · 2018 – 2022 · Yazd, Iran</p>
      <p>Built a strong foundation in software engineering, algorithms, and distributed systems.</p>
    </article>
  </div>
</section>

<section class="section" id="projects">
  <div class="section-heading">
    <h2>Research &amp; Projects</h2>
    <p>Exploring new frontiers in multimodal reasoning and intelligent tooling.</p>
  </div>
  <div class="card-grid">
    <article class="info-card">
      <h3>Hyperbolic Compositionality in Vision-Language Models</h3>
      <p class="info-meta">Master thesis · Ongoing</p>
      <p>Developing hyperbolic embedding strategies, task-vector merging, and ablation studies for safer multimodal reasoning across downstream V-L benchmarks.</p>
    </article>
    <article class="info-card">
      <h3>Enhancing Software Maintainability through LLM-Assisted Refactoring</h3>
      <p class="info-meta">PROFES 2025 · Accepted</p>
      <p>Created a zero-shot LLM framework for automated Python refactoring, evaluating model and metric impacts on code quality.</p>
    </article>
    <article class="info-card">
      <h3>TalkToSQL</h3>
      <p class="info-meta">Production deployment</p>
      <p>Secure natural-language-to-SQL assistant powered by LangGraph orchestration, multi-state validation, and human approvals.</p>
    </article>
  </div>
</section>

<section class="section" id="skills">
  <div class="section-heading">
    <h2>Technical Stack</h2>
    <p>Tools I reach for when translating ideas into shipped systems.</p>
  </div>
  <div class="pill-groups">
    <div>
      <h4>AI &amp; ML</h4>
      <div class="pill-row">
        <span class="pill">PyTorch</span>
        <span class="pill">TensorFlow</span>
        <span class="pill">LangChain</span>
        <span class="pill">LangGraph</span>
        <span class="pill">RAG Systems</span>
        <span class="pill">Vector DBs (Pinecone, ChromaDB)</span>
        <span class="pill">LoRA / QLoRA</span>
        <span class="pill">Prompt Engineering</span>
        <span class="pill">Computer Vision</span>
        <span class="pill">NLP</span>
        <span class="pill">Diffusion Models</span>
        <span class="pill">WhisperX</span>
        <span class="pill">Faster-Whisper</span>
        <span class="pill">PyAnnote</span>
      </div>
    </div>
    <div>
      <h4>Programming</h4>
      <div class="pill-row">
        <span class="pill">Python</span>
        <span class="pill">Java</span>
        <span class="pill">C++</span>
        <span class="pill">JavaScript</span>
        <span class="pill">SQL</span>
        <span class="pill">Kotlin</span>
      </div>
    </div>
    <div>
      <h4>Tools &amp; Frameworks</h4>
      <div class="pill-row">
        <span class="pill">FastAPI</span>
        <span class="pill">WebSockets</span>
        <span class="pill">Docker</span>
        <span class="pill">Git</span>
        <span class="pill">REST APIs</span>
        <span class="pill">Electron</span>
        <span class="pill">React</span>
        <span class="pill">MCP Servers</span>
        <span class="pill">OpenAI Whisper</span>
        <span class="pill">CLIP</span>
        <span class="pill">pandas</span>
        <span class="pill">NumPy</span>
        <span class="pill">Kaolin</span>
        <span class="pill">Open3D</span>
      </div>
    </div>
  </div>
</section>

<section class="section" id="languages">
  <div class="section-heading">
    <h2>Languages</h2>
    <p>Comfortable working across multicultural teams and international environments.</p>
  </div>
  <div class="pill-row">
    <span class="pill">English (C2)</span>
    <span class="pill">Italian (Elementary)</span>
    <span class="pill">Persian (Native)</span>
    <span class="pill">Hindi (Fluent)</span>
  </div>
</section>

<section class="section section--accent" id="contact">
  <div class="section-heading">
    <h2>Let’s build the future of AI together</h2>
    <p>Open to industry collaborations, research partnerships, and advanced AI/ML engineering roles.</p>
  </div>
  <div class="contact-actions">
    <a class="btn btn--primary" href="mailto:meeladd7@gmail.com">Email Me</a>
    <a class="btn btn--outline" href="https://linkedin.com/in/MeeladDashti" target="_blank" rel="noopener">Connect on LinkedIn</a>
  </div>
</section>

