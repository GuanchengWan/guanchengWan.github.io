---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-bottom: 60px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  /* 全局文本颜色 */
  body {
    color: #333; /* 主要文本颜色 */
  }

  /* 链接颜色 */
  a {
    color: #0066cc; /* 链接颜色 */
  }

  /* 作者名字颜色 */
  strong {
    color: #000; /* 作者名字颜色 */
  }

  /* 年份标题颜色 */
  .year-title {
    color: #666;
  }

  /* 会议标签样式 */
  .conference-label {
    position: absolute;
    top: 10px;
    left: -5px;
    background-color: #2c3e50;  /* 深蓝色背景 */
    color: white;  /* 白色文字 */
    padding: 6px 12px;
    border-radius: 6px;
    font-size: 0.95em;
    font-weight: 600;
    letter-spacing: 0.5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    z-index: 1;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    font-style: italic;  /* 添加斜体 */
  }

  /* 鼠标悬停效果 */
  .conference-label:hover {
    background-color: #34495e;  /* 悬停时稍微变亮 */
    transition: background-color 0.2s ease;
  }

  dl dt img {
    width: 400px; /* 设定统一宽度 */
    height: 200px; /* 设定统一高度 */
    object-fit: cover; /* 确保图片不会被裁剪 */
    display: block;
    margin: 10px 10px 10px 0px; /* 适当的间距 */
    
    /* 添加美化效果 */
    border-radius: 8px; /* 让图片有轻微的圆角 */
    border: 2px solid #ddd; /* 添加淡灰色的边框 */
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2); /* 添加轻微阴影 */
    padding: 5px; /* 给图片一些内边距，让它不贴着边框 */
    background-color: #fff; /* 设置背景色，让图片更加干净 */
  }

  dl dt {
    position: relative;
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }

  dl dd {
  margin-top: 5px; 
  margin-bottom: 5px;
}

  dl dd strong {
  font-weight: bold;
  color: black;
  }

  .co-first {
    color: red;
  }

  .down {
    transform: rotate(180deg);
  }

</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


