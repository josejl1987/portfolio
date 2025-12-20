
# JoseJL — Game Development Engineering Portfolio

Work includes **rendering**, **systems programming**, **reverse engineering**, and **tooling**.  
A large portion of shipped output has been in projects where changes must be delivered as **runtime patches** (no source code access, strict compatibility requirements) and validated against long play sessions.

Links:
- GitHub: https://github.com/josejl1987


---

## Geofront — Trails from Zero / Trails to Azure (PC)

**Role:** lead programmer (features, fixes, integration)

Work delivered (representative):
- **UI / input systems:** controller remapping flows; integration of new actions into existing input + UI paths
- **Backlog / message log:** storing dialogue history and exposing it through a usable navigation UI
- **Save/options-related work:** reducing friction in common player workflows (configuration, menu responsiveness)
- **Frame pacing / high-FPS work:** addressing assumptions tied to a 30 FPS baseline and validating behavior at higher refresh rates
- **Stability/performance fixes:** targeted fixes where long play sessions expose resource lifetime issues

**Media**
![Controller remapping / options UI](assets/geofront_options_controller.png)  
*In-game options / controller mapping UI with added actions (e.g., Message Log) and rebinding support.*

![Dialogue presentation](assets/geofront_dialogue.png)  
*Dialogue UI sample (layout and text flow under the patched build).*



<div style="max-width: 900px;">
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe
      src="https://www.youtube.com/embed/zULIUYoSZRU"
      title="Performance optimizations"
      style="position:absolute; top:0; left:0; width:100%; height:100%;"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen>
    </iframe>
  </div>
</div>
---

## Committee of Zero — Robotics;Notes Elite / Chaos;Head Noah (PC)

**Role:** programmer / hacker (engine-side patching and supporting tooling)

Work delivered (representative):
- **Runtime patching** to support large script and asset changes safely
- **Text/UI behavior fixes** (presentation, interaction edge cases, regression handling)
- **Compatibility work** across common PC configurations
- **Iteration discipline:** build/packaging/repro workflows to keep testing and releases manageable

**Media**
![Robotics;Notes Elite — before/after example](assets/coz_rne_before_after.png)  
*Example of “before/after” text improvements in Robotics;Notes Elite.*

![Text revision — before/after example](assets/coz_text_before_after.png)  
*Example of targeted line revisions and terminology cleanup.*

---

## Brandish 2 (PC-98) — Fan Translation Engineering

**Role:** programmer (reverse engineering + translation pipeline support)

Work delivered :
- Handling **format/layout constraints** typical of PC-98-era titles (text boxes, font constraints, pointer safety)
- Tooling/workflows to **extract/insert/verify** content changes
- Conservative patching to avoid late-game regressions under tight constraints

**Media**
![Brandish 2 on PC-98 CRT](assets/brandish2_pc98.png)  
*In-game English text working on original hardware (CRT capture).*

---

## plagueng — Legacy D3D9 Engine Modernization / Rendering R&D (C++)

Repository: https://github.com/josejl1987/plagueng

Goal: modernize a legacy D3D9-era engine architecture into a codebase suitable for experimenting with modern rendering and tools.

Implemented / explored (high-level):
- **PBR pipeline** (material parameters + lighting model integration)
- **Deferred + clustered lighting path** (scaling dynamic lights; reducing per-light CPU overhead)
- **Forward rendering path** for comparisons and cases that don’t fit deferred cleanly
- **GPU-driven terrain tooling** (interactive authoring/painting workflows and GPU-side data flow)



<img src="https://docs.khosmium.com/~gitbook/image?url=https%3A%2F%2F4192102853-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FXgWn8Pw4fHYy81wa6DEA%252Fuploads%252FKrbLUNn9r5RZRAM7mzCz%252F4b700c793de829d18064304de4cd491d_original.webp%3Falt%3Dmedia%26token%3Db1391134-b7e9-456b-9584-67cd7a7eb375&width=1200&dpr=1&quality=100&sign=b6cf5187&sv=2" />

---

## Technical focus (summary)
- Rendering: PBR, forward/deferred variants, clustered lighting, GPU-driven tools
- Systems: frame pacing, UI/input integration, stability work, resource lifetime issues
- Reverse engineering: working without source, patch safety, regression avoidance
- Tooling: iteration pipelines, validation, automation for content-heavy projects

---

## Notes
This page avoids distributing copyrighted game data. Screenshots and clips are shown for demonstration.
