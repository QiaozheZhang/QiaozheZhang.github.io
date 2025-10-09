<!-- -->
- <span class="badge">NeurIPS 2024</span> **How Sparse Can We Prune A Deep Network: A Fundamental Limit Perspective** <br>
  Qiaozhe Zhang, <span class="underline"><b>Ruijie Zhang</b></span>, Jun Sun, Yingzhuang Liu <br>
  The Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/pdf/2306.05857" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/QiaozheZhang/Global-One-shot-Pruning" target="_blank" rel="noopener">code</a>
  <a class="newbadge purple"  href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/a627810151be4d13f907ac898ff7e948-Abstract-Conference.html" target="_blank" rel="noopener">NeurIPS</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{zhang2024sparse,
      title={How sparse can we prune a deep network: A fundamental limit perspective},
      author={Zhang, Qiaozhe and Zhang, Ruijie and Sun, Jun and Liu, Yingzhuang},
      journal={Advances in Neural Information Processing Systems},
      volume={37},
      pages={91337--91372},
      year={2024}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Network pruning is a commonly used measure to alleviate the storage and computational burden of deep neural networks. However, the fundamental limit of network pruning is still lacking. To close the gap, in this work we'll take a first-principles approach, i.e. we'll directly impose the sparsity constraint on the loss function and leverage the framework of statistical dimension in convex geometry, thus enabling us to characterize the sharp phase transition point, which can be regarded as the fundamental limit of the pruning ratio. Through this limit, we're able to identify two key factors that determine the pruning ratio limit, namely, weight magnitude and network sharpness. Generally speaking, the flatter the loss landscape or the smaller the weight magnitude, the smaller pruning ratio. Moreover, we provide efficient countermeasures to address the challenges in the computation of the pruning limit, which mainly involves the accurate spectrum estimation of a large-scale and non-positive Hessian matrix. Moreover, through the lens of the pruning ratio threshold, we can also provide rigorous interpretations on several heuristics in existing pruning algorithms. Extensive experiments are performed which demonstrate that our theoretical pruning ratio threshold coincides very well with the experiments.</code></pre></div>
