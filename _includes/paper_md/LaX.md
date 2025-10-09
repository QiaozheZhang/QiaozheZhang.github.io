<!-- -->
- <span class="badge">NeurIPS 2025</span> **LaX: Boosting Low-Rank Training of Foundation Models via Latent Crossing** <br>
  <span class="underline"><b>Ruijie Zhang</b></span><sup>*</sup>, Ziyue Liu<sup>*</sup>, Zhengyang Wang, Zheng Zhang <br>
  The 39th Annual Conference on Neural Information Processing Systems (NeurIPS), 2025 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2505.21732" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/K1seki221/Latent_Crossing" target="_blank" rel="noopener">code</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{zhang2025lax,
  title={LaX: Boosting Low-Rank Training of Foundation Models via Latent Crossing},
  author={Zhang, Ruijie and Liu, Ziyue and Wang, Zhengyang and Zhang, Zheng},
  journal={arXiv preprint arXiv:2505.21732},
  year={2025}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Training foundation models such as ViTs and LLMs requires tremendous computing cost. Low-rank matrix or tensor factorization offers a parameter-efficient alternative, but often downgrades performance due to the restricted parameter space. In this work, we introduce {\textbf{Latent Crossing (LaX)}} -- a simple yet effective plug-and-play module that enhances the capacity of low-rank models by enabling information flow across low-rank subspaces. We extensively validate the benefits of LaX on pre-training tasks with ViT-Base/Large and LLaMA-like models ranging from 60M to 1B parameters. LaX boosts low-rank model performance to match or exceed the full-rank baselines while using 2-3 fewer parameters. When equipped with low-rank adapters (i.e., LoRA) for fine-tuning LLaMA-7/13B, LaX consistently improves performance on arithmetic and common sense reasoning tasks with negligible cost.</code></pre></div>
