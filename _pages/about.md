---
layout: default
title: "About Me"
permalink: /
author_profile: true
---

<style>
  /* Section headings */
  .page__content h2 {
    font-size: 1.4em;
    border-bottom: 2px solid #f2f3f3;
    padding-bottom: 0.3em;
    margin-top: 1.5em;
  }
  .page__content h2 .section-icon {
    margin-right: 0.3em;
  }

  /* News list */
  .news-list {
    list-style: none;
    padding-left: 0;
  }
  .news-list li {
    padding: 0.3em 0;
    border-bottom: 1px dashed #eee;
  }
  .news-list li:last-child {
    border-bottom: none;
  }
  .news-badge {
    display: inline-block;
    background: #0076df;
    color: #fff;
    font-size: 0.8em;
    font-weight: 600;
    padding: 0.1em 0.5em;
    border-radius: 4px;
    margin-right: 0.4em;
    vertical-align: middle;
  }
  .news-badge.new {
    background: #e74c3c;
  }

  /* Education & Experience Entries */
  .edu-entry {
    display: flex;
    align-items: flex-start;
    margin-bottom: 1em;
    padding: 0.8em;
    background: #f9f9fb;
    border-radius: 8px;
    border-left: 3px solid #0076df;
  }
  
  /* Modified for Image Logos */
  .edu-entry .edu-icon {
    width: 45px;
    height: 45px;
    margin-right: 1em;
    margin-top: 0.1em;
    flex-shrink: 0;
  }
  .edu-entry .edu-icon img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }

  .edu-entry .edu-details h3 {
    margin: 0 0 0.2em 0;
    font-size: 1em;
  }
  .edu-entry .edu-details p {
    margin: 0.1em 0;
    font-size: 0.9em;
    color: #555;
  }
  .edu-entry .edu-details .edu-meta {
    font-size: 0.85em;
    color: #888;
  }

  /* Publications */
  .pub-entry {
    padding: 0.8em 0;
    border-bottom: 1px solid #f0f0f0;
  }
  .pub-entry:last-child {
    border-bottom: none;
  }
  .pub-entry .pub-title {
    font-weight: 700;
    font-size: 1em;
    color: #333;
    margin-bottom: 0.2em;
  }
  .pub-entry .pub-authors {
    font-size: 0.9em;
    color: #555;
    margin-bottom: 0.2em;
    line-height: 1.4;
  }
  
  /* Highlight the site owner's name in publications */
  .pub-authors .me {
    font-weight: 800;
    color: #0076df;
    text-decoration: underline;
  }

  .pub-entry .pub-venue {
    font-size: 0.9em;
    font-style: italic;
    color: #777;
    margin-bottom: 0.3em;
  }
  .pub-entry .pub-links a {
    display: inline-block;
    font-size: 0.8em;
    padding: 0.15em 0.6em;
    border: 1px solid #0076df;
    border-radius: 4px;
    color: #0076df;
    text-decoration: none;
    margin-right: 0.3em;
  }
  .pub-entry .pub-links a:hover {
    background: #0076df;
    color: #fff;
    text-decoration: none;
  }
  .pub-badge {
    display: inline-block;
    font-size: 0.75em;
    font-weight: 600;
    padding: 0.1em 0.5em;
    border-radius: 4px;
    margin-left: 0.4em;
    vertical-align: middle;
  }
  .pub-badge.review {
    background: #fff3cd;
    color: #856404;
  }
  .pub-badge.accepted {
    background: #d4edda;
    color: #155724;
  }
  .pub-badge.preprint {
    background: #e2e3e5;
    color: #383d41;
  }

  /* Awards */
  .awards-list {
    list-style: none;
    padding-left: 0;
  }
  .awards-list li {
    padding: 0.35em 0;
    font-size: 0.95em;
  }
  .awards-list li::before {
    content: "\f005";
    font-family: "Font Awesome 5 Free";
    font-weight: 900;
    color: #f1c40f;
    margin-right: 0.5em;
    font-size: 0.8em;
  }
  .award-year {
    font-size: 0.85em;
    color: #888;
    margin-left: 0.3em;
  }

  /* Skills */
  .skills-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8em;
    margin-top: 0.5em;
  }
  .skill-category {
    flex: 1 1 200px;
    padding: 0.8em;
    background: #f9f9fb;
    border-radius: 8px;
    border-top: 3px solid #0076df;
  }
  .skill-category h3 {
    margin: 0 0 0.4em 0;
    font-size: 0.95em;
    color: #333;
  }
  .skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.3em;
  }
  .skill-tag {
    display: inline-block;
    font-size: 0.8em;
    padding: 0.15em 0.5em;
    background: #e8f0fe;
    color: #1a73e8;
    border-radius: 4px;
  }
