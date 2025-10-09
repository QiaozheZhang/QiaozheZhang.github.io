<!-- -->
- <span class="badge">EMNLP 2025 </span> **CoLA: Compute-Efficient Pre-Training of LLMs via Low-Rank Activation <span style="color:red">(oral)</span>** <br>
  Ziyue Liu<sup>*</sup>, <span class="underline"><b>Ruijie Zhang</b></span><sup>*</sup>, Zhengyang Wang<sup>*</sup>, Mingsong Yan, Zi Yang, Paul Hovland, Bogdan Nicolae, Franck Cappello, Sui Tang, Zheng Zhang  <br>
  The 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP 2025) <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2502.10940" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/alvin-zyl/CoLA" target="_blank" rel="noopener">code</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{liu2025cola,
  title={Cola: Compute-efficient pre-training of llms via low-rank activation},
  author={Liu, Ziyue and Zhang, Ruijie and Wang, Zhengyang and Yan, Mingsong and Yang, Zi and Hovland, Paul and Nicolae, Bogdan and Cappello, Franck and Tang, Sui and Zhang, Zheng},
  journal={arXiv preprint arXiv:2502.10940},
  year={2025}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">The full-size MLPs and the projection layers in attention introduce tremendous model sizes of large language models (LLMs), consuming extensive computational resources in pre-training. We empirically observe that the activations of pre-trained LLMs exhibit low-rank property. Motivated by such observations, we propose CoLA and its memory-efficient implementation, CoLA-M, to replace these full-size layers with compute-efficient auto-encoders that naturally enforce low-rank activations throughout training. This fundamental architectural change eliminates the activation redundancy and significantly boosts model capacity and training efficiency. Experiments on LLaMA models with 60 million to 7 billion parameters show that CoLA reduces the computing cost by 2×× and improves training throughput by 1.86×× while maintaining full-rank level performance. CoLA-M further squeezes memory cost without sacrificing throughput, offering a pre-training approach with collectively superior parameter, computing, and memory efficiency. The LLMs produced are also 2×× smaller, enabling faster inference with lower memory cost on resource-constrained platforms.</code></pre></div>
