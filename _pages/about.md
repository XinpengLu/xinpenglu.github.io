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

<button id="theme-toggle" class="home-v2-floating-toggle" type="button">Dark Mode</button>

<div class="home-v2">
  <section class="home-v2-hero">
    <div class="home-v2-profile">
      <div class="home-v2-title-row">
        <h1>Xinpeng Lu (陆新蓬)</h1>
        <img src="https://xinpenglu.github.io/images/USTC.png" alt="USTC" class="home-v2-inline-avatar">
      </div>
      <p class="home-v2-tagline">M.S. Student in Computer Technology, University of Science and Technology of China</p>
      <p>
        I am currently pursuing my master's degree in Computer Technology at
        <a href="https://www.ustc.edu.cn/">University of Science and Technology of China (USTC)</a>,
        having been recommended for direct admission without the entrance exam. I am advised by
        <a href="http://staff.ustc.edu.cn/~lihq/">Prof. Houqiang Li (李厚强, IEEE Fellow, 长江学者)</a>
        and
        <a href="http://staff.ustc.edu.cn/~zhwg/index.html">Prof. Wengang Zhou (周文罡, 国家优青)</a>.
      </p>
      <p>
        I graduated with a bachelor's degree in Software Engineering from
        <a href="http://xxgcxy.yzu.edu.cn/index.htm">College of Information Engineering</a>,
        <a href="https://www.yzu.edu.cn/">Yangzhou University</a>, where I was advised by
        <a href="https://xxgcxy.yzu.edu.cn/info/1020/7295.htm">Prof. Junwu Zhu (朱俊武)</a>.
      </p>
      <p>
        My research interest includes <strong>Multi-Agent System (MAS)</strong> and
        <strong>Reinforcement Learning (RL)</strong>.
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
  </section>

  <span class='anchor' id='news'></span>
  <section class="home-v2-section">
    <h2>News</h2>
    <ul>
      <li><strong>2024.09</strong>: I entered USTC without the entrance exam.</li>
      <li><strong>2024.05</strong>: My innovation project on unmanned clusters was successfully completed.</li>
      <li><strong>2023.12</strong>: Our work MUCFC has been accepted to AAMAS 2024 as an oral paper. See you in New Zealand.</li>
    </ul>
  </section>

  <span class='anchor' id='publications'></span>
  <section class="home-v2-section">
    <h2>Publications</h2>
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
        <span class="paper-status under-review">Under Review</span>
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
        <span class="oral-status">(Oral)</span>
      </li>
    </ul>
    <p><em>* Corresponding author.</em></p>
  </section>

  <section class="home-v2-section">
    <span class='anchor' id='honors-and-awards'></span>
    <h2>Honors and Awards</h2>
    <ul>
      <li>Coming Soon.</li>
    </ul>
  </section>

  <section class="home-v2-section">
    <span class='anchor' id='educations'></span>
    <h2>Educations</h2>
    <ul>
      <li>
        <strong>2025.09 - present</strong>, Master, University of Science and Technology of China (USTC), Hefei.
        <div class="home-v2-org-logo-line"><img src="https://xinpenglu.github.io/images/USTC.png" alt="USTC logo"></div>
      </li>
      <li>
        <strong>2021.09 - 2025.06</strong>, Undergraduate, Yangzhou University, Yangzhou.
        <div class="home-v2-org-logo-line"><img src="https://logo.clearbit.com/yzu.edu.cn" alt="Yangzhou University logo"></div>
      </li>
      <li>
        <strong>2018.09 - 2021.06</strong>, Huangyan Middle School, Taizhou.
      </li>
    </ul>
  </section>

  <section class="home-v2-section">
    <span class='anchor' id='internships'></span>
    <h2>Internships</h2>
    <ul>
      <li>
        <strong>2025.03 - 2025.08</strong>, Tencent, Chengdu.
        <div class="home-v2-org-logo-line"><img src="https://logo.clearbit.com/tencent.com" alt="Tencent logo"></div>
      </li>
    </ul>
  </section>

  <div class="home-v2-globe">
    <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=NkvASYdG2r1i3NU4bU0kprSdMw-6b-hZgGBlclS77qQ"></script>
  </div>
</div>

<script>
  (function () {
    var root = document.documentElement;
    var btn = document.getElementById('theme-toggle');
    if (!btn) return;

    var key = 'site-theme';
    var saved = localStorage.getItem(key);
    if (saved === 'dark' || saved === 'light') {
      root.setAttribute('data-theme', saved);
    }

    function syncLabel() {
      btn.textContent = root.getAttribute('data-theme') === 'dark' ? 'Light Mode' : 'Dark Mode';
    }

    syncLabel();
    btn.addEventListener('click', function () {
      var next = root.getAttribute('data-theme') === 'dark' ? 'light' : 'dark';
      root.setAttribute('data-theme', next);
      localStorage.setItem(key, next);
      syncLabel();
    });
  })();
</script>
