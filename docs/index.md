---
layout: default
title: JoseJL
---

<div class="hero">
  <div class="hero__title">JoseJL</div>
  <div class="hero__contact">
    <a href="mailto:josejl1987@gmail.com">josejl1987@gmail.com</a>
  </div>
  <div class="hero__subtitle">
    Game Engineering &amp; Systems Architect.<br>
    8+ years professional experience (Healthcare/Cloud) specializing in Rendering, Reverse Engineering, and Tooling.
  </div>
  <div class="hero__links">
    <a class="pill" href="https://github.com/josejl1987">GitHub</a>
    <a class="pill" href="#career">Professional Exp.</a>
    <a class="pill" href="#plagueng">plagueng (Contract)</a>
    <a class="pill" href="#geofront">Geofront (Official)</a>
  </div>
</div>

<nav class="toc">
  <a href="#plagueng">plagueng (bgfx)</a>
  <a href="#pnkr">pnkr (Vulkan)</a>
  <a href="#glider">Glider, the Folding Hero (UE4)</a>
  <a href="#career">Healthcare Systems (8 Years)</a>
  <a href="#geofront">Geofront — Crossbell Arc</a>
  <a href="#coz">Chaos;Head Noah</a>
  <a href="#brandish2">Brandish 2</a>
  <a href="#ys8">Ys VIII Graphics Mod</a>
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
	
      <div class="callout" id="media">
        <div class="callout__title">Project Trailer</div>
        <div class="video">
          <iframe
            src="https://www.youtube.com/embed/NkcVND3AKks"
            title="Khosmium alpha teaser"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        </div>
      </div>
  </div>
</section>

<section class="project" id="pnkr">
  <div class="project__top">
    <h2 class="project__title">pnkr_ng — Vulkan Research Engine</h2>
    <div class="project__meta">
        <strong>Status:</strong> Work in Progress / Research Project
        <br>
        <strong>Tech:</strong> Vulkan, C++20, Slang, enkiTS, KTX2
        <br>
        Repository: <a href="https://github.com/josejl1987/pnkr_ng/">github.com/josejl1987/pnkr_ng/</a>
    </div>
  </div>

  <div class="project__grid">
    <div class="project__description">
      <p>
        A custom rendering framework developed to research explicit graphics API paradigms and GPU-driven visibility. The project focuses on minimizing CPU overhead by moving draw call generation and resource binding logic directly to the GPU.
      </p>

      <div class="project__sub-grid">
        <div>
          <h3>Core Architecture</h3>
          <ul class="bullets">
            <li><strong>GPU-Driven Pipeline:</strong> Implements compute-based frustum culling and DrawIndexedIndirectCount to consolidate scene rendering into a few multi-draw calls.</li>
            <li><strong>Pass-Based FrameGraph:</strong> Uses a directed acyclic graph to manage transient resources, automatically generating Vulkan memory barriers and layout transitions based on pass dependencies.</li>
            <li><strong>Bindless Resource Heaps:</strong> Utilizes descriptor indexing to provide shaders with global access to textures and buffers, removing the need for traditional per-object descriptor set rebinding.</li>
            <li><strong>Task-Based Execution:</strong> Integrated enkiTS for multi-threaded command buffer recording and asset processing.</li>
          </ul>
        </div>
        <div>
          <h3>Systems & Tooling</h3>
          <ul class="bullets">
            <li><strong>Progressive Texture Streaming:</strong> Background loading of KTX2/Basis textures with an incremental mip-exposure system and min_lod clamping to maintain visual consistency during uploads.</li>
            <li><strong>Memory Management:</strong> Specialized linear allocators for per-frame transient data and VMA integration for long-term GPU resource allocations.</li>
            <li><strong>Diagnostics:</strong> Custom GPU timeline profiler, real-time BDA (Buffer Device Address) auditing to track memory faults, and runtime log-level filtering.</li>
            <li><strong>Modular Shaders:</strong> Built with Slang to facilitate shared structures between C++ and shader code with support for modular PBR materials.</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="media">
      <figure>
        <img src="assets/pnkr.png" alt="pnkr GPU profiler and bistro scene" loading="lazy">
        <figcaption>GPU timeline profiler in pnkr_ng with a Bistro scene capture.</figcaption>
      </figure>
    </div>
  </div>
</section>

