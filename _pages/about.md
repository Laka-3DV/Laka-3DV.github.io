---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!-- Top hero — small avatar + name (replaces removed sidebar identity) -->
<div class="hero-row">
  <img class="hero-avatar" src="images/cola.jpg" alt="Shaocheng Yan">
  <h1 class="hero-name">Shaocheng Yan <span style="color:var(--ink-3);font-weight:400;">(颜绍程)</span></h1>
</div>


<!-- <div class="container">
        <img src="../cola_image/04-Hey.svg" alt="Hey, this is Laka!" class="foreground" />
</div> -->


<p align="center">
    <!-- <a href="https://github.com/Laka-3DV"> -->
      <!-- <img width="90%" alt="Hey, this is Laka!" src="../cola_image/04-Hey.svg" style="margin-top: -0px;" /> -->
      <img width="70%" alt="Hey, this is Laka!" src="../cola_image/07-Hey.png" style="margin-top: -0px;" />
    <!-- </a> -->
</p>

<!-- 
<p align="center">
    <a href="https://github.com/Laka-3DV">
        <img width="90%" alt="Hey, this is Laka!" src="../cola_image/06-Hey-dynamic.gif" style="margin-top: -0px;" />
    </a>
</p>
 -->


## 🧑‍💻 About Me

Hi, I'm **Shaocheng Yan** — a **Ph.D. student** at **Wuhan University** (M.S. 2023–25 → Ph.D. 2025–), supervised by Prof. [Jiayuan Li](https://ljy-rs.github.io/web/).
My research follows a single question, asked in two steps: given observations, **can we reconstruct the world?** — and now, **can we predict it?** From **3D reconstruction** to **world models**, the sensors stay the same; what changes is the ambition.

Outside the lab, you'll find me on a **bicycle** 🚴‍♂️ — chasing wind, sunrises 🌅, and sunsets 🌄, wherever the road takes me. When two wheels aren't enough, I head into the **mountains** 🏔️ for a good hike 🥾 — no deep thoughts, just legs, trails, and altitude.

Always open to collaboration — happy to chat research, side projects, or trail recommendations.

<div class="focus-tags"><strong>Focus:</strong> 3D Reconstruction · World Models · Robust Geometry · Visual Localization</div>

<div class="quick-links">
  <a class="quick-link" href="https://scholar.google.com/citations?user=2h_BHmoAAAAJ" target="_blank" rel="noopener">📖 Scholar</a>
  <a class="quick-link" href="https://github.com/Laka-3DV" target="_blank" rel="noopener">💻 GitHub</a>
  <a class="quick-link" href="mailto:shaochengyan@whu.edu.cn" title="Click to copy" onclick="event.preventDefault(); navigator.clipboard.writeText('shaochengyan@whu.edu.cn').then(()=>{const o=this.innerHTML;this.innerHTML='✓ Copied';setTimeout(()=>this.innerHTML=o,1500);});">📧 Email</a>
</div>


## 🔥 News