</style>

I am currently a Master's student at the Institute of Artificial Intelligence, College of Computer Science and Technology, **Zhejiang University**, advised by Prof. [Zhao Zhou](https://person.zju.edu.cn/zhaozhou) (赵洲). Currently I work as a research assistant at the DCD Lab. Previously, I received my B.S. degree from the **Turing Class** (an elite AI program) at Chu Kochen Honors College, Zhejiang University (浙江大学竺可桢学院图灵班).

My research interests lie at the intersection of **Spoken Dialogue Systems** and **Multimodal Large Language Models (MLLMs)**. Specifically, I am exploring how to leverage **Reinforcement Learning** to enhance the alignment, robustness, and long-term interaction capabilities of conversational agents.

**I am actively looking for academic collaboration, feel free to contact me via email at [lujingyu@zju.edu.cn](mailto:lujingyu@zju.edu.cn).**

## <span class="section-icon">📢</span> News

<ul class="news-list">
  <li><span class="news-badge">2025</span> Our paper <em>"VoxDialogue"</em> was accepted to <strong>ICLR 2025</strong>!</li>
  <li><span class="news-badge">2025</span> Preprint of <em>OmniChat</em> released on arXiv.</li>
  <li><span class="news-badge">2024</span> Survey paper <em>WavChat: A Survey of Spoken Dialogue Models</em> released on arXiv.</li>
</ul>

## <span class="section-icon">🎓</span> Education

<div class="edu-entry">
  <div class="edu-icon">
    <img src="images/Zhejiang_University_Logo.svg.png" alt="ZJU Logo" style="width: 45px; height: 45px; object-fit: contain;">
  </div>
  <div class="edu-details">
    <h3>Zhejiang University <span class="edu-meta">| 2025.09 - Present</span></h3>
    <p>M.S. in Computer Science and Technology</p>
    <p class="edu-meta">Institute of Artificial Intelligence · Advisor: Prof. Zhao Zhou</p>
  </div>
</div>

<div class="edu-entry">
  <div class="edu-icon">
    <img src="images/Zhejiang_University_Logo.svg.png" alt="ZJU Logo" style="width: 45px; height: 45px; object-fit: contain;">
  </div>
  <div class="edu-details">
    <h3>Zhejiang University <span class="edu-meta">| 2021.09 - 2025.06</span></h3>
    <p>B.S. in Artificial Intelligence (Turing Class, Chu Kochen Honors College)</p>
    <p class="edu-meta">GPA: 4.45/5.0 (Top 30%) · Outstanding Undergraduate Thesis Award</p>
  </div>
</div>

## <span class="section-icon">📝</span> Publications

<div class="pub-entry">
  <div class="pub-title">Modeling and Benchmarking Spoken Dialogue Rewards with Modality and Colloquialness <span class="pub-badge review">Under Review</span></div>
  <div class="pub-authors"><span class="me">Jingyu Lu</span>*, Yuhan Wang*, Fan Zhuo*, Xize Cheng, Changhao Pan, Xueyi Pu, Yifu Chen, Chenyuhao Wen, Tianle Liang, Zhou Zhao </div>
</div>

