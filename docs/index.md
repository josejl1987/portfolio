---
layout: default
title: JoseJL
---

<div class="hero">
  <div class="hero__title">JoseJL</div>
  <div class="hero__subtitle">
    Game Engineering &amp; Systems Architect.<br>
    8+ years professional experience (Healthcare/Cloud) specializing in Rendering, Reverse Engineering, and Tooling.
  </div>
  <div class="hero__links">
    <a class="pill" href="https://github.com/josejl1987">GitHub</a>
    <a class="pill" href="#career">Professional Exp.</a>
    <a class="pill" href="#plagueng">plagueng (Contract)</a>
  </div>
</div>

<nav class="toc">
  <a href="#plagueng">plagueng (bgfx)</a>
  <a href="#pnkr">pnkr (Vulkan)</a>
  <a href="#career">Healthcare Systems (8 Years)</a>
  <a href="#geofront">Trails from Zero (Official)</a>
  <a href="#brandish2">Brandish 2</a>
</nav>

<section class="project" id="plagueng">
  <div class="project__top">
    <h2 class="project__title">plagueng — D3D9 Engine Modernization (bgfx)</h2>
    <div class="project__meta">Role: Contract Engine Programmer (C++ / bgfx)</div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        <strong>Contracted engineering work</strong> to evolve a legacy D3D9-era architecture. The goal was to decouple the game logic from the graphics API and introduce modern rendering features via the <strong>bgfx</strong> abstraction layer.
      </p>

      <ul class="bullets">
        <li><b>bgfx Integration:</b> Replaced the fixed-function D3D9 pipeline with a flexible rendering backend.</li>
        <li><b>PBR Pipeline:</b> Implemented physically based rendering materials and lighting models into the legacy engine.</li>
        <li><b>Clustered Lighting:</b> Frustum/cluster partitioning shaders designed to scale dynamic lights.</li>
        <li><b>GPU-Driven Tools:</b> Interactive terrain authoring workflows with GPU-side data flow.</li>
      </ul>
    </div>

    <div class="media">
      <figure>
        <img src="https://docs.khosmium.com/~gitbook/image?url=https%3A%2F%2F4192102853-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FXgWn8Pw4fHYy81wa6DEA%252Fuploads%252FKrbLUNn9r5RZRAM7mzCz%252F4b700c793de829d18064304de4cd491d_original.webp%3Falt%3Dmedia%26token%3Db1391134-b7e9-456b-9584-67cd7a7eb375&width=1200&dpr=1&quality=100&sign=b6cf5187&sv=2"
             alt="plagueng rendering screenshot" loading="lazy">
        <figcaption>Rendering capture from the plagueng engine (bgfx).</figcaption>
      </figure>
    </div>
  </div>
</section>

<section class="project" id="pnkr">
  <div class="project__top">
    <h2 class="project__title">pnkr_ng — Vulkan Rendering Engine</h2>
    <div class="project__meta">Repository: <a href="https://github.com/josejl1987/pnkr_ng/">github.com/josejl1987/pnkr_ng/</a></div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        <strong>Work in Progress.</strong> A ground-up rendering engine focused on explicit graphics API management using <strong>Vulkan</strong>.
      </p>

      <ul class="bullets">
        <li><b>Vulkan Backend:</b> Explicit synchronization and resource management.</li>
        <li><b>Modern C++:</b> Utilizing C++20 features for engine architecture.</li>
        <li><b>Architecture:</b> Designed for high-performance, low-overhead draw dispatch.</li>
      </ul>
    </div>
  </div>
</section>