My name is Guancheng Wan (万冠呈) <span class="pronunciation" style="cursor: pointer;" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'; this.querySelector('.toggle-symbol').textContent = this.nextElementSibling.style.display === 'block' ? '▼' : '►';"><span class="toggle-symbol" style="margin-right: 5px;">►</span><span style="color: gray;">How to pronounce?</span></span>
<span style="display: none;">My name is pronounced as "Gwan-chung Wan". The "Gwan" rhymes with "man", and "chung" sounds like "chung" in "chunk".</span>, an incoming CS PhD student (25 Fall) at University of California, Los Angeles ([UCLA](https://www.ucla.edu/)), supervised by [Wei Wang](https://scholar.google.com/citations?user=UedS9LQAAAAJ) and [Yizhou Sun](https://scholar.google.com/citations?user=TQgOjK0AAAAJ). I obtained B.S. degree at [Wuhan University](https://www.whu.edu.cn/), working closely with [Mang Ye](https://scholar.google.com/citations?user=j-HxRy0AAAAJ&hl=zh-CN), [Bo Du](https://scholar.google.com/citations?user=Shy1gnMAAAAJ&hl=en) and [Wenke Huang](https://scholar.google.com/citations?hl=zh-CN&user=aFoCI3MAAAAJ). 

I am open to research collaborations and internships, with a great record of cooperating and mentoring. 🥳 Feel free to contact me via <a href="mailto:gcwan03@ucla.edu">Email</a> or <a href="https://guanchengwan.github.io/images/wechat.png">WeChat</a>.


<!-- Previously, I spent a wonderful summer at Emory University, supervised by [Wei Jin](https://scholar.google.com/citations?user=eWow24EAAAAJ&hl=en&oi=ao), [Carl Yang](https://scholar.google.com/citations?user=mOINlwcAAAAJ&hl=en&oi=ao) 
and collaborated with [B. Aditya Prakash](https://scholar.google.com/citations?user=C-NftTgAAAAJ). -->

<div style="text-align: left; margin: 20px 0;">
  <img src="../images/sign.png" alt="Signature" style="max-width: 150px; height: auto;">
</div>





# 🔎 Research 
<!-- "All things are interconnected, this is the essence of nature."  -->

<dt style="text-align: center; margin: 0; padding: 0;">
  <img src="../images/research.png" style="display: block; max-width: 700px; width: 100%; height: auto; margin: 0 auto;">
</dt>

I am passionate about modeling the relationships among all points (*e.g.*, nodes, tokens, or agents). My current research interests focus on three key areas:

a) (Multimodal) Large Language Models (MLLM), Large Reasoning Models, LLM-based Multi-Agent System

b) AI for Science: Biotechnology, Physics and Chemistry...

c) Trustworthy AI:  Federated (Graph) Learning, MLLM Safety and Hallucination 


<div style="background-color: #f8f9fa; padding: 20px; border-radius: 10px; margin: 20px 0; border: 1px solid #e9ecef;">
  <p style="margin: 0; "> <strong style="color: red">🌟 📢 Hiring:  Remote Research Intern</strong><br>
We are looking for motivated research interns to work together! Almost every intern who worked with me has published papers at top conferences such as ICML, NeurIPS, ICLR and CVPR.
    If you are interested, please don't hesitate to contact me via <a href="mailto:gcwan03@ucla.edu">Email</a> or <a 
href="https://guanchengwan.github.io/images/wechat.png">WeChat</a>.
  </p>
</div>


# 🔥 News

<div style="max-height: 350px; overflow-y: auto; padding: 20px; background: #f8f9fa; border-left: 4px solid #2c3e50; margin: 0px 0;">
<style>
  /* 为 Webkit 浏览器（Chrome, Safari, Edge）设置滚动条样式 */
  div::-webkit-scrollbar {
    width: 8px;
  }

  div::-webkit-scrollbar-track {
    background: #e9ecef;
    border-radius: 4px;
  }

  div::-webkit-scrollbar-thumb {
    background: #2c3e50;
    border-radius: 4px;
  }

  div::-webkit-scrollbar-thumb:hover {
    background: #1a252f;
  }

  /* 为 Firefox 设置滚动条样式 */
  div {
    scrollbar-width: thin;
    scrollbar-color: #2c3e50 #e9ecef;
  }
</style>
<ul style="list-style-type: none; padding-left: 0; margin: 0;">
  <li><em>2025.05:</em> 🎉 Two papers were accepted by <strong>ACL 2025 Main</strong>. Thanks to all collaborators!</li>
  <li><em>2025.05:</em> 🎉 Some papers were accepted by <strong>ICML 2025</strong> with <strong class="co-first"> Two Spotlights (Top 2.6%)</strong>. See you in Vancouver!</li>
  <li><em>2025.04:</em> 🎉 One co-first authored paper: LoRASculpt (MLLM visual instruction tuning) was selected as an <strong class="co-first">Oral Presentation (Top 3.3%)</strong> at <strong>CVPR 2025</strong>. Thanks to all collaborators!</li>
    <li><em>2025.03:</em> 🎉 One co-first authored paper: FedTGE was selected as an <strong class="co-first">Oral Presentation (Top 1.8%)</strong> at <strong>ICLR 2025</strong>. Thanks to all collaborators!</li>
  <li><em>2025.02:</em> 🎉 Three papers accepted by <strong>CVPR 2025</strong> on fine-tuning and applications of <strong>Multimodal Large Language Models (MLLM)</strong>. Thanks to all collaborators! See you in Nashville.</li>
  <li><em>2024.02:</em> I serve as a reviewer for <strong>NeurIPS 2025</strong>.</li>
  <li><em>2025.01:</em> 🎉 Two papers were accepted by <strong>ICLR 2025</strong>. See you in Singapore.</li>
  <li><em>2024.12:</em> 🎉 One paper was accepted by <strong>AAAI 2025</strong>.</li>
  <li><em>2024.12:</em> I serve as a reviewer for <strong>ICML 2025</strong>.</li>
  <li><em>2024.11:</em> 🎈I was honored with <strong>Lei Jun Excellence Scholarship</strong> ~ <strong>100k</strong> (The <strong><u>Highest</u></strong> Scholarship at Wuhan University, <strong><u>Top-4</u></strong> among All Undergraduates, Award Rate ~ <strong>0.01%</strong>)</li>
  <li><em>2024.11:</em> I serve as a reviewer for <strong>CVPR 2025</strong>.</li>
  <li><em>2024.09:</em> 🎉 Two papers were accepted by <strong>NeurIPS 2024</strong>. See you in Vancouver.</li>
  <li><em>2024.08:</em> Organize a tutorial at <strong>KDD 2024</strong> in Barcelona on 25th, come if you are interested in epidemics + GNN!</li>
  <li><em>2024.08:</em> I serve as a reviewer for <strong>ICLR 2025</strong>.</li>
  <li><em>2024.06:</em> 🎉 One paper is accepted by <strong>TPAMI</strong>, congrats to all collaborators!</li>
  <li><em>2024.05:</em> I serve as a reviewer for <strong>NeurIPS 2024</strong>.</li>
  <li><em>2024.05:</em> 🎉 Our survey about GNNs in Epidemic Modeling is accepted by <strong>KDD 2024</strong>. See you in Barcelona!</li>
  <li><em>2024.05:</em> 🎉 One paper about self-supervised graph learning was accepted by <strong>ICML 2024</strong>. See you in Austria!</li>
  <li><em>2024.04:</em> 🚀 Explore our pre-print: a deep look at using Graph Neural Networks in Epidemic Modeling. Check our collected <a href="https://github.com/Emory-Melody/awesome-epidemic-modeling-papers">paper list</a>.</li>
  <li><em>2024.02:</em> I serve as a reviewer for <strong>ACM MM 2024</strong>.</li>
  <li><em>2024.02:</em> I serve as a reviewer for <strong>ECCV 2024</strong>.</li>
  <li><em>2023.12:</em> A paper was accepted to <strong>AAAI 2024</strong>. See you in Vancouver.</li>
  <li><em>2023.11:</em> I serve as a reviewer for <strong>CVPR 2024</strong>.</li>
  <li><em>2023.11:</em> 🚀 We thoroughly explore three core research areas in federated learning: generalization, robustness, and fairness. Don't hesitate to utilize our <a href="https://github.com/WenkeHuang/MarsFL">benchmarking codes</a> for your own research goal!</li>
  <li><em>2023.10:</em> I attended China National Computer Congress (CNCC) and was awarded the honor of CCF (China Computer Federation) Elite Collegiate Award (102 Students nation-wide).</li>
  <li><em>2023.10:</em> I won the National Scholarship for the second time (0.2% nation-wide), and was selected the Pacemaker to Merit Student (Award Rate: 60/59774=0.1%).</li>
  <li><em>2023.08:</em> we attended <em>the 32nd international joint conference on artificial intelligence (<strong>ijcai</strong>)</em> and presented our work in macao.</li>
</ul>
</div>

<br/>

# 📝 Manuscripts

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/MOTION.png">
<span class="conference-label">Under Review</span>
</dt>
  <dd><a href=""><strong>MOTION: Multi-Sculpt Evolutionary Coarsening for Federated Continual Graph Learning</strong></a></dd>
<dd>under review, 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/HYPERION.png">
<span class="conference-label">Under Review</span>
</dt>
  <dd><a href=""><strong>HYPERION: Fine-Grained Hypersphere Alignment for Robust Federated Graph Learning</strong></a></dd>
<dd>under review, 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/TRUST.png">
<span class="conference-label">Under Review</span>
</dt>
  <dd><a href=""><strong>Multi-order Orchestrated Curriculum Distillation for Model-Heterogeneous Federated Graph Learning</strong></a></dd>
<dd>under review, 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/OASIS.png">
<span class="conference-label">Under Review</span>
</dt>
  <dd><a href=""><strong>OASIS: One-Shot Federated Graph Learning via Wasserstein Assisted Knowledge Integration</strong></a></dd>
<dd>under review, 2025</dd>
</dl>

<hr>

# 📃 Selected Publications ([Full List](https://scholar.google.com/citations?user=pB8zP9UAAAAJ))

**&dagger; Equal Contribution**   

<div style="text-align: left; margin: 20px 0; font-size: 1.2em; color: #666;">
2025 
</div>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/FedTGE.png">
<span class="conference-label">ICLR 2025</span>
</dt>
  <dd><a href="https://openreview.net/forum?id=5Jc7r5aqHJ"><strong>	
Energy-based Backdoor Defense Against Federated Graph Learning
</strong></a></dd>
<dd><strong><strong>Guancheng Wan</strong>&dagger;</strong>, Zitong Shi&dagger;, Wenke Huang&dagger;, Guibin Zhang, Dacheng Tao, Mang Ye</dd>
<dd> <strong class="co-first"><i>Oral Presentation (Top 1.8%)</i></strong> in International Conference on Learning Representations (<strong>ICLR</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/GREAT.png">
<span class="conference-label">ICML 2025</span>
</dt>
  <dd><a href=""><strong>Rethink GraphODE Generalization within Coupled Dynamical System</strong></a></dd>
<dd><strong>Guancheng Wan</strong>, Zijie Huang, Wanjia Zhao, Xiao Luo, Yizhou Sun, Wei Wang</dd>
<dd>  <strong class="co-first"><i>Spotlight Presentation (Top 2.6%)</i></strong> in International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/LoRASculpt.png">
<span class="conference-label">CVPR 2025</span>
</dt>
  <dd><a href=""><strong>LoRASculpt: Sculpting LoRA for Harmonizing General and Specialized Knowledge in Multimodal Large Language Models</strong></a></dd>
  <dd>Jian Liang&dagger;, Wenke Huang&dagger;, <strong>Guancheng Wan&dagger;</strong> <span class="co-first">(co-first)</span>, Qu Yang, Mang Ye</dd>
  <dd><strong class="co-first"><i>Oral Presentation (Top 3.3%)</i></strong> in Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/FedSPA.png">
<span class="conference-label">CVPR 2025</span>
</dt>
  <dd><a href=""><strong>FedSPA: Generalizable Federated Graph Learning under Homophily Heterogeneity</strong></a></dd>
  <dd>Zihan Tan&dagger;, <strong>Guancheng Wan&dagger;</strong> <span class="co-first">(co-first)</span>, Wenke Huang, Guibin Zhang, He Li, Carl Yang, Mang Ye</dd>
  <dd>Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/EARTH.png">
<span class="conference-label">ICML 2025</span>
</dt>
  <dd><a href="https://arxiv.org/abs/2410.00049"><strong>Epidemiology-Aware Neural ODE with Continuous Disease Transmission Graph</strong></a></dd>
<dd><strong>Guancheng Wan</strong>, Zewen Liu, Xiaojun Shan, Max S.Y. Lau, B. Aditya Prakash, Wei Jin</dd>
<dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>


<hr>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/EMOE.png">
<span class="conference-label">CVPR 2025</span>
</dt>
  <dd><a href=""><strong>EMOE: Modality-Specific Enhanced Dynamic Emotion Experts</strong></a></dd>
  <dd>Yiyang Fang&dagger;, Wenke Huang&dagger;, <strong>Guancheng Wan&dagger;</strong> <span class="co-first">(co-first)</span>, Kehua Su, Mang Ye</dd>
  <dd>Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>), 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/GHOST.png">
  <span class="conference-label">ICML 2025</span>
  </dt>
  <dd><a href=""><strong>GHOST: Generalizable One-Shot Federated Graph Learning with Proxy-Based Topology Knowledge Retention</strong></a></dd>
  <dd>Jiaru Qian&dagger;, <strong>Guancheng Wan</strong>&dagger; <span class="co-first">(co-first)</span>, Wenke Huang, Guibin Zhang, Yuxin Wu, Bo Du, Mang Ye</dd>
  <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/EAGLES.png">
  <span class="conference-label">ICML 2025</span>
  </dt>
  <dd><a href=""><strong>EAGLES: Towards Effective, Efficient, and Economical Federated Graph Learning via Unified Sparsification</strong></a></dd>
  <dd>Zitong Shi&dagger;, <strong>Guancheng Wan</strong>&dagger; <span class="co-first">(co-first)</span>, Guibin Zhang, Wenke Huang, He Li, Carl Yang, Mang Ye</dd>
  <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/Gdesigner.png">
  <span class="conference-label">ICML 2025</span>
  </dt>
  <dd><a href=""><strong>G-Designer: Architecting Multi-agent Communication Topologies via Graph Neural Networks</strong></a></dd>
  <dd>Guibin Zhang, Yanwei Yue, Xiangguo Sun, <strong>Guancheng Wan</strong>, Miao Yu, Junfeng Fang, Kun Wang, Tianlong Chen, Dawei Cheng</dd>
  <dd> <strong class="co-first"><i>Spotlight Presentation (Top 2.6%)</i></strong> in International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/BeConfident.png">
  <span class="conference-label">ICML 2025</span>
  </dt>
  <dd><a href=""><strong>Be Confident: Uncovering Overfitting in MLLM Multi-Task Tuning</strong></a></dd>
  <dd>Wenke Huang, Jian Liang, <strong>Guancheng Wan</strong>, Didi Zhu, He Li, Jiawei Shao, Mang Ye, Bo Du, Dacheng Tao</dd>
  <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/agentprune.png">
  <span class="conference-label">ICLR 2025</span>
  </dt>
  <dd><a href="https://openreview.net/forum?id=LkzuPorQ5L"><strong>	
Cut the Crap: An Economical Communication Pipeline for LLM-based Multi-Agent Systems
</strong></a></dd>
  <dd>Guibin Zhang, Yanwei Yue, Zhixun Li, Sukwon Yun, <strong>Guancheng Wan</strong>, Kun Wang, Dawei Cheng, Jeffrey Xu Yu, Tianlong Chen</dd>
  <dd>International Conference on Learning Representations (<strong>ICLR</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/FedPHA.png">
<span class="conference-label">ICML 2025</span>
</dt>
  <dd><a href=""><strong>FedPHA: Federated Prompt Learning for Heterogeneous Client Adaptation</strong></a></dd>
  <dd>Chengying Fang&dagger;, Wenke Huang&dagger;, <strong>Guancheng Wan&dagger;</strong> <span class="co-first">(co-first)</span>, Yihao Yang, Mang Ye</dd>
  <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>

<hr>


<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/LFBA.png">
  <span class="conference-label">AAAI 2025</span>
  </dt>
  <dd><a href="https://ojs.aaai.org/index.php/AAAI/article/download/34246/36401"><strong>	
Label-free backdoor attacks in vertical federated learning</strong></a></dd>
  <dd>Wei Shen, Wenke Huang, <strong>Guancheng Wan</strong>, Mang Ye
  </dd>
    <dd> Annual AAAI Conference on Artificial Intelligence (<strong>AAAI</strong>), 2025</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/LearnFromDownstream.png">
  <span class="conference-label">ICML 2025</span>
  </dt>
  <dd><a href=""><strong>Learn from Downstream and Be Yourself in Multimodal Large Language Models Fine-Tuning</strong></a></dd>
  <dd>Wenke Huang, Jian Liang, Zekun Shi, Didi Zhu, <strong>Guancheng Wan</strong>, He Li, Bo Du, Dacheng Tao, Mang Ye</dd>
  <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>



<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/FedPrompt.png">
  <span class="conference-label">IJCAI 2025</span>
  </dt>
  <dd><a href=""><strong>An Empirical Study of Federated Prompt Learning for Vision Language Model</strong></a></dd>
  <dd>Zhihao Wang, Wenke Huang, Tian Chen, Zekun Shi, <strong>Guancheng Wan</strong>, Yu Qiao, Bin Yang, Jian Wang, Bing Li, Mang Ye</dd>
  <dd>The 34th International Joint Conference on Artificial Intelligence (<strong>IJCAI</strong>), 2025</dd>
</dl>


<hr>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="../images/FedDisentangledTuning.png">
<span class="conference-label">ICML 2025</span>
</dt>
  <dd><a href=""><strong>Federated Disentangled Tuning with Textual Prior Decoupling and Visual Dynamic Adaptation</strong></a></dd>
  <dd>Yihao Yang&dagger;, Wenke Huang&dagger;, <strong>Guancheng Wan&dagger;</strong> <span class="co-first">(co-first)</span>, Bin Yang, Mang Ye</dd>
  <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2025</dd>
</dl>




<hr>

<div style="text-align: left; margin: 20px 0; font-size: 1.2em; color: #666;">
2024
</div>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/S3GCL_ICML24.png">
  <span class="conference-label">ICML 2024</span>
  </dt>
  <dd><a href="https://proceedings.mlr.press/v235/wan24g.html"><strong>S3GCL: Spectral, Swift, Spatial Graph Contrastive Learning
</strong></a></dd>
  <dd><strong>Guancheng Wan</strong>, Yijun Tian, Wenke Huang, Nitesh V Chawla, Mang Ye</dd>
    <dd>International Conference on Machine Learning (<strong>ICML</strong>), 2024 </dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/FedSSP.png">
  <span class="conference-label">NeurIPS 2024</span>
  </dt>
  <dd><a href="https://arxiv.org/pdf/2410.20105"><strong>FedSSP: Federated Graph Learning with Spectral Knowledge and Personalized Preference</strong></a></dd>
  <dd>Zihan Tan&dagger;, <strong>Guancheng Wan&dagger; </strong><span class="co-first">(co-first)</span>, Wenke Huang&dagger;, Mang Ye</dd>
  <dd>Annual Conference on Neural Information Processing Systems (<strong>NeurIPS</strong>), 2024</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/FDCR.png">
  <span class="conference-label">NeurIPS 2024</span>
  </dt>
  <dd><a href=""><strong>	
Parameter Disparities Dissection for Backdoor Defense in Heterogeneous Federated Learning</strong></a></dd>
  <dd>Wenke Huang, Mang Ye, Zekun Shi, <strong>Guancheng Wan</strong>, He Li, Bo Du
  </dd>
  <dd>Annual Conference on Neural Information Processing Systems (<strong>NeurIPS</strong>), 2024</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  wspace="20" hspace="10" src="../images/fggp.png">
  <span class="conference-label">AAAI 2024</span>
  </dt>
  <dd ><a href="https://ojs.aaai.org/index.php/AAAI/article/view/29468"><strong> Federated Graph Learning under Domain Shift with Generalizable Prototypes</strong></a></dd>
  <dd><strong>Guancheng Wan</strong>, Wenke Huang, Mang Ye</dd>
    <dd> Annual AAAI Conference on Artificial Intelligence (<strong>AAAI</strong>), 2024</dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/episurvey.png">
  <span class="conference-label">KDD 2024</span>
  </dt>
  <dd><a href="https://dl.acm.org/doi/pdf/10.1145/3637528.3671455"><strong>A Review of Graph Neural Networks in Epidemic Modeling</strong></a></dd>
  <dd>Zewen Liu&dagger;, <strong>Guancheng Wan&dagger; </strong><span class="co-first">(co-first)</span>, B. Aditya Prakash, Max S. Y. Lau, Wei Jin</dd>
    <dd>ACM SIGKDD Conference on Knowledge Discovery and Data Mining (<strong>KDD</strong>), 2024</dd>
    <dd><a href="https://github.com/Emory-Melody/awesome-epidemic-modeling-papers">Project Page</a></dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10"   wspace="20" src="../images/fgssl.png">
  <span class="conference-label">IJCAI 2023</span>
  </dt>
  <dd><a href="https://arxiv.org/pdf/2406.18937"><strong>Federated Graph Semantic and Structural Learning</strong></a></dd>
  <dd>Wenke Huang&dagger;, <strong>Guancheng Wan&dagger; </strong><span class="co-first">(co-first)</span>, Mang Ye, Bo Du</dd>
  <dd> International Joint Conference on Artificial Intelligence (<strong>IJCAI</strong>), 2023  </dd>
</dl>

<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/flsurvey.png">
  <span class="conference-label">TPAMI 2024</span>
  </dt>
  <dd><a href="https://arxiv.org/abs/2311.06750"><strong>Federated Learning for Generalization, Robustness, Fairness: A Survey and Benchmark</strong></a></dd>
  <dd>Wenke Huang, Mang Ye, Zekun Shi, <strong>Guancheng Wan</strong>, He Li, Bo Du,  Qiang Yang
  </dd>
    <dd>IEEE Transactions on Pattern Analysis and Machine Intelligence (<strong>TPAMI</strong>), 2024</dd>
    <dd><a href="https://github.com/WenkeHuang/MarsFL">Project Page</a></dd>
</dl>

<hr>

# 📝 Manuscripts

- **Keeping Yourself is Important in Downstream Tuning Multimodal Large Language Model**

- **Protein Large Language Models: A Comprehensive Survey**

- **A Comprehensive Survey in LLM (-Agent) Full Stack Safety: Data, Training and Deployment**

<!-- 
<hr>


<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/SPIDER.png">
  </dt>
  <dd><a href=""><strong>	
Learn from Downstream and Be Yourself in Multimodal Large Language Model Fine-Tuning
</strong></a></dd>
<dd>under review, 2025</dd>


</dl>


<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/EAGLES.png">
  </dt>
  <dd><a href=""><strong>	
EAGLES: Towards Effective, Efficient, and Economical Federated Graph Learning via Unified Sparsification
</strong></a></dd>
<dd>under review, 2025</dd>


</dl> -->



<!-- 


<hr>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/FedSPA.png">
  </dt>
  <dd><a href=""><strong>	
FedSPA : Generalizable Federated Graph Learning under Homophily Heterogeneity
</strong></a></dd>
<dd>under review, 2024</dd>

</dl>


 -->


<hr>

# 🎡 Service
## Program Chair
- [FedKDD 2025 Workshop@KDD 2025](https://fedkdd.github.io/fedkdd2025/)


## Conference Committee Member
- Reviewer for ICML'2025, ICLR'2025, NeurIPS'2024/2025, AISTATS'2025
- Reviewer for CVPR'2024/2025, ICCV'2025, ECCV'2024
- Reviewer for AAAI'2025, IJCAI'2025, ACM MM'2024/2025

##  Journal Reviewer
- IEEE TIFS, TIP, TKDE, TNNLS
- ACM TKDD
- Pattern Recognition (PR)
- Data-centric Machine Learning Research (DMLR)

<!-- - Reviewer for Data-centric Machine Learning Research (DMLR) -->


<br/>

# 🎖 Scholarships and Honors

- *2024.11* <a href="https://mp.weixin.qq.com/s/aS639YfEZLi2Y457L5XjUg">**Lei Jun Excellence Scholarship** </a>(**<u>雷军卓越奖学金</u>**) **~100k** (The **<u>Highest</u>** Scholarship at Wuhan University, **<u>Top-4</u>** among All Undergraduates, Award Rate ~ **0.01%**)  *Wuhan University*

- *2023.09* **National Scholarship** **(<u>Twice</u>)** (**<u>国家奖学金</u>**) (Award Rate: <strong>0.2% nation-wide</strong>) *Ministry of Education, China* 

- *2022.09* **National Scholarship** (**<u>国家奖学金</u>**) (Award Rate: <strong>0.2% nation-wide</strong>) *Ministry of Education, China* 

- *2025.03* <a href="https://mp.weixin.qq.com/s/1quPOGcxbMkfMFgkl8tFKQ">**Luo Jia Role model** </a>(榜样珞珈年度人物) (10 Students school-wide)  *Wuhan University*

- *2024.10* **Luojia Undergraduate Innovation Research Fund** (首批珞珈本科生研究基金) ~50k (4 Students department-wide)  *Wuhan University*

- *2024.06* **Lei Jun Computer Innovation and Development Fund** and  **Research Fund** (雷军创新发展基金、雷军研究基金) (3 Students department-wide)  *Wuhan University*

- *2024.06* <a href="https://scholarship2024.sensetime.com/cn/">**SenseTime Scholarship**</a> (商汤奖学金) ~20k (**25 Students nation-wide**) *SenseTime*

- *2024.04* <a href="https://mp.weixin.qq.com/s/zdx8hH8-g0FScgZvkYQRnw">**CS Pioneer**</a> (计科先锋年度人物) (10 Students department-wide)  *Wuhan University*

- *2023.10* **CCF (China Computer Federation) Elite Collegiate Award** (CCF优秀大学生) (102 Students nation-wide) *China Computer Federation*

- *2023.10* **Pacemaker to Merit Student** (三好学生标兵) (Award Rate ~ <strong>0.1%</strong>) *Wuhan University*


<br/>

# 📖 Educations

<div style="margin-bottom: 40px;">
  <div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1; font-size: 1.1em;">
      <strong>2025.09 - Now</strong><br/>
      PhD, Computer Science, University of California, Los Angeles (UCLA)<br/>
    </div>
    <div style="flex-shrink: 0; max-width: 100px;">
      <img src="../images/UCLA.png" alt="UCLA Logo" style="width: 100%; height: auto; object-fit: contain;" />
    </div>
  </div>
</div>

<div style="margin-bottom: 40px;">
  <div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1; font-size: 1.1em;">
      <strong>2021.09 - 2025.06</strong><br/>
      Undergraduate, School of Computer Science, Wuhan University<br/>
    </div>
    <div style="flex-shrink: 0; max-width: 100px;">
      <img src="../images/WHU.jpeg" alt="Wuhan University Logo" style="width: 100%; height: auto; object-fit: contain;" />
    </div>
  </div>
</div>

<!-- 
<div style="margin-bottom: 40px;">
  <div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1; font-size: 1.1em;">
      <strong>2018.09 - 2021.06</strong><br/>
      High School, The Attached Middle School To Jiangxi Normal University
    </div>
    <div style="flex-shrink: 0; max-width: 100px;">
      <img src="../images/fuzhong.png" alt="High School Logo" style="width: 100%; height: auto; object-fit: contain;" />
    </div>
  </div>
</div> -->


<dl><a href="https://clustrmaps.com/site/1bxa7" title="Visit tracker"><img src="//clustrmaps.com/map_v2.png?cl=080808&w=400&t=n&d=3d-gAqSb6Wx-DoL_BIvviv0g9ivHnOPl9-3M98ywjqw&co=ffffff&ct=808080" /></a></dl>




# Miscellaneous

<details>
  <summary><strong>Talks and Shares</strong></summary>
<dd><a href="https://www.bilibili.com/video/BV1gZ42177VL/?spm_id_from=333.337.search-card.all.click&vd_source=0b7a3cc3d3ec288abaca83b9a7e036af"><strong>泛化图学习与本科生科研经历分享</strong></a></dd>




</details>


<details>
  <summary><strong>Undergraduate research resource and enrollment process</strong></summary>

<dd><a href="https://zxeupbuzh9y.feishu.cn/docx/ZDEsdpZtPosRWOxcBnkcF8Hknkd"><strong>Link</strong></a></dd>


</details>



<details>
  <summary><strong>Poems that inspire me</strong></summary>
  <dd><strong>白鹭立雪，愚者看鹭，聪者观雪，智者见白</strong> —— A white egret stands in the snow. The foolish see only the egret, the wise observe the snow, and the enlightened perceive the whiteness.</dd>
  <dd><strong>世界不黑也不白, 而是一道精致的灰</strong> —— The world is neither black nor white, but a delicate shade of gray. </dd>
    <dd><strong>风吹到哪页读哪页</strong> —— The wind blows to which page, read which page.. </dd>
</details>




