<div align="center">
  <img src="assets/profile-banner.svg" width="100%" alt="Youngmin Seo — Machine learning research and engineering systems" />
  <p><strong>Machine Learning Research &nbsp;·&nbsp; Agent Systems &nbsp;·&nbsp; Computer Graphics</strong></p>
  <p>
    <a href="#research--publications">Research</a> &nbsp;·&nbsp;
    <a href="#agent-skills--selected-work">Agent Skills</a> &nbsp;·&nbsp;
    <a href="#systems--tooling">Systems</a> &nbsp;·&nbsp;
    <a href="#ongoing-explorations">Explorations</a>
  </p>
</div>

## About

I study machine learning models and build software systems around them. My work began with computer vision and neural-network architectures and has expanded into **agent workflows, 3D reconstruction, and tools for inspecting real outputs**.

One question connects these interests: **how can I verify that a system produced what it was intended to produce?** I try to make that question part of the workflow, from research experiments to software prototypes.

## Research & publications

<table>
  <tr>
    <td width="14%" valign="top"><strong>2026</strong><br/><sub>ACM TODAES</sub></td>
    <td valign="top">
      <strong><a href="https://doi.org/10.1145/3847672">WACA-UNet — Weakness-Aware Channel Attention for Static IR-drop Prediction</a></strong><br/>
      A computer-vision-based approach to estimating voltage-drop regions from heterogeneous chip-layout maps, with attention to underrepresented input features.<br/>
      <sub><a href="https://github.com/ictseoyoungmin/WACA-UNet">Source code</a> · <a href="https://arxiv.org/abs/2507.19197">Preprint</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>2026</strong><br/><sub>IEEE Access</sub></td>
    <td valign="top">
      <strong><a href="https://doi.org/10.1109/ACCESS.2026.3667968">Swish-T — Enhancing Swish Activation with Tanh-Based Bias</a></strong><br/>
      An activation-function family exploring how bounded tanh-based bias changes learning behavior across network architectures.<br/>
      <sub><a href="https://github.com/ictseoyoungmin/Swish-T-pytorch">PyTorch implementation</a> · <a href="https://arxiv.org/abs/2407.01012">Preprint</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>2023</strong><br/><sub>Applied Sciences</sub></td>
    <td valign="top">
      <strong><a href="https://doi.org/10.3390/app13052922">DRRU-Net — DCT-Coefficient-Learning RRU-Net for Image-Splicing Forgery Detection</a></strong><br/>
      An image-forensics model that combines learned visual features with JPEG compression artifacts in the DCT domain.<br/>
      <sub><a href="https://github.com/ictseoyoungmin/DRRU-Net">Source code</a> · <a href="https://doi.org/10.3390/app13052922">Paper</a></sub>
    </td>
  </tr>
</table>

<details>
  <summary><strong>View a research figure — Swish-T activation study</strong></summary>
  <p align="center">
    <a href="https://github.com/ictseoyoungmin/Swish-T-pytorch">
      <img src="https://raw.githubusercontent.com/ictseoyoungmin/Swish-T-pytorch/main/figs/plot_SiwshT_C.png" width="650" alt="Swish-T C activation-function plot from its source repository" />
    </a>
  </p>
</details>

## Agent Skills & selected work

I build tools that let agents construct, inspect, and revise actual artifacts — whether that's a line drawing, a 3D asset, or an interactive environment.

### img2drawing · Explicit stroke authoring

<table>
  <tr>
    <td width="118" align="center" valign="middle">
      <a href="https://github.com/ictseoyoungmin/img2drawing">
        <img src="https://raw.githubusercontent.com/ictseoyoungmin/img2drawing/main/skills/img2drawing/assets/icon.svg" width="90" alt="img2drawing official icon" />
      </a>
    </td>
    <td valign="middle">
      <strong><a href="https://github.com/ictseoyoungmin/img2drawing">img2drawing ↗</a></strong><br/>
      An agent drawing workflow based on <strong>explicit pencil strokes</strong> rather than one-shot image generation. Observation, authored strokes, rendering, and revision remain inspectable and replayable.<br/>
      <sub>Python · Stroke geometry · Rendering · Revision · Timelapse</sub><br/>
      <sub><a href="https://github.com/ictseoyoungmin/img2drawing/tree/main/showcase">Showcase and source examples</a></sub>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/ictseoyoungmin/img2drawing/tree/main/showcase/entries/croquis-sniper-girl-astra-v1">
    <img src="https://raw.githubusercontent.com/ictseoyoungmin/img2drawing/main/showcase/entries/croquis-sniper-girl-astra-v1/timelapse.gif" width="300" alt="Character pencil-stroke drawing timelapse" />
  </a><br/>
  <sub><strong>Character drawing process</strong> · Pencil-stroke timelapse</sub>
</p>

<details>
  <summary><strong>Finished character drawing</strong></summary>
  <p align="center">
    <a href="assets/drawing/featured-lineart.png">
      <img src="assets/drawing/featured-lineart.png" width="455" alt="Character line art with a long rifle" />
    </a><br/>
    <sub>Finished line drawing</sub>
  </p>
</details>

<p align="center">
  <a href="https://github.com/ictseoyoungmin/img2drawing/blob/main/docs/media/hand-line-studies.gif">
    <img src="https://raw.githubusercontent.com/ictseoyoungmin/img2drawing/main/docs/media/hand-line-studies.gif" width="360" alt="Animated pencil drawing line studies" />
  </a><br/>
  <sub>Additional pencil line studies</sub>
</p>

### RefAs · Reference Asset Foundry