<!-- <ul style="list-style: disc; padding-left: 20px; line-height: 1.5; font-size: 15px;"> -->
<ul style="list-style: disc; padding-left: 30px;">
  <li>
    <strong>2026.04</strong>: 🌟 Our paper <a class="paper-link" href="#ulf-loc"><span class="pub-name">ULF-Loc</span></a> is selected as a 
    <a class="venue-label highlight" href="https://cvpr.thecvf.com/Conferences/2026" target="_blank" rel="noopener">CVPR'26 ★ Highlight</a>
    <span class="venue-label top">Top ~3%</span>
  </li>
  <li>
    <strong>2026.04</strong>: 🎉 Our paper <a class="paper-link" href="#ulf-loc"><span class="pub-name">ULF-Loc</span></a> is accepted by 
    <a class="venue-label" href="https://cvpr.thecvf.com/Conferences/2026" target="_blank" rel="noopener">CVPR'26</a>
    <span class="venue-label ccf">CCF A</span>
  </li>
  <li>
    <strong>2025.08</strong>: 🎙 Invited by <strong>
      <a href="https://space.bilibili.com/483478083" target="_blank" title="3DCVer Bilibili Space">3DCVer</a>
    </strong> to share <a class="paper-link" href="#turboreg"><span class="pub-name">TurboReg</span></a>!
    Replay on 
    <a href="https://www.bilibili.com/video/BV1mNtmzaEKP?t=17" target="_blank" title="Replay on Bilibili">
      <img src="https://img.shields.io/badge/Bilibili-FB7299?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili" height="20" style="vertical-align: text-bottom;">
    </a>
  </li>
  <li>
    <strong>2025.07</strong>: 🎙 Invited by <strong> 
      <a href="https://space.bilibili.com/45189691" target="_blank" title="3DCVer Bilibili Space">CVlife</a>
    </strong> to share <a class="paper-link" href="#turboreg"><span class="pub-name">TurboReg</span></a>!
    Replay on 
    <a href="https://www.bilibili.com/video/BV1atbSzJEdv?t=158.1" target="_blank" title="Replay on Bilibili">
      <img src="https://img.shields.io/badge/Bilibili-FB7299?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili" height="20" style="vertical-align: text-bottom;">
    </a>
  </li>
  <li>
    <strong>2025.06</strong>: 🎉 Our paper <a class="paper-link" href="#turboreg"><span class="pub-name">TurboReg</span></a> is accepted by 
    <a class="venue-label" href="https://iccv.thecvf.com/Conferences/2025" target="_blank" rel="noopener">ICCV'25</a>
    <span class="venue-label ccf">CCF A</span>
  </li>
  <li>
    <strong>2025.02</strong>: 🎉 Our paper <a class="paper-link" href="#hemora"><span class="pub-name">HeMoRa</span></a> (zh: 赫默拉) is accepted by 
    <a class="venue-label" href="https://cvpr.thecvf.com/Conferences/2025" target="_blank" rel="noopener">CVPR'25</a>
    <span class="venue-label ccf">CCF A</span>
  </li>
  <li>
    <strong>2024.07</strong>: 🎉 Our paper <a class="paper-link" href="#ml-semreg"><span class="pub-name">ML-SemReg</span></a> is accepted by 
    <a class="venue-label" href="https://eccv2024.ecva.net/Conferences/2024" target="_blank" rel="noopener">ECCV'24</a>
    <span class="venue-label ccf">CCF B</span>
  </li>
</ul>

<details style="margin-left: 20px;">
  <summary style="cursor: pointer; font-weight: bold; margin-top: 10px;">Show More</summary>
  <ul style="list-style: disc; padding-left: 11.5px;">
    <li>
      <strong>2024.07</strong>: 🎉 My homepage is created!
    </li>
  </ul>
</details>


<!-- - *2025.07*: 🎉 Invited by **CVlife** to share **TurboReg**! Replay on <a href="https://www.bilibili.com/video/BV1atbSzJEdv?t=158.1" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">Bilibili</a>.
- *2025.06*:  🎉 Our paper **TurboReg** is accepted by **<a href="https://iccv.thecvf.com/" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">ICCV 2025</a>**!
- *2025.02*:  🎉 Our paper **HeMoRa** (zh: 赫默拉) is accepted by **<a href="https://cvpr.thecvf.com/Conferences/2025" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">CVPR 2025</a>**!
- *2024.11*:  🎉 One paper is accepted by **RA-L 2024**!
- *2024.09*:  🎉 One paper is accepted by TGRS 2024</span>!
- *2024.07*:  🎉 One paper is accepted by **<a href="https://eccv2024.ecva.net/" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">ECCV 2024</a>**!
- *2024.07*:  🎉 My homepage is created!
 -->

<!-- Unified card system (shared by .pub-card / .proj-card) -->
<style>
/* Modern polish: smooth scroll + soft resting elevation on cards */
html { scroll-behavior: smooth; }

/* =========================================================
   COLOR PALETTE (Apple-inspired, restrained, ~5 colors total)
   ---------------------------------------------------------
   --accent  #00788c  teal       : paper / project names, links, default chip
   .highlight #fde68a/#78350f    : Highlight (gold-amber)
   .top       #fef3c7/#92400e    : Top % (lighter amber)
   .ccf       #f0f4f8/#475569    : CCF rank (slate-blue, lowest weight)
   .date      #f4f4f5/#52525b    : Talk dates (neutral gray)
   Bilibili   #FB7299           : platform brand pink (only on Replay badges)
   ========================================================= */
.cola-gradient { color: var(--accent); font-weight: 700; }