<section class="project" id="career">
  <div class="project__top">
    <h2 class="project__title">Professional Experience — Healthcare Systems</h2>
    <div class="project__meta">Experience: 8 Years (C# / React / Cloud)</div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        Extensive professional background developing complex, high-reliability systems for the healthcare industry.
      </p>

      <ul class="bullets">
        <li><b>Cloud-Based Imaging:</b> Developed cloud-native medical image visualization solutions (C# / React), optimizing for performance and low latency.</li>
        <li><b>Complex Scheduling:</b> Architected and maintained large-scale scheduling systems for clinical environments.</li>
        <li><b>Full Stack Architecture:</b> Managed the full lifecycle of feature development from backend logic (C#) to frontend implementation (React).</li>
      </ul>
    </div>
  </div>
</section>

<section class="project" id="geofront">
  <div class="project__top">
    <h2 class="project__title">Geofront — Trails from Zero / Trails to Azure</h2>
    <div class="project__meta">Role: Lead Programmer (Reverse Engineering &amp; Systems)</div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        Fan localization engineering project that served as the technical foundation for the <strong>official English releases by NIS America</strong>.
      </p>
      
      <ul class="bullets">
        <li><b>Official Adoption:</b> This work was acquired and used as the base for the commercial release on PC and Switch.</li>
        <li><b>UI / Input Systems:</b> Complete controller remapping flows; integration of new actions into existing input + UI paths.</li>
        <li><b>Frame Pacing:</b> Decoupled game logic from rendering to validate timing-sensitive behavior beyond the original 30 FPS cap.</li>
        <li><b>Stability:</b> Targeted fixes for resource lifetime issues exposed by long play sessions.</li>
      </ul>
      
      <div class="callout" id="media">
        <div class="callout__title">Feature Showcase</div>
        <div class="video">
          <iframe
            src="https://www.youtube.com/embed/zULIUYoSZRU"
            title="Trails from Zero Feature Demo"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        </div>
      </div>
    </div>

    <div class="media">
      <figure>
        <img src="assets/geofront_options_controller.png" alt="Options / controller mapping UI" loading="lazy">
        <figcaption>Reverse engineered Options + Controller mapping UI, including new actions like Message Log.</figcaption>
      </figure>
      <figure>
        <img src="assets/geofront_dialogue.png" alt="Dialogue presentation" loading="lazy">
        <figcaption>Dialogue presentation sample.</figcaption>
      </figure>
    </div>
  </div>
</section>

<section class="project" id="coz">
  <div class="project__top">
    <h2 class="project__title">Committee of Zero — Robotics;Notes Elite / Chaos;Head Noah</h2>
    <div class="project__meta">Role: Programmer / Hacker (Engine-side patching)</div>
  </div>

  <div class="project__grid">
    <div>
      <ul class="bullets">
        <li><b>Runtime Patching:</b> Changes delivered via DLL injection without engine source access.</li>
        <li><b>Text/UI Fixes:</b> Solved presentation and interaction edge cases; regression handling.</li>
        <li><b>Compatibility:</b> Practical fixes across common PC configurations and locales.</li>
      </ul>
    </div>

    <div class="media">
      <figure>
        <img src="assets/coz_rne_before_after.png" alt="Robotics;Notes Elite before/after" loading="lazy">
        <figcaption>Example “before/after” text improvements (Robotics;Notes Elite).</figcaption>
      </figure>
    </div>
  </div>
</section>

<section class="project" id="brandish2">
  <div class="project__top">
    <h2 class="project__title">Brandish 2 (PC-98 / DOS)</h2>
    <div class="project__meta">Role: Programmer (Reverse Engineering + Translation Pipeline)</div>
  </div>

  <div class="project__grid">
    <div>
      <ul class="bullets">
        <li><b>x86 Segmented Mode:</b> Reverse engineered a DOS game running in 16-bit real/segmented mode.</li>
        <li><b>Memory Constraints:</b> Solved extremely tight memory limits inherent to the architecture when injecting variable-width English text.</li>
        <li><b>Tooling:</b> Wrote workflows to extract/insert/verify content changes in legacy binary formats.</li>
      </ul>
    </div>

    <div class="media">
      <figure>
        <img src="assets/brandish2_pc98.png" alt="Brandish 2 on PC-98 CRT" loading="lazy">
        <figcaption>In-game English text on original-style output (CRT capture).</figcaption>
      </figure>
    </div>
  </div>
</section>

<section class="project" id="focus">
  <div class="project__top">
    <h2 class="project__title">Technical focus</h2>
  </div>

  <div class="project__grid">
    <div>
      <ul class="bullets">
        <li><b>Rendering:</b> Vulkan, bgfx, D3D9/11, PBR, GPU-driven pipelines.</li>
        <li><b>Systems:</b> Frame pacing, Input abstraction, Memory management, Resource lifetime.</li>
        <li><b>Reverse Engineering:</b> Working without source, binary patching, x86 segmentation/legacy constraints.</li>
        <li><b>Tooling:</b> Automation for content-heavy projects, asset extraction/insertion pipelines.</li>
      </ul>
    </div>
    <div class="media">
      <div class="note">
        <b>Note:</b> This page avoids distributing copyrighted game data. Screenshots and clips are shown for demonstration.
      </div>
    </div>
  </div>
</section>
