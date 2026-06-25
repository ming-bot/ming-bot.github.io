---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
.pub-list { margin-top: 1.5em; }
.pub-card {
  display: flex;
  gap: 1.3em;
  padding: 1.3em 1.5em;
  margin-bottom: 1.4em;
  border: 1px solid #e6e8eb;
  border-radius: 14px;
  background: #fff;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  transition: box-shadow 0.22s ease, transform 0.22s ease, border-color 0.22s ease;
}
.pub-card:hover {
  box-shadow: 0 8px 22px rgba(0,0,0,0.09);
  transform: translateY(-2px);
  border-color: #d0d4d9;
}
.pub-thumb {
  flex: 0 0 210px;
  align-self: center;
}
.pub-thumb img {
  width: 100%;
  border-radius: 9px;
  display: block;
}
.pub-body { flex: 1 1 auto; min-width: 0; }
.pub-venue {
  display: inline-block;
  font-size: 0.72em;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #0085a1;
  background: rgba(0,133,161,0.10);
  padding: 0.28em 0.75em;
  border-radius: 999px;
  margin-bottom: 0.65em;
}
.pub-venue.spotlight {
  color: #b8860b;
  background: rgba(184,134,11,0.13);
}
.pub-title {
  font-size: 1.08em;
  font-weight: 700;
  line-height: 1.38;
  margin: 0 0 0.45em 0;
  color: #1a1a1a;
}
.pub-authors {
  font-size: 0.92em;
  color: #555;
  line-height: 1.5;
  margin-bottom: 0.85em;
}
.pub-authors .me { color: #1a1a1a; font-weight: 700; }
.pub-links { display: flex; flex-wrap: wrap; gap: 0.55em; }
.pub-btn {
  display: inline-flex;
  align-items: center;
  font-size: 0.82em;
  font-weight: 600;
  text-decoration: none !important;
  color: #0085a1;
  border: 1px solid #0085a1;
  padding: 0.32em 0.95em;
  border-radius: 999px;
  transition: background 0.18s ease, color 0.18s ease;
}
.pub-btn:hover {
  background: #0085a1;
  color: #fff !important;
}
@media (max-width: 600px) {
  .pub-card { flex-direction: column; gap: 1em; }
  .pub-thumb { flex-basis: auto; }
}
</style>

<div class="pub-list" markdown="0">
<div class="pub-card"> 
<div class="pub-thumb">
    <img src="../images/ICLR_data_distribution.png" alt="IDEAL: Data Equilibrium Adaptation for Multi-Capability Language Model Alignment" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">ICLR 2026</span>
    <p class="pub-title">IDEAL: Data Equilibrium Adaptation for Multi-Capability Language Model Alignment</p>
    <p class="pub-authors"><span class="me">Chenlin Ming</span>, Chendi Qu, Xiaoming Duan, Qizhi Pei, Zhuoshi Pan, Yu Li, Conghui He, Lijun Wu</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://arxiv.org/abs/2505.12762" target="_blank" rel="noopener">arXiv</a>
      <a class="pub-btn" href="https://github.com/ming-bot/IDEAL" target="_blank" rel="noopener">Code</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/ral_obstacle_exp.png" alt="Stochastic Trajectory Optimization for Robotic Skill Acquisition From a Suboptimal Demonstration" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">RA-L 2025</span>
    <p class="pub-title">Stochastic Trajectory Optimization for Robotic Skill Acquisition From a Suboptimal Demonstration</p>
    <p class="pub-authors"><span class="me">Chenlin Ming</span>, Zitong Wang, Boxuan Zhang, Zhanxiang Cao, Xiaoming Duan, Jianping He</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://ieeexplore.ieee.org/document/10976394/" target="_blank" rel="noopener">IEEE</a>
      <a class="pub-btn" href="https://github.com/ming-bot/MSTOMP" target="_blank" rel="noopener">Code</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/CAC_Framework.png" alt="HiCRISP: An LLM-Based Hierarchical Closed-Loop Robotic Intelligent Self-Correction Planner" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">CAC 2024</span>
    <p class="pub-title">HiCRISP: An LLM-Based Hierarchical Closed-Loop Robotic Intelligent Self-Correction Planner</p>
    <p class="pub-authors"><span class="me">Chenlin Ming</span>, Jiacheng lin, Pangkit Fong, Han Wang, Xiaoming Duan, Jianping He</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://ieeexplore.ieee.org/abstract/document/10865457/" target="_blank" rel="noopener">IEEE</a>
      <a class="pub-btn" href="https://github.com/ming-bot/HiCRISP" target="_blank" rel="noopener">Code</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/MathFusion.png" alt="MathFusion: Enhancing mathematic problem-solving of LLM through instruction fusion" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">ACL 2025</span>
    <p class="pub-title">MathFusion: Enhancing mathematic problem-solving of LLM through instruction fusion</p>
    <p class="pub-authors">Qizhi, Pei, Lijun Wu, Zhuoshi Pan, Yu Li, Honglin lin, <span class="me">Chenlin Ming</span>, Xin Gao, Conghui He, Rui Yan</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://aclanthology.org/2025.acl-long.367.pdf" target="_blank" rel="noopener">ACL</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/Lemma.png" alt="LEMMA: Learning from Errors for MatheMatical Advancement in LLMs" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">ACL 2025(Findings)</span>
    <p class="pub-title">LEMMA: Learning from Errors for MatheMatical Advancement in LLMs</p>
    <p class="pub-authors">Zhuoshi Pan, Yu Li, Honglin lin, Qizhi Pei, Zinan Tang, Wei Wu, <span class="me">Chenlin Ming</span>, H. Vicky Zhao, Conghui He, Lijun Wu</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://aclanthology.org/2025.findings-acl.605.pdf" target="_blank" rel="noopener">ACL</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/Ciperbench.png" alt="CipherBank: Exploring the Boundary of LLM Reasoning Capabilities through Cryptography Challenges" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">ACL 2025(Findings)</span>
    <p class="pub-title">CipherBank: Exploring the Boundary of LLM Reasoning Capabilities through Cryptography Challenges</p>
    <p class="pub-authors">Yu Li, Qizhi Pei, Mengyuan Sun, Honglin lin, <span class="me">Chenlin Ming</span>, Xin Gao, Jiang Wu, Conghui He, Lijun Wu</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://aclanthology.org/2025.findings-acl.309.pdf" target="_blank" rel="noopener">ACL</a>
    </div>
  </div>
</div>

<!-- <div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/selection_sequential.png" alt="Detecting and Identifying Selection Structure in Sequential Data" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">ICML 2024</span>
    <p class="pub-title">Detecting and Identifying Selection Structure in Sequential Data</p>
    <p class="pub-authors">Yujia Zheng, Zeyu Tang, <span class="me">Yiwen Qiu</span>, Bernhard Schölkopf, Kun Zhang</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://arxiv.org/pdf/2407.00529" target="_blank" rel="noopener">arXiv</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-body">
    <span class="pub-venue">IEEE L-CSS 2023</span>
    <p class="pub-title">Data-Driven Predictive Control Using Closed-Loop Data: An Instrumental Variable Approach</p>
    <p class="pub-authors">Yibo Wang, <span class="me">Yiwen Qiu</span>, Malika Sader, Dexian Huang, Chao Shang</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://arxiv.org/pdf/2309.05916" target="_blank" rel="noopener">arXiv</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/1_transferable_demonstrations.jpeg" alt="Out-of-Dynamics Imitation Learning from Multimodal Demonstrations" />
  </div>
  <div class="pub-body">
    <span class="pub-venue">CoRL 2022</span>
    <p class="pub-title">Out-of-Dynamics Imitation Learning from Multimodal Demonstrations</p>
    <p class="pub-authors"><span class="me">Yiwen Qiu</span>, Jialong Wu, Zhangjie Cao, Mingsheng Long</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://openreview.net/forum?id=X6CjiTWVRVr" target="_blank" rel="noopener">OpenReview</a>
      <a class="pub-btn" href="https://arxiv.org/abs/2211.06839v1" target="_blank" rel="noopener">arXiv</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-thumb">
    <img src="../images/2_wheel_legged.jpeg" alt="When to Trust Your Simulator" />
  </div>
  <div class="pub-body">
    <span class="pub-venue spotlight">NeurIPS 2022 · Spotlight</span>
    <p class="pub-title">When to Trust Your Simulator: Dynamics-Aware Hybrid Offline-and-Online Reinforcement Learning</p>
    <p class="pub-authors">Haoyi Niu, Shubham Sharma, <span class="me">Yiwen Qiu</span>, Ming Li, Guyue Zhou, Jianming Hu, Xianyuan Zhan</p>
    <div class="pub-links">
      <a class="pub-btn" href="https://arxiv.org/abs/2206.13464v1" target="_blank" rel="noopener">arXiv</a>
    </div>
  </div>
</div>

</div> -->