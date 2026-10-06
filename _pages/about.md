---
permalink: /
title: ""
excerpt: ""
author_profile: false
editorial: true
redirect_from:
  - /about/
  - /about.html
---

<section class="hero" id="about-me" aria-labelledby="intro-name">
  <div>
    <p class="eyebrow">Sustainable computing · Purdue University</p>
    <h1 id="intro-name">Tianyao Shi <span class="name-zh" lang="zh">史天尧</span></h1>
    <p class="hero-statement">I study the environmental impact of computing—from energy and carbon to biodiversity.</p>
    <p class="hero-bio">I am a PhD student at Purdue University, where I joined Prof. <a href="https://y-ding.github.io/">Yi Ding</a>'s STYLE group in August 2024. My research focuses on sustainable computing systems and LLM serving.</p>
    <div class="contact-links" aria-label="Contact and profiles">
      <a class="primary-link" href="{{ '/pdf/Resume_TianyaoShi_2602.pdf' | relative_url }}">Curriculum vitae <span aria-hidden="true">&nbsp;↗</span></a>
      <a href="{{ site.author.googlescholar }}">Scholar</a>
      <a href="mailto:{{ site.author.email }}">Email</a>
      <a href="https://github.com/{{ site.author.github }}">GitHub</a>
    </div>
  </div>
  <figure class="portrait">
    <img src="{{ site.author.avatar | relative_url }}" alt="Tianyao Shi" width="210" height="210" fetchpriority="high">
    <figcaption>West Lafayette, Indiana</figcaption>
  </figure>
</section>

<h2 id="research">Selected research</h2>

I connect life-cycle assessment and ecological modeling with computer architecture and systems research to quantify computing's broader environmental impact, including biodiversity loss. My work explores energy- and carbon-efficient data center operation and LLM serving.

{% include research-highlights.html %}

<h2 id="news"><span class="anchor" id="-news" aria-hidden="true"></span>Recent news</h2>

<ul class="news-list">
  <li><time datetime="2026-10">Oct 2026</time><p><em>An Interference-Aware QoS Violation Alleviation Framework for Multi-Tenancy Public Clouds</em> accepted to IEEE Transactions on Parallel and Distributed Systems (TPDS).</p></li>
  <li><time datetime="2026-08">Aug 2026</time><p><em>BIRDS: Characterizing and Understanding Biodiversity Impact of Large Language Model Serving</em> accepted to EMNLP 2026 Findings.</p></li>
  <li><time datetime="2025-06">Jun 2025</time><p><em>When Servers Meet Species: A Fab-to-Grave Lens on Computing's Biodiversity Impact</em> accepted to HotCarbon 2025.</p></li>
</ul>
<details>
  <summary>Earlier updates</summary>
  <ul class="news-list">
    <li><time datetime="2025-03">Mar 2025</time><p>Certified as a teaching assistant at Purdue after passing the OEPT with a score of 50/55.</p></li>
    <li><time datetime="2025-03">Mar 2025</time><p>Received an $800 Research Award from Purdue's Institute for a Sustainable Future (ISF).</p></li>
  </ul>
</details>
<h2 id="preprints"><span class="anchor" id="-preprints" aria-hidden="true"></span>Preprints</h2>

<div class="pub-list">
  <div class="pub-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2609.35569">Beyond Energy: When Sustainability Dimensions Reshape LLM Serving Decisions</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">ArXiv 2026</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi</strong>, Xipeng Shen, Yi Ding</span>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://www.techrxiv.org/users/1024518/articles/1384487-sustainability-of-computing-systems-a-survey-from-environmental-impact-perspectives">Sustainability of Computing Systems: A Survey from Environmental Impact Perspectives</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">TechRxiv 2026</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi</strong>, Yanran Wu, Inez Hua, Yi Ding</span>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://arxiv.org/pdf/2508.16712">Systematic Characterization of LLM Quantization: A Performance, Energy, and Quality Perspective</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">ArXiv 2025</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi</strong>, Yi Ding</span>
    </div>
  </div>
