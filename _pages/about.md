---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<p style="text-align: justify;">
I am a second-year PhD candidate in the Department of <a href="https://www.uclahealth.org/departments/radiology">Radiological Sciences</a> and the Department of <a href="https://samueli.ucla.edu/">Electrical and Computer Engineering</a> at <a href="https://www.ucla.edu/">UCLA</a>, where I am privileged to be co-advised by <a href="https://mrrl.ucla.edu/people/kyung-sung-phd">Prof. Kyung Sung</a> and <a href="https://samueli.ucla.edu/people/robert-candler/">Prof. Robert Candler</a>. Prior to joining UCLA, I received my Bachelor's degree in Electronic Science and Engineering from <a href="https://www.nju.edu.cn/en/">Nanjing University</a> in 2022, advised by <a href="https://ieeexplore.ieee.org/author/37676384600">Prof. Yang Li</a>. During my undergraduate studies, I was also fortunate to work with <a href="https://hrlblab.github.io/">Prof. Yuankai Huo</a> at <a href="https://vanderbilt.edu/">Vanderbilt University</a>.
</p>

<p style="text-align: justify;">
I am a member of the <a href="https://mrrl.ucla.edu/labs/sung-lab">Sung Lab</a> within <a href="https://mrrl.ucla.edu/">MRRL Labs</a>. I also engage in collaborative research with <a href="https://www.uclahealth.org/providers/wayne-brisbane">Prof. Wayne Brisbane</a>'s group. My current research focuses on data-driven medical image enhancement, generative models, and foundation models. I was an Oncology–Deep Learning Researcher Intern at <a href="https://www.bms.com/">Bristol Myers Squibb</a> during summer 2025.
</p>

<p style="text-align: justify;">
Outside of academia, I enjoy soccer, billiards, and bouldering. I am a fan of <a href="https://www.arsenal.com/">Arsenal</a> and the <a href="https://www.nba.com/heat">Miami Heat</a>. I am also a long-time player of <a href="https://www.ea.com/games/ea-sports-fc">EA Sports FC</a>.
</p>

<div class="profile-callouts">
  <p>🙌 <strong>Feel free to drop me an email if you are interested in my research projects or potential collaboration.</strong></p>
  <p>💻 <strong>I will be joining Samsung Research America (SRA) this summer as a Research Intern.</strong></p>
</div>

<p class="personal-motto">Mindfully, Compassionately, Boldly.</p>

<div class="profile-details-grid">
  <div>
    <h2>Research Interests</h2>
    <ul>
      <li>Medical Imaging</li>
      <li>Computational Imaging</li>
      <li>Foundation Models</li>
      <li>Generative Models</li>
    </ul>
  </div>
  <div>
    <h2>Education</h2>
    <ul>
      <li><strong>Ph.D., Electrical and Computer Engineering</strong><br>University of California, Los Angeles, 2024–Now</li>
      <li><strong>M.S., Electrical and Computer Engineering</strong><br>University of California, Los Angeles, 2022–2024</li>
      <li><strong>B.Eng., Electronic Science and Engineering</strong><br>Nanjing University, 2018–2022</li>
    </ul>
  </div>
</div>

<span class="anchor" id="recent-posts"></span>

# ✍️ Recent Posts

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <span class="post-date">{{ post.date | date: "%Y.%m.%d" }}</span>
    <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a>
    {% if post.summary %}<span class="post-summary">— {{ post.summary }}</span>{% endif %}
  </li>
{% endfor %}
</ul>

<span class="anchor" id="selected-publications"></span>

# 📝 Selected Publications

- <span class="venue-badge">IEEE ISBI 2026 · Oral</span> **AICM: An Anatomical-Prior Integrated Conditional Consistency Model for Self-Supervised MRI Through-Plane Super-Resolution.**<br>
  **Kaifeng Pang**, Qi Miao, Alex Ling Yu Hung, Changsuk Oh, Kai Zhao, Qiudi He, Marcel Dominik Nickel, Fei Han, Kyunghyun Sung.<br>
  [**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11515945) \| [**Code**](https://github.com/Calvin-Pang/AICM)

- <span class="venue-badge">IEEE ISBI 2026 · Oral</span> **CoDe: A Self-Supervised Consistency Model Framework for MRI Denoising.**<br>
  Junying Li, Qingyang Hou, **Kaifeng Pang**, Qi Miao, Alex Ling Yu Hung, Elif Aygun, Shu-Fu Shih, Qing Dai, Holden H. Wu, Kyunghyun Sung.<br>
  [**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11515485) \| *Co-first author and corresponding author*

- <span class="venue-badge">IEEE ISBI 2025</span> **MPR-Diff: A Self-Supervised Diffusion Model for Multi-Planar Reformation in Prostate Micro-Ultrasound Imaging.**<br>
  **Kaifeng Pang**, Qi Miao, Alex Ling Yu Hung, Kai Zhao, Eunsun Oh, Raymi Ramirez, Wayne Brisbane, Kyunghyun Sung.<br>
  [**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10981012) \| [**Code**](https://github.com/Calvin-Pang/MPR-Diff) \| [**Poster**](/uploads/isbi25-MPRDiff.pdf)

- <span class="venue-badge">Computers in Biology and Medicine · 2025</span> **NExpR: Neural Explicit Representation for Fast Arbitrary-Scale Medical Image Super-Resolution.**<br>
  **Kaifeng Pang**, Kai Zhao, Alex Ling Yu Hung, Haoxin Zheng, Ran Yan, Kyunghyun Sung.<br>
  [**Paper**](https://www.sciencedirect.com/science/article/pii/S0010482524014392) \| [**Code**](https://github.com/Calvin-Pang/NExpR)

- <span class="venue-badge">IEEE ISBI 2022 · Oral</span> **MAg: A Simple Learning-Based Patient-Level Aggregation Method for Detecting Microsatellite Instability from Whole-Slide Images.**<br>
  **Kaifeng Pang**, Zuhayr Asad, Shilin Zhao, Yuankai Huo.<br>
  [**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9761500) \| [**Code**](https://github.com/Calvin-Pang/MAg) \| [**Presentation**](https://youtu.be/Ln60y3aGthc)

Please refer to my [Google Scholar page](https://scholar.google.com/citations?user=aA28ZkcAAAAJ&hl=en) for the full list.

<span class="anchor" id="academic-service"></span>

# 🖋️ Academic Service

- **Journals:** *IEEE Transactions on Medical Imaging (TMI)*, *Scientific Reports*, *BMC Medical Imaging*, etc.
- **Conferences:** *MICCAI*, *IEEE ISBI*, and *IEEE-EMBS BHI*, etc.