/* Publication card */
.pub-grid { display: flex; flex-direction: column; gap: 14px; margin: 18px 0; }
.pub-card { display: block; padding: 14px 16px; border: 1px solid #e5e7eb; border-radius: 10px; background: #fff; box-shadow: 0 1px 3px rgba(0,0,0,.03); transition: transform .15s, box-shadow .15s, border-color .15s; }
.pub-card:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,0,0,.08); border-color: #00cc99; }
.pub-body { display: flex; flex-direction: column; gap: 6px; min-width: 0; }
.pub-title { font-size: 1.05em; line-height: 1.4; }
/* Paper short-name — single teal, no gradient (Apple-style restraint) */
.pub-name { color: var(--accent); font-weight: 700; }
.venue-label { display: inline-block; font-size: .68em; letter-spacing: .08em; font-weight: 700; text-transform: uppercase; padding: 3px 10px; border-radius: 999px; background: #eef7f4; color: #00788c; }
.venue-label.highlight { background: #fde68a; color: #78350f; }
.venue-label.ccf { background: #f0f4f8; color: #475569; }
.venue-label.top { background: #fef3c7; color: #92400e; }
.venue-label.date { background: #f4f4f5; color: #52525b; }
a.venue-label { text-decoration: none !important; border-bottom: none !important; transition: filter .15s, transform .15s; }
a.venue-label:hover { filter: brightness(0.95); transform: translateY(-1px); }
.venue-row { display: flex; gap: 6px; flex-wrap: wrap; align-items: center; }

/* Quick-link chips (About Me) */
.quick-links { display: flex; gap: 8px; flex-wrap: wrap; margin: 14px 0 4px; }
a.quick-link { display: inline-block; font-size: .72em; letter-spacing: .06em; font-weight: 700; text-transform: uppercase; padding: 5px 14px; border-radius: 999px; background: #fff; color: #2c3e50 !important; border: 1px solid #e5e7eb; text-decoration: none !important; transition: background .15s, color .15s, border-color .15s, transform .15s; }
a.quick-link:hover { background: #00788c; color: #fff !important; border-color: #00788c; transform: translateY(-1px); text-decoration: none !important; }

/* Focus tags (research areas, subtle inline) */
.focus-tags { font-size: .85em; color: #666; margin: 6px 0 0; }
.focus-tags strong { color: #00788c; font-weight: 600; }

/* Talk mini-cards — 2-col grid (matches proj-card family) */
.talk-list { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin: 14px 0; }
@media (max-width: 600px) { .talk-list { grid-template-columns: 1fr; } }
.talk-item { display: flex; flex-direction: column; gap: 8px; padding: 12px 14px; border: 1px solid #e5e7eb; border-radius: 10px; background: #fff; box-shadow: 0 1px 3px rgba(0,0,0,.03); transition: transform .15s, box-shadow .15s, border-color .15s; }
.talk-item:hover { transform: translateY(-1px); box-shadow: 0 6px 18px rgba(0,0,0,.06); border-color: #00cc99; }
.talk-head { display: flex; align-items: center; justify-content: space-between; gap: 10px; }
.talk-body { font-size: .92em; color: #444; line-height: 1.5; }
.talk-body a { color: #00788c; text-decoration: none; border-bottom: 1px dotted transparent; transition: border-color .15s; }
.talk-body a:hover { border-bottom-color: #00788c; }
.talk-actions img { height: 20px; display: block; }
.pub-badges { display: flex; gap: 6px; flex-wrap: wrap; }
.pub-badges img { height: 20px; }
.pub-authors { font-size: .88em; color: #444; line-height: 1.55; }
.pub-authors a { color: inherit; text-decoration: none; border-bottom: 1px dotted transparent; transition: border-color .15s; }
.pub-authors a:hover { border-bottom-color: #00cc99; }
.pub-authors b { color: var(--accent); font-weight: 700; }
.pub-note { font-size: .78em; color: #888; font-style: italic; margin-top: -2px; }
.pub-note sup { color: var(--accent); font-style: normal; font-weight: 600; }
.pub-tldr { font-size: .9em; color: #555; line-height: 1.5; }
.pub-tldr strong { color: #00788c; }
.pub-footer { font-size: .85em; color: #888; text-align: center; margin-top: 8px; }
.pub-footer a { color: #00788c; text-decoration: none; border-bottom: 1px dotted #00788c; }
</style>

<!--
  Per-paper citation count (infra in _includes/fetch_google_scholar_stats.html):
  Find each paper's ID in google-scholar-stats/gs_data.json, then drop
    <span class='show_paper_citations' data='YOUR_PAPER_ID'></span>
  inside the pub-badges row. It auto-renders as "| Citations: N".
-->
<span class='anchor' id='-publications'></span>
## 📚 Selected Publications

<div class="pub-grid">

  <!-- ULF-Loc -->
  <span class='anchor' id='ulf-loc'></span>
  <div class="pub-card">
    <div class="pub-body">
      <div class="pub-title"><span class="pub-name">ULF-Loc:</span> Unbiased Landmark Feature for Robust Visual Localization with 3D Gaussian Splatting</div>
      <div class="venue-row">
        <span class="venue-label highlight">CVPR'26 ★ Highlight</span>
        <span class="venue-label top">Top ~3%</span>
        <span class="venue-label ccf">CCF A</span>
      </div>
      <div class="pub-badges">
        <a href="https://arxiv.org/abs/2605.04730" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/PDF-red?logo=gitbook&logoColor=white&style=flat-square" alt="PDF"></a>
        <a href="https://github.com/Cyril-gyd/ULF-Loc" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/Code-181717?logo=github&logoColor=white&style=flat-square" alt="Code"></a>
        <a href="cola_bib/0005_ulf_loc.txt" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/BibTeX-2C5DB0?logo=latex&logoColor=white&style=flat-square" alt="BibTeX"></a>
      </div>
      <div class="pub-authors">
        <a href="https://github.com/Cyril-gyd" target="_blank" rel="noopener">Yingdong Gu</a><sup>*</sup>,
        <b>Shaocheng Yan</b><sup>*</sup>,
        <a href="https://ericzzj1989.github.io/" target="_blank" rel="noopener">Zhenjun Zhao</a>,
        Yuan Kou, Jianxin Luo,
        <a href="https://orcid.org/0000-0003-2504-9890" target="_blank" rel="noopener">Pengcheng Shi</a>,
        <a href="https://ljy-rs.github.io/web/" target="_blank" rel="noopener">Jiayuan Li</a>
      </div>
      <div class="pub-note"><sup>*</sup> Equal contribution (co-first authors)</div>
      <div class="pub-tldr"><strong>TL;DR:</strong> Unbiased landmark features via keypoint-consensus sampling and geometry-weighted feature fusion, fundamentally solving alpha-blending bias for highly accurate and ultra-efficient visual localization with 3D Gaussian Splatting.</div>
    </div>
  </div>

  <!-- TurboReg -->
  <span class='anchor' id='turboreg'></span>
  <div class="pub-card">
    <div class="pub-body">
      <div class="pub-title"><span class="pub-name">TurboReg:</span> TurboClique for Robust and Efficient Point Cloud Registration</div>
      <div class="venue-row">
        <span class="venue-label">ICCV'25</span>
        <span class="venue-label ccf">CCF A</span>
      </div>
      <div class="pub-badges">
        <a href="https://arxiv.org/pdf/2507.01439" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/PDF-red?logo=gitbook&logoColor=white&style=flat-square" alt="PDF"></a>
        <a href="https://github.com/Laka-3DV/TurboReg" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/Code-181717?logo=github&logoColor=white&style=flat-square" alt="Code"></a>
        <a href="cola_bib/0004_turboreg.txt" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/BibTeX-2C5DB0?logo=latex&logoColor=white&style=flat-square" alt="BibTeX"></a>
        <a href="https://www.bilibili.com/video/BV1atbSzJEdv?t=158.1" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/CVlife-FB7299?logo=bilibili&logoColor=white&style=flat-square" alt="CVlife"></a>
        <a href="https://www.bilibili.com/video/BV1mNtmzaEKP?t=17" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/3DCVer-FB7299?logo=bilibili&logoColor=white&style=flat-square" alt="3DCVer"></a>
      </div>
      <div class="pub-authors">
        <b>Shaocheng Yan</b>,
        <a href="https://orcid.org/0000-0003-2504-9890" target="_blank" rel="noopener">Pengcheng Shi</a>,
        <a href="https://ericzzj1989.github.io/" target="_blank" rel="noopener">Zhenjun Zhao</a>,
        Kaixin Wang, Kuang Cao, Ji Wu,
        <a href="https://ljy-rs.github.io/web/" target="_blank" rel="noopener">Jiayuan Li</a>
      </div>
      <div class="pub-tldr"><strong>TL;DR:</strong> A highly efficient and robust estimator for point cloud registration (PCR), supporting both CPU and GPU platforms.</div>
    </div>
  </div>

  <!-- HeMoRa -->
  <span class='anchor' id='hemora'></span>
  <div class="pub-card">
    <div class="pub-body">
      <div class="pub-title"><span class="pub-name">HeMoRa:</span> Unsupervised Heuristic Consensus Sampling for Robust Point Cloud Registration</div>
      <div class="venue-row">
        <span class="venue-label">CVPR'25</span>
        <span class="venue-label ccf">CCF A</span>
      </div>
      <div class="pub-badges">
        <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Yan_HeMoRa_Unsupervised_Heuristic_Consensus_Sampling_for_Robust_Point_Cloud_Registration_CVPR_2025_paper.html" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/PDF-red?logo=gitbook&logoColor=white&style=flat-square" alt="PDF"></a>
        <a href="https://github.com/Laka-3DV/HeMoRa" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/Code-181717?logo=github&logoColor=white&style=flat-square" alt="Code"></a>
        <a href="./cola_bib/0003_hemora.txt" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/BibTeX-2C5DB0?logo=latex&logoColor=white&style=flat-square" alt="BibTeX"></a>
      </div>
      <div class="pub-authors">
        <b>Shaocheng Yan</b>,
        <a href="https://yimingwangmingle.github.io/bio/" target="_blank" rel="noopener">Yiming Wang</a>,
        <a href="https://kaiyanzhaophoenix.github.io/bio/" target="_blank" rel="noopener">Kaiyan Zhao</a>,
        <a href="https://orcid.org/0000-0003-2504-9890" target="_blank" rel="noopener">Pengcheng Shi</a>,
        <a href="https://ericzzj1989.github.io/" target="_blank" rel="noopener">Zhenjun Zhao</a>,
        <a href="https://skyearth.org/zhangyj/" target="_blank" rel="noopener">Yongjun Zhang</a>,
        <a href="https://ljy-rs.github.io/web/" target="_blank" rel="noopener">Jiayuan Li</a>
      </div>
      <div class="pub-tldr"><strong>TL;DR:</strong> Learning a sampling probability distribution for matches in robust estimation — no supervision, reinforcement-inspired.</div>
    </div>
  </div>

  <!-- ML-SemReg -->
  <span class='anchor' id='ml-semreg'></span>
  <div class="pub-card">
    <div class="pub-body">
      <div class="pub-title"><span class="pub-name">ML-SemReg:</span> Boosting Point Cloud Registration with Multi-level Semantic Consistency</div>
      <div class="venue-row">
        <span class="venue-label">ECCV'24</span>
        <span class="venue-label ccf">CCF B</span>
      </div>
      <div class="pub-badges">
        <a href="https://arxiv.org/pdf/2407.09862" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/PDF-red?logo=gitbook&logoColor=white&style=flat-square" alt="PDF"></a>
        <a href="https://github.com/Laka-3DV/ML-SemReg" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/Code-181717?logo=github&logoColor=white&style=flat-square" alt="Code"></a>
        <a href="./cola_bib/0002_ml_semreg.txt" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/BibTeX-2C5DB0?logo=latex&logoColor=white&style=flat-square" alt="BibTeX"></a>
      </div>
      <div class="pub-authors">
        <b>Shaocheng Yan</b>,
        <a href="https://orcid.org/0000-0003-2504-9890" target="_blank" rel="noopener">Pengcheng Shi</a>,
        <a href="https://ljy-rs.github.io/web/" target="_blank" rel="noopener">Jiayuan Li</a>
      </div>
      <div class="pub-tldr"><strong>TL;DR:</strong> Boosting 3D keypoint match recall using semantic labels — no learning needed, SLAM-ready.</div>
    </div>
  </div>

</div>

<div class="pub-footer">For the full list of publications (including co-authored work), see <a href="https://scholar.google.com/citations?user=2h_BHmoAAAAJ" target="_blank" rel="noopener">Google Scholar →</a></div>


<span class='anchor' id='-selected-projects'></span>
## 💻 Selected Projects

<style>
.proj-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; margin: 16px 0; }
@media (max-width: 600px) { .proj-grid { grid-template-columns: 1fr; } }
.proj-card { display: block; padding: 14px 16px; border: 1px solid #e5e7eb; border-radius: 10px; color: inherit; background: #fff; box-shadow: 0 1px 3px rgba(0,0,0,.03); transition: transform .15s, box-shadow .15s, border-color .15s; }
.proj-card:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,0,0,.08); border-color: #00cc99; }
.proj-body { display: flex; flex-direction: column; gap: 6px; min-width: 0; }
.proj-head { display: flex; align-items: center; justify-content: space-between; gap: 12px; min-width: 0; }
/* Project name — same teal as paper-name, for cross-section consistency */
.proj-title { display: inline-block; font-weight: 700; font-size: 1.05em; color: var(--accent); text-decoration: none !important; border-bottom: none !important; transition: opacity .15s; }
.proj-title:hover { opacity: 0.78; text-decoration: none !important; }
.proj-head .github-button { flex-shrink: 0; }
.proj-desc { font-size: .85em; color: #555; line-height: 1.4; }
</style>

<div class="proj-grid">
  <div class="proj-card">
    <div class="proj-body">
      <div class="proj-head">
        <a class="proj-title" href="https://github.com/Laka-3DV/TurboReg" target="_blank" rel="noopener">TurboReg</a>
        <a class="github-button" href="https://github.com/Laka-3DV/TurboReg" data-icon="octicon-star" data-show-count="true" aria-label="Star Laka-3DV/TurboReg on GitHub">Star</a>
      </div>
      <div><span class="venue-label">ICCV'25</span></div>
      <div class="proj-desc">TurboClique-based robust & efficient point cloud registration (CPU/GPU).</div>
    </div>
  </div>
  <div class="proj-card">
    <div class="proj-body">
      <div class="proj-head">
        <a class="proj-title" href="https://github.com/Cyril-gyd/ULF-Loc" target="_blank" rel="noopener">ULF-Loc</a>
        <a class="github-button" href="https://github.com/Cyril-gyd/ULF-Loc" data-icon="octicon-star" data-show-count="true" aria-label="Star Cyril-gyd/ULF-Loc on GitHub">Star</a>
      </div>
      <div><span class="venue-label highlight">CVPR'26 ★ Highlight</span></div>
      <div class="proj-desc">Unbiased landmark features for visual localization with 3D Gaussian Splatting.</div>
    </div>
  </div>
  <div class="proj-card">
    <div class="proj-body">
      <div class="proj-head">
        <a class="proj-title" href="https://github.com/Laka-3DV/ML-SemReg" target="_blank" rel="noopener">ML-SemReg</a>
        <a class="github-button" href="https://github.com/Laka-3DV/ML-SemReg" data-icon="octicon-star" data-show-count="true" aria-label="Star Laka-3DV/ML-SemReg on GitHub">Star</a>
      </div>
      <div><span class="venue-label">ECCV'24</span></div>
      <div class="proj-desc">Multi-level semantic consistency for boosting registration recall.</div>
    </div>
  </div>
</div>


 




<span class='anchor' id='-invited-talks'></span>
## 🎙 Invited Talks & Sharing

<div class="talk-list">
  <div class="talk-item">
    <div class="talk-head">
      <span class="venue-label date">2025.08</span>
      <a href="https://www.bilibili.com/video/BV1mNtmzaEKP?t=17" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/Replay-FB7299?logo=bilibili&logoColor=white&style=flat-square" alt="Replay"></a>
    </div>
    <div class="talk-body">
      Invited talk on <a class="paper-link" href="#turboreg"><span class="pub-name">TurboReg</span></a> @ <a href="https://space.bilibili.com/483478083" target="_blank" rel="noopener">3DCVer</a>
    </div>
  </div>
  <div class="talk-item">
    <div class="talk-head">
      <span class="venue-label date">2025.07</span>
      <a href="https://www.bilibili.com/video/BV1atbSzJEdv?t=158.1" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/Replay-FB7299?logo=bilibili&logoColor=white&style=flat-square" alt="Replay"></a>
    </div>
    <div class="talk-body">
      Invited talk on <a class="paper-link" href="#turboreg"><span class="pub-name">TurboReg</span></a> @ <a href="https://space.bilibili.com/45189691" target="_blank" rel="noopener">CVlife</a>
    </div>
  </div>
</div>


## 🏆 Honors and Awards

- *2025.04*, **Outstanding Graduate**, Class of 2025  
- *2024.11*, **National Second Prize**, China Graduate Mathematical Modeling Contest
- *2022.08*, **National First Prize (Champion)**, China University Robotics Innovation Competition  
- *2020.12*, **First Prize**, 11th National College Student Mathematics Competition (Non-Math Major Category)


## 🎓 Educations
- *2025.09 - Present*, Ph.D. in Photogrammetry and Remote Sensing, School of Remote Sensing and Information Engineering, Wuhan University
- *2023.09 - 2025.06*, M.S. in Geomatics Engineering, School of Remote Sensing and Information Engineering, Wuhan University
- *2019.09 - 2023.06*, B.S. in Electronic and Information Engineering, School of Electrical Engineering, Southwest Jiaotong University