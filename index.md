---
layout: page
title: About
permalink: /index.html
---

<img style="float:right; padding-left:10px" src="images/selfandcat.jpg" width="220" height="220">

I am a Ph.D. student at [Huazhong University of Science and Technology](https://english.hust.edu.cn/), supervised by Prof. Jun Sun and Prof. Yingzhuang Liu. 

Previously, I received my B.Eng degree (2014-2018) in Electronic Information Engineering from [Huazhong University of Science and Technology](https://english.hust.edu.cn/).

<!-- News -->

# Selected work

- <span class="badge">Preprint</span> **Rényi Sharpness: A Novel Sharpness that Strongly Correlates with Generalization** <br>
  <span class="underline"><b>Qiaozhe Zhang</b></span>, Jun Sun, Ruijie Zhang, Yingzhuang Liu <br>
  Arxiv 2025 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="" target="_blank" rel="noopener">arXiv (coming soon)</a>
  <a class="newbadge red"  href="https://github.com/QiaozheZhang/RSAM" target="_blank" rel="noopener">code</a>
  </div>
  <div id="bib" class="bibbox">
    <pre><code class="language-bibtex">coming soon</code></pre>
  </div>
  <div id="abstract" class="bibbox">
    <pre><code class="language-bibtex">Sharpness (of the loss minima) is a common measure to investigate the generalization of neural networks. Intuitively speaking, the flatter the landscape near the minima is, the better generalization might be. Unfortunately, the correlation between many existing sharpness measures and the generalization is usually not strong, sometimes even weak. To close the gap between the intuition and the reality, we propose a novel sharpness measure, i.e., \textit{Rényi sharpness}, which is defined as the negative Rényi entropy (a generalization of the classical Shannon entropy) of the loss Hessian. The main ideas are as follows: 1) we realize that \textit{uniform} (identical) eigenvalues of the loss Hessian is most desirable (while keeping the sum constant) to achieve good generalization; 2) we employ the \textit{Rényi entropy} to concisely characterize the extent of the spread of the eigenvalues of loss Hessian. Normally, the larger the spread, the smaller the (Rényi) entropy. To rigorously establish the relationship between generalization and (Rényi) sharpness, we provide several generalization bounds in terms of Rényi sharpness, by taking advantage of the reparametrization invariance property of Rényi sharpness, as well as the trick of translating the data discrepancy to the weight perturbation. Furthermore, extensive experiments are conducted to verify the strong correlation (in specific, Kendall rank correlation) between the Rényi sharpness and generalization. Moreover, we propose to use a variant of Rényi Sharpness as  regularizer during training, i.e., Rényi Sharpness Aware Minimization (RSAM),  which turns out to outperform all existing sharpness-aware minimization methods. It is worthy noting that the test accuracy gain of our proposed RSAM method could be as high as nearly 2.5\%,  compared against the classical SAM method. </code></pre>
  </div>


<!-- - ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1e88e5?style=flat) **How Sparse Can We Prune A Deep Network: A Fundamental Limit Perspective** <br> -->
- <span class="badge">NeurIPS 2024</span> **How Sparse Can We Prune A Deep Network: A Fundamental Limit Perspective** <br>
  <span class="underline"><b>Qiaozhe Zhang</b></span>, Ruijie Zhang, Jun Sun, Yingzhuang Liu <br>
  The Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024 <br>
    [paper](https://arxiv.org/pdf/2306.05857) |
    [repo](https://github.com/QiaozheZhang/Global-One-shot-Pruning) |
    [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a627810151be4d13f907ac898ff7e948-Abstract-Conference.html)

- <span class="badge">Preprint</span> **Multi-level Multiple Instance Learning with Transformer for Whole Slide Image Classification** <br>
  Ruijie Zhang, <span class="underline"><b>Qiaozhe Zhang</b></span>, Yingzhuang Liu, Hao Xin, Yan Liu, Xinggang Wang <br>
  Arxiv 2023 <br>
    [paper](https://arxiv.org/pdf/2306.05029) |
    [repo](https://github.com/hustvl/MMIL-Transformer/tree/main)

<!-- - <span class="badge">ACM MM 2018</span> **Monocular Camera Based Real-Time Dense Mapping Using Generative Adversarial Network** <br>
  Xin Yany, Jinyu Chen, Zhiwei Wang, <span class="underline"><b>Qiaozhe Zhang</b></span>, Wenyu Liu, Chunyuan Liao, Kwang-Ting Cheng <br>
  Proceedings of the 26th ACM international conference on Multimedia, 896-904 <br>
    [paper](https://drive.google.com/file/d/1xjo4Ghima4qP_VZGdxzn4ZjHPHkDqjnW/view)  -->

# Services
Review: NeurIPS'24, ICLR'25, ICML'25, NeurIPS'25, ICLR'26, etc


<script>
document.addEventListener('click', function (e) {
  const btn = e.target.closest('.newbadges .newbadge[data-tab]');
  if (!btn) return;
  const wrap = btn.closest('.newbadges');
  const tab = btn.dataset.tab;
  wrap.dataset.open = (wrap.dataset.open === tab) ? '' : tab;
});
</script>