<section class="project" id="glider">
  <div class="project__top">
    <h2 class="project__title">Glider, the Folding Hero — Master's Thesis Project</h2>
    <div class="project__meta">Role: Programming &amp; Design | Unreal Engine 4</div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        <strong>Final Master's Project (TFM)</strong> for the Master's Degree in Video Game Development at Universidad de Málaga (2015-2016) [attached_file:1]. Collaborative game prototype developed by a three-person team ("12 brujos") [attached_file:1].
      </p>
      
      <ul class="bullets">
        <li><b>Engine:</b> Built with Unreal Engine 4, showcasing integration of gameplay systems with modern rendering features.</li>
        <li><b>Cross-Disciplinary:</b> Collaborated with Bruno Galán Adega (Art &amp; Design) and Jose Navarrete Vicente (Programming &amp; Design) [attached_file:1].</li>
        <li><b>Audio Integration:</b> Original soundtrack composed by Oliver Moya [attached_file:1].</li>
        <li><b>Academic Recognition:</b> Completed as part of the official <a href="http://mastervideojuegos.uma.es/">Máster Videojuegos UMA</a> program.</li>
      </ul>
      
      <div class="callout" id="media">
        <div class="callout__title">Project Trailer</div>
        <div class="video">
          <iframe
            src="https://www.youtube.com/embed/vMcymRMXPms"
            title="Glider, the folding hero (TFM Máster Videojuegos UMA)"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        </div>
      </div>
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
    <h2 class="project__title">Geofront — The Crossbell Arc</h2>
    <div class="project__meta">Role: Lead Programmer (Reverse Engineering &amp; Systems)</div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        Fan localization engineering project that served as the technical foundation for the <strong>official English releases by NIS America</strong>.
      </p>

      <h3>Trails from Zero / Trails to Azure</h3>
      <ul class="bullets">
        <li><b>Official Adoption:</b> Acquired and used as base for commercial PC/Switch releases</li>
        <li><b>Framerate Unlock:</b> Engine decoupling from fixed 30 fps, validated up to 144 fps</li>
        <li><b>4K Support:</b> Arbitrary resolution support with proper UI scaling matrices</li>
        <li><b>Text Engine:</b> Variable-width font system, expansion of fixed-width buffers</li>
        <li><b>HD Assets:</b> Memory-managed injection preventing OOM errors</li>
        <li><b>UI/Input:</b> Complete controller remapping, custom launcher integration</li>
        <li><b>Azure Specifics:</b> Pom Pom Party minigame localization, save transfer logic</li>
        <li><b>Stability:</b> Resource lifetime fixes, frame pacing improvements</li>
      </ul>

      <h3>Dinosaur Resurrection</h3>
      <ul class="bullets">
        <li><b>DX8 Framerate Unlock:</b> Lifted 30 fps cap to 120 fps through timing analysis</li>
        <li><b>Engine Decoupling:</b> Separated game logic from fixed timestep validation</li>
        <li><b>Physics/Animation:</b> Validated systems stability at higher refresh rates</li>
        <li><b>Input Scaling:</b> Ensured responsiveness scales correctly with framerate</li>
        <li><b>Modern Compatibility:</b> DX8 driver considerations for current GPU stacks</li>
      </ul>

      <h3>The Legend of Heroes III: White Witch</h3>
      <ul class="bullets">
        <li><b>SDL3 Mapper:</b> DirectDraw and DirectInput to SDL3 compatibility layer</li>
        <li><b>Text System:</b> Variable-width fonts, English script expansion</li>
        <li><b>Modern Systems:</b> Windows 10/11 compatibility, stability fixes</li>
        <li><b>Tooling:</b> Script extraction/reinsertion pipelines</li>
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
        <li><b>Text Engine Rewrite:</b> Complete renderer overhaul with typography support (italics, distinct fonts, word-wrapping)</li>
        <li><b>Censorship Restoration:</b> Restored 500+ censored lines and scenes through pointer re-linking and asset validation</li>
        <li><b>DLC Restoration:</b> Lingerie Conversion Patch DLC recovery via sprite flag system and menu logic rebuild</li>
        <li><b>SHORTCUT Menu:</b> Completed unfinished developer code with full implementation</li>
        <li><b>Cross-Platform:</b> Works on Steam, GOG, and Nintendo Switch (via Custom Firmware)</li>
        <li><b>Runtime Patching:</b> Changes delivered via DLL injection without engine source access</li>
        <li><b>Compatibility:</b> Practical fixes across common PC configurations and locales</li>
      </ul>
    </div>

    <div class="media">
      <figure>
        <img src="assets/coz_rne_before_after.png" alt="Robotics;Notes Elite before/after" loading="lazy">
        <figcaption>Example "before/after" text improvements (Robotics;Notes Elite).</figcaption>
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
        <li><b>Full Disassembly:</b> Complete reverse engineering of entire PC-98 binary</li>
        <li><b>Custom OMF Linker:</b> Implemented Object Module Format linker to reconstruct build chain</li>
        <li><b>Translation Pipeline:</b> Memory constraint solutions and workflows for PC-98 architecture</li>
        <li><b>x86 Segmented Mode:</b> Reverse engineered DOS game running in 16-bit real/segmented mode</li>
        <li><b>Tooling:</b> Wrote workflows to extract/insert/verify content changes in legacy binary formats</li>
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

<section class="project" id="ys8">
  <div class="project__top">
    <h2 class="project__title">Ys VIII — DirectX 11 Graphics Mod</h2>
    <div class="project__meta">Role: Reverse Engineer (Render Pipeline &amp; Shaders)</div>
  </div>

  <div class="project__grid">
    <div>
      <p class="muted">
        Production-level DirectX 11 graphics enhancement mod with real-time parameter adjustment via ImGui control panel.
      </p>

      <ul class="bullets">
        <li><b>Render Loop Hooking:</b> Intercepted renderLoop, CTexMgr::CreateTexture, C3DCommand queue</li>
        <li><b>Shadow Control Panel:</b> Custom resolution (512×512 to 16384×16384), 4-level cascade shadows, PCSS light size</li>
        <li><b>Shader Replacement:</b> Real-time custom/original shader switching, debugging overlays</li>
        <li><b>Advanced Graphics:</b> Render target management (geometry, normals, glare), custom cascade bounds, camera debugging</li>
        <li><b>SMAA Integration:</b> Subpixel Morphological AA with presets (Low-Ultra), temporal reprojection (T2x), MSAA detection</li>
        <li><b>Multi-Pass Interception:</b> SSAO, volume lighting, glare/DOF, blur effects, overlay rendering</li>
        <li><b>Thread Safety:</b> Critical section synchronization for real-time parameter modification</li>
      </ul>
      
      <div class="callout" id="media">
        <div class="callout__title">Repository</div>
        <p><a href="https://github.com/josejl1987/YsVIII">github.com/josejl1987/YsVIII</a></p>
      </div>
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
        <li><b>Reverse Engineering:</b> Working without source, Ghidra and IDA analysis, binary patching, x86 segmentation/legacy constraints.</li>
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
<footer class="site-footer">
  <span>Contact: <a href="mailto:josejl1987@gmail.com">josejl1987@gmail.com</a></span>
</footer>