</div>

<h2 id="publications"><span class="anchor" id="-publications" aria-hidden="true"></span>Publications</h2>

<div class="pub-list">
  <div class="pub-item">
    <div class="pub-title">
       <a href="https://www.computer.org/csdl/journal/td/5555/01/11719242/2kfWz1DwwuI">An Interference-Aware QoS Violation Alleviation Framework for Multi-Tenancy Public Clouds</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">TPDS</span>
      <span class="pub-track-badge">Accepted</span>
      <span class="pub-authors-journal">Yunlong Cheng, Hongji Dong, <strong>Tianyao Shi</strong>, Xiaofeng Gao, Guihai Chen. IEEE Transactions on Parallel and Distributed Systems.</span>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2605.27480">BIRDS: Characterizing and Understanding Biodiversity Impact of Large Language Model Serving</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">EMNLP 2026</span>
      <span class="pub-track-badge">Findings</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi</strong>, Yi Ding</span>
    </div>
    <div class="resource-links">
      <a href="https://tianyaoshi.github.io/BIRDS/">Project <span aria-hidden="true">↗</span></a>
      <a href="https://github.com/TianyaoShi/BIRDS">Code <span aria-hidden="true">↗</span></a>
      <a href="https://gist.science/paper/2605.27480#gist">Summary <span aria-hidden="true">↗</span></a>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://ieeexplore.ieee.org/abstract/document/11230830/">Disaggregated Speculative Decoding for Carbon-Efficient LLM Serving</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">CAL 2025</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi*</strong>, Yanran Wu*, Sihang Liu, Yi Ding, IEEE Computer Architecture Letters 24 (2), 369-372.</span>
    </div>
    <div class="resource-links">
      <a href="https://arxiv.org/pdf/2412.20322">Full-length preprint <span aria-hidden="true">↗</span></a>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://arxiv.org/abs/2506.20442">When Servers Meet Species: A Fab-to-Grave Lens on Computing's Biodiversity Impact</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">HotCarbon 2025</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi</strong>, Ritbik Kumar, Inez Hua, Yi Ding, ACM SIGEnergy Energy Informatics Review (EIR), Volume 5 Issue 2, pp. 34-40.</span>
    </div>
    <div class="resource-links">
      <a href="https://github.com/TianyaoShi/FABRIC">Code <span aria-hidden="true">↗</span></a>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://ieeexplore.ieee.org/abstract/document/10765824">Sustainable LLM Serving: Environmental Implications, Challenges, and Opportunities</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">IGSC 2024</span>
      <span class="pub-authors-journal">Yi Ding, <strong>Tianyao Shi</strong>, pp. 37-38.</span>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://arxiv.org/pdf/2307.08949.pdf">Alioth: A Machine Learning Based Interference-Aware Performance Monitor for Multi-Tenancy Applications in Public Cloud</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">IPDPS 2023</span>
      <span class="pub-authors-journal"><strong>Tianyao Shi</strong>, Yingxuan Yang, Yunlong Cheng, Xiaofeng Gao, Zhen Fang, Yongqiang Yang, pp. 908-917.</span>
    </div>
    <div class="resource-links">
      <a href="https://github.com/StHowling/Alioth">Code <span aria-hidden="true">↗</span></a>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://dl.acm.org/doi/abs/10.1145/3404835.3462831">FORM: Following the Online Regularized Meta-Leader for Cold-Start Recommendation</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">SIGIR 2021</span>
      <span class="pub-authors-journal">Xuehan Sun, <strong>Tianyao Shi</strong>, Xiaofeng Gao, Yanrong Kang, Guihai Chen, pp. 1177-1186.</span>
    </div>
  </div>

  <div class="pub-item">
    <div class="pub-title">
      <a href="https://link.springer.com/chapter/10.1007/978-3-030-73200-4_23">GCAN: A Group-Wise Collaborative Adversarial Networks for Item Recommendation</a>
    </div>
    <div class="pub-info">
      <span class="pub-venue-badge">DASFAA 2021</span>
      <span class="pub-authors-journal">Xuehan Sun, <strong>Tianyao Shi</strong>, Xiaofeng Gao, Xiang Li, Guihai Chen, pp. 330-338.</span>
    </div>
  </div>