<div class="pub-entry">
  <div class="pub-title">VoxDialogue: Can Spoken Dialogue Systems Understand Information Beyond Words? <span class="pub-badge accepted">ICLR 2025</span></div>
  <div class="pub-authors">Xize Cheng*, Ruofan Hu*, Xiaoda Yang, <span class="me">Jingyu Lu</span>, Dongjie Fu, Zehan Wang, Shengpeng Ji, Rongjie Huang, Boyang Zhang, Tao Jin, Zhou Zhao</div>
  <div class="pub-venue">International Conference on Learning Representations (ICLR), 2025</div>
  <div class="pub-links">
    <a href="https://iclr.cc/virtual/2025/poster/27903"><i class="fas fa-file-pdf"></i> Paper</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">WavChat: A Survey of Spoken Dialogue Models <span class="pub-badge preprint">Preprint</span></div>
  <div class="pub-authors">Shengpeng Ji*, Yifu Chen*, Minghui Fang*, Jialong Zuo*, <span class="me">Jingyu Lu</span>, Hanting Wang, Ziyue Jiang, Long Zhou, Shujie Liu, Xize Cheng, Xiaoda Yang, Zehan Wang, Qian Yang, Jian Li, Yidi Jiang, Jingzhen He, Yunfei Chu, Jin Xu, Zhou Zhao</div>
  <div class="pub-venue">arXiv preprint, 2024</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2411.13577"><i class="fas fa-file-pdf"></i> Paper</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">OmniChat: Enhancing Spoken Dialogue Systems with Scalable Synthetic Data for Diverse Scenarios <span class="pub-badge preprint">Preprint</span></div>
  <div class="pub-authors">Xize Cheng*, Dongjie Fu*, Xiaoda Yang*, Minghui Fang, Ruofan Hu, <span class="me">Jingyu Lu</span>, Bai Jionghao, Zehan Wang, Shengpeng Ji, Rongjie Huang, Linjun Li, Yu Chen, Tao Jin, Zhou Zhao</div>
  <div class="pub-venue">arXiv preprint, 2025</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2501.01384"><i class="fas fa-file-pdf"></i> Paper</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">Synthetic Singers: A Review of Deep-Learning-based Singing Voice Synthesis Approaches <span class="pub-badge accepted">IJCNLP-AACL 2025</span></div>
  <div class="pub-authors">Changhao Pan*, Dongyu Yao*, Yu Zhang, Wenxiang Guo, <span class="me">Jingyu Lu</span>, Zhiyuan Zhu, Zhou Zhao</div>
  <div class="pub-venue">Proceedings of the 14th International Joint Conference on Natural Language Processing (IJCNLP-AACL), 2025</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2601.13910"><i class="fas fa-file-pdf"></i> Paper</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">Versatile Framework for Song Generation with Prompt-based Control <span class="pub-badge accepted">EMNLP Findings 2025</span></div>
  <div class="pub-authors">Yu Zhang*, Wenxiang Guo*, Changhao Pan*, Zhiyuan Zhu*, Ruiqi Li, <span class="me">Jingyu Lu</span>, Rongjie Huang, Ruiyuan Zhang, Zhiqing Hong, Ziyue Jiang, Zhou Zhao</div>
  <div class="pub-venue">Findings of the Association for Computational Linguistics: EMNLP 2025</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2504.19062"><i class="fas fa-file-pdf"></i> Paper</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">GTSinger: A Global Multi-Technique Singing Corpus with Realistic Music Scores for All Singing Tasks <span class="pub-badge accepted">NeurIPS 2024</span></div>
  <div class="pub-authors">Yu Zhang*, Changhao Pan*, Wenxiang Guo*, Ruiqi Li, Zhiyuan Zhu, Jialei Wang, Wenhao Xu, <span class="me">Jingyu Lu</span>, Zhiqing Hong, Chuxin Wang, LiChao Zhang, Jinzheng He, Ziyue Jiang, Yuxin Chen, Chen Yang, Jiecheng Zhou, Xinyu Cheng, Zhou Zhao</div>
  <div class="pub-venue">Advances in Neural Information Processing Systems (NeurIPS), 2024</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2409.13832"><i class="fas fa-file-pdf"></i> Paper</a>
  </div>
</div>

<small><i>(* indicates equal contribution)</i></small>


## <span class="section-icon">🏆</span> Awards

<ul class="awards-list">
  <li>Zhejiang Provincial Government Scholarship  (Top 5%)  <span class="award-year">(2021-2022)</span></li>
  <li>Zhejiang University First-Class Scholarship  (Top 10%)  <span class="award-year">(2022-2023, 2023-2024)</span></li>
  <li>Zhejiang University Outstanding Student <span class="award-year">(2022-2023, 2023-2024)</span></li>
  <li>Outstanding Undergraduate Thesis Award <span class="award-year">(2025)</span></li>
</ul>


## <span class="section-icon">💻</span> Research & Internships

<div class="edu-entry">
  <div class="edu-icon">
    <img src="images/Zhejiang_University_Logo.svg.png" alt="ZJU Logo" style="width: 45px; height: 45px; object-fit: contain;">
  </div>
  <div class="edu-details">
    <h3>Zhejiang University <span class="edu-meta">| 2023.09 - 2024.06</span></h3>
    <p>Research Assistant in Audio Research Team</p>
    <p class="edu-meta">Advisor: Prof. Zhou Zhao (赵洲)</p>
  </div>
</div>