<table>
  <tr>
    <td width="118" align="center" valign="middle">
      <a href="https://github.com/ictseoyoungmin/refas">
        <img src="https://raw.githubusercontent.com/ictseoyoungmin/refas/main/skills/refas/assets/icon.svg" width="90" alt="RefAs official icon" />
      </a>
    </td>
    <td valign="middle">
      <strong><a href="https://github.com/ictseoyoungmin/refas">RefAs ↗</a></strong><br/>
      Vision-first 3D reconstruction tooling for observing references, building editable geometry, reviewing GLB renders, and revising individual parts through recorded evidence.<br/>
      <sub>3D reconstruction · GLB · Multiview comparison · Evidence</sub><br/>
      <sub><a href="https://github.com/ictseoyoungmin/refas/tree/main/examples/parameter-fit">Parameter-fit fixture</a> · <a href="https://github.com/ictseoyoungmin/refas/tree/main/examples/hard-surface">Hard-surface example</a></sub>
    </td>
  </tr>
</table>

### Immersive Web Simulation Forge

<table>
  <tr>
    <td width="118" align="center" valign="middle">
      <a href="https://github.com/ictseoyoungmin/immersive-web-simulation-forge">
        <img src="https://raw.githubusercontent.com/ictseoyoungmin/immersive-web-simulation-forge/main/skills/immersive-web-simulation-forge/assets/icon.svg" width="90" alt="Simulation Forge official icon" />
      </a>
    </td>
    <td valign="middle">
      <strong><a href="https://github.com/ictseoyoungmin/immersive-web-simulation-forge">Immersive Web Simulation Forge ↗</a></strong><br/>
      Reusable tools and examples for spatial web experiences and technical simulations, with functional state, deterministic capture, and explicit inspection.<br/>
      <sub>Three.js · WebGL · Simulation · Browser QA</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/ictseoyoungmin/immersive-web-simulation-forge/tree/main/examples/0.6.0/AEROLAB_X4_Drone_Wind_Tunnel">
        <img src="https://raw.githubusercontent.com/ictseoyoungmin/immersive-web-simulation-forge/main/examples/0.6.0/AEROLAB_X4_Drone_Wind_Tunnel/preview.webp" width="100%" alt="AEROLAB X4 drone wind tunnel preview from its public repository" />
      </a><br/>
      <sub><strong>AEROLAB X4</strong> · Wind-tunnel example</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/ictseoyoungmin/immersive-web-simulation-forge/tree/main/examples/0.7.0/realistic-ocean-simulation">
        <img src="https://raw.githubusercontent.com/ictseoyoungmin/immersive-web-simulation-forge/main/examples/0.7.0/realistic-ocean-simulation/preview.png" width="100%" alt="Ocean simulation from its public repository" />
      </a><br/>
      <sub><strong>Ocean</strong> · Real-time graphics example</sub>
    </td>
  </tr>
</table>

## Systems & tooling

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ictseoyoungmin/HADARA">
        <img src="https://raw.githubusercontent.com/ictseoyoungmin/HADARA/main/docs/assets/hadara_sub_right_name.png" width="270" alt="HADARA official project wordmark" />
      </a><br/>
      <strong><a href="https://github.com/ictseoyoungmin/HADARA">HADARA · Agent development evidence ↗</a></strong>
      <p>A local-first development workflow built around task capsules, inspectable evidence, current-state recovery, and guarded handoffs.</p>
      <sub>Node.js · CLI · Agent infrastructure</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ictseoyoungmin/talarion">Talarion ↗</a></h3>
      <strong>One game. Many runtimes.</strong>
      <p>An evolving portability and QA toolchain for games built for the web and Android, with replay, state comparisons, and target-specific checks.</p>
      <sub>JavaScript · Three.js · Godot · Android QA</sub>
      
    </td>
  </tr>
</table>

## Ongoing Explorations

Additional experiments in procedural 3D authoring and spatial interfaces.

### Procedural character & hair authoring

Strand-based hair geometry, layered guides, and interactive side-by-side comparisons for developing and inspecting character appearance.

<p align="center">
  <a href="assets/experiments/hair-side-by-side-full.png">
    <img src="assets/experiments/hair-side-by-side-full.png" width="820" alt="Side-by-side character hair comparison and controls" />
  </a><br/>
  <sub><strong>Hair appearance comparison</strong></sub>
</p>

<p align="center">
  <a href="assets/experiments/hair-layer-guides-full.png">
    <img src="assets/experiments/hair-layer-guides-full.png" width="820" alt="Character hair guide layers, inspector and scene tree" />
  </a><br/>
  <sub><strong>Hair guide-layer inspection</strong></sub>
</p>

### Interactive 3D creative environments

Exploring spatial interaction, multi-view inspection, and iterative review workflows for 3D work.

<p align="center">
  <img src="assets/experiments/spatial-3d-workspace.webp" width="790" alt="Experimental browser-based 3D workspace with a mechanical bird model and multiple views" /><br/>
  <sub>Spatial 3D workspace</sub>
</p>

## Technology

<p>
  <img src="https://img.shields.io/badge/Python-243448?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-243448?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/JavaScript-243448?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-243448?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Three.js-243448?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Blender-243448?style=flat-square&logo=blender&logoColor=white" alt="Blender" />
  <img src="https://img.shields.io/badge/Git-243448?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

<sub>Computer vision · Machine learning · AI agents · 3D asset reconstruction · Rendering · Reproducible evaluation</sub>

---

<div align="center">
  <sub><strong>Build → Observe → Verify → Revise</strong></sub>
  <p><a href="https://github.com/ictseoyoungmin?tab=repositories">Explore public repositories ↗</a></p>
</div>