</div>

<h2 id="education">Education</h2>

- **Purdue University** · PhD student, August 2024–present
- **Shanghai Jiao Tong University** · Master's degree in Electronic and Information Engineering, March 2024
- **Shanghai Jiao Tong University** · Bachelor's degree in Computer Science, June 2021

<h2 id="honors"><span class="anchor" id="-honors-and-awards" aria-hidden="true"></span>Honors &amp; awards</h2>

- *2025.03* &nbsp; ISF Research Award of Purdue
- *2023.11* &nbsp; Excellent Graduate Scholarship of SJTU
- *2021 ~ 2023* &nbsp; First-Class Graduate Grant of SJTU
- *2021.06* &nbsp; Outstanding Graduate of SJTU [[Certificate]](../images/Q20230417161501.jpg)
- *2021.06* &nbsp; Excellent Bachelor's Thesis of SJTU
- *2020.10* &nbsp; No. 95 of LeetCode Cup Team Coding Contest (LCCUP’2020) (top 3.6% of 2575 teams) [[Result Screenshot]](../images/Q20230417161021.jpg)
- *2018.05* &nbsp; Meritorious Winner of Mathematical Contest In Modeling (MCM) (top 9.7% of 26062 teams) [[Certificate]](../pdf/73043.pdf)

<h2 id="experience"><span class="anchor" id="-work-experience" aria-hidden="true"></span>Experience</h2>

- *2026.01 - 2026.05*, Teaching Assistant of **ECE20875: Python for Data Science** at Purdue University
- *2022.03 – 2022.09*, Teaching Assistant of [**Introduction to Computer Science (“Xuesen Challenge Program”)**](https://news.sjtu.edu.cn/mtjj/20220306/167909.html) at SJTU
- *2020.09 - 2020.12*, Teaching Assistant of [**Algorithm Design and Analysis (CS7310)**](http://anl.sjtu.edu.cn/gao-xf/resources/projectDesc/CS7310-2020/Project-Data-AnalyticJobScheduling.pdf/hehe) at SJTU
- *2019.09 - 2021.01*, Managing Assistant of Office of Instructional Operations Management in SJTU Academic Affairs Office

<h2 id="service"><span class="anchor" id="-academic-services" aria-hidden="true"></span>Academic service</h2>

- Reviewer of IEEE TPAMI, IEEE TII, ACM TOMPECS
- External Reviewer of IEEE TNSE, IEEE TNSM, AAAI 2022, ICDM 2023

<h2 id="beyond-research"><span class="anchor" id="-hobbies" aria-hidden="true"></span>Beyond research</h2>

I have always been a soccer fan, as a life-long supporter of Taishan FC and a supporter of FC Barcelona since 2011. I was a referee of SJTU Football Association during my undergraduate years and Vice Chairman of SJTUFA during 2019-2020. (See this [certificate of appointment](../images/IMG_20231119_222610.jpg) and [report](https://mp.weixin.qq.com/s/3d9hQbrdfmXSLzk2y8Y_2w) in Chinese)

<footer class="site-footer">
  <span>Tianyao Shi · Purdue University</span>
  <div class="footer-links" aria-label="Additional profiles">
    <a href="{{ site.author.dblp }}">DBLP</a>
    <a href="{{ site.author.orcid }}">ORCID</a>
    <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
    <a href="#about-me">Back to top ↑</a>
  </div>
</footer>
