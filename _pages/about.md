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

<div class="home-v2">
  <section class="home-v2-hero">
    <div class="home-v2-profile">
      <h1>Xinpeng Lu</h1>
      <p class="home-v2-tagline">M.S. Student in Computer Technology, University of Science and Technology of China</p>
      <p>
        I focus on <strong>Multi-Agent Systems</strong> and <strong>Reinforcement Learning</strong>, with recent work in
        task allocation, coalition formation, and learning-based mechanism design.
      </p>
      <p class="home-v2-contact">
        Email:
        <a href="mailto:xinpenglu@mail.ustc.edu.cn">xinpenglu@mail.ustc.edu.cn</a>
        | Google Scholar:
        <a href="https://scholar.google.com/citations?user=b3N2f4kAAAAJ&hl=zh-CN">Profile</a>
      </p>
      <div class="home-v2-links">
        <a class="home-v2-btn" href="https://github.com/XinpengLu">GitHub</a>
        <a class="home-v2-btn" href="https://dblp.uni-trier.de/pid/372/0756.html">DBLP</a>
      </div>
    </div>
    <img src="https://xinpenglu.github.io/images/USTC.png" alt="Xinpeng Lu Photo" class="home-v2-avatar">
  </section>

  <section class="home-v2-section">
    <h2>News</h2>
    <ul>
      <li><strong>2024.09</strong>: Started M.S. study at USTC via recommended admission.</li>
      <li><strong>2024.05</strong>: Innovation project on unmanned clusters completed.</li>
      <li><strong>2023.12</strong>: MUCFC accepted by AAMAS 2024 as an oral paper.</li>
    </ul>
  </section>

  <section class="home-v2-section">
    <h2>Selected Publications</h2>
    <h3>Journal Papers</h3>
    <ul>
      <li>
        <span class="home-v2-venue">IEEE Access, IF=3.9</span>
        <a href="https://xinpenglu.github.io/files/journal/IEEEAccess2026.pdf">Neural Auction Mechanisms for Partial Fulfillment in Edge Computing</a>,
        Yuanyuan Zhang, <strong>Xinpeng Lu</strong>, Mingxuan Liang, Junwu Zhu*, Yonglong Zhang, Yi Jiang.
      </li>
      <li>
        <span class="home-v2-venue">Neurocomputing, IF=6.5</span>
        <a href="https://xinpenglu.github.io/files/journal/NeuroComputing2025.pdf">A Context and Preference-aware Neural Network for Auction Design</a>,
        Yuanyuan Zhang, Junwu Zhu*, Yonglong Zhang, Mingxuan Liang, Xueqing Li, <strong>Xinpeng Lu</strong>.
      </li>
      <li>
        <span class="home-v2-venue">IEEE Transactions on Consumer Electronics, IF=10.9</span>
        <a href="https://xinpenglu.github.io/files/journal/TCE2024.pdf">Research on UAVs reconnaissance task allocation method based on communication preservation</a>,
        Xueqing Li, <strong>Xinpeng Lu</strong>, Wenhao Chen, Die Ge, and Junwu Zhu*.
      </li>
    </ul>

    <h3>Conference Papers</h3>
    <ul>
      <li>
        <span class="home-v2-venue">NeurIPS 2025</span>
        <a href="https://xinpenglu.github.io/">MAE-AM: Query-driven Multi-Advertisement Embeddings and Auction Mechanism in LLM</a>,
        <strong>Xinpeng Lu</strong>, Heng Song, Yuanyuan Zhang, Xiangyu Shan, and Junwu Zhu.
        <em>(Under review)</em>
      </li>
      <li>
        <span class="home-v2-venue">ICCD 2024</span>
        <a href="https://xinpenglu.github.io/files/conference/ICCD2024.pdf">HRAM: Underwater Hierarchical Route Allocation Mechanism Based on Load Balancing</a>,
        Na Liu, Yi Jiang*, and <strong>Xinpeng Lu</strong>. (Qinzhou, China, September 28-30, 2024)
      </li>
      <li>
        <span class="home-v2-venue">WISE 2024, CCF-B</span>
        <a href="https://xinpenglu.github.io/files/conference/WISE2024.pdf">Incremental Task Replanning Algorithm for Multi-UAV Based on Centralized-Distributed Negotiation</a>,
        Peng Tian, Xiangyu Shan, <strong>Xinpeng Lu</strong>, Xueqing Li, and Junwu Zhu*. (Doha, Qatar, December 2-5, 2024)
      </li>
      <li>
        <span class="home-v2-venue">CSCWD 2024, CCF-C</span>
        <a href="https://xinpenglu.github.io/files/conference/CSCWD2024.pdf">Research on Bandwidth-Oriented Distributed Task Allocation Mechanism for Multi-UAV</a>,
        <strong>Xinpeng Lu</strong>, Heng Song*, Huailing Ma, Xueqing Li and Junwu Zhu*. (Tianjin, China, May 8-10, 2024)
      </li>
      <li>
        <span class="home-v2-venue">AAMAS 2024, CCF-B</span>
        <a href="https://xinpenglu.github.io/files/conference/AAMAS2024.pdf">A Task-Driven Multi-UAV Coalition Formation Mechanism</a>,
        <strong>Xinpeng Lu</strong>, Heng Song*, Huailing Ma, and Junwu Zhu*. (Auckland, New Zealand, May 6-10, 2024)
        <em>(Oral)</em>
      </li>
    </ul>
    <p><em>* Corresponding author.</em></p>
  </section>

  <section class="home-v2-grid">
    <div>
      <h2>Education</h2>
      <ul>
        <li><strong>2025.09 - Present</strong>, M.S., USTC, Hefei.</li>
        <li><strong>2021.09 - 2025.06</strong>, B.E., Yangzhou University, Yangzhou.</li>
        <li><strong>2018.09 - 2021.06</strong>, Huangyan Middle School, Taizhou.</li>
      </ul>
    </div>
    <div>
      <h2>Experience</h2>
      <ul>
        <li><strong>2025.03 - 2025.08</strong>, Tencent, Chengdu.</li>
      </ul>
      <h2>Honors & Awards</h2>
      <ul>
        <li>Coming soon.</li>
      </ul>
    </div>
  </section>

  <div class="home-v2-globe">
    <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=NkvASYdG2r1i3NU4bU0kprSdMw-6b-hZgGBlclS77qQ"></script>
  </div>
</div>

