<!-- -->
- <span class="badge">Preprint</span> **Beyond the Matrix Sign: Quadratic Spectral Descent** <br>
  <span class="underline"><b>Qiaozhe Zhang</b></span>, Jun Sun, Yingzhuang Liu <br>
  arXiv, 2026  <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/pdf/2609.07597" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="URL" target="_blank" rel="noopener">code (coming soon)</a>
  </div>
  <div id="bib" class="bibbox"><pre><code class="language-bibtex">@misc{zhang2026matrixsignquadraticspectral,
      title={Beyond the Matrix Sign: Quadratic Spectral Descent}, 
      author={Qiaozhe Zhang and Jun Sun and Yingzhuang Liu},
      year={2026},
      eprint={2609.07597},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2609.07597}, 
}</code></pre></div>
  <div id="abstract" class="bibbox"><pre><code class="language-bibtex">Muon emerges as a strong competitor of the AdamW for LLM pretraining, because the matrix-wise update it employs can potentially incur smaller second-order penalty than the once dominating AdamW, which performs coordinate-wise update. However, the spectral flattening procedure in Muon is quite debatable since it discards the spectral amplitude information totally. To seek  for better spectral  allocation (and the associated spectral subspace), we propose to solve the quadratic model of loss function under  the spectral norm constraint \textit{directly} (i.e., in a genuinely Newtonian way) and thus obtaining the Quadratic Spectral Descent (QSD) algorithm. In contrast, many existing curvature-aware methods either exploit the second-order information in an \textit{implicit} way by changing the weight update geometry (such as Mousse, FISMO) or rely on strong assumptions (such as the weight displacement isotropy assumption in Newton-Muon). QSD's potential advantage over these methods is best illustrated in the isotropic curvature scenario, where Mousse, FISMO and Newton-Muon all reduce to Muon while the spectral allocation in QSD is still  \textit{non-flat} (since the spectral allocation in QSD depends on the \textit{gradient to curvature ratio}). Meanwhile, to control the complexity of QSD, we employ inversion-free K-FAC and \textit{online} Frank-Wolfe update which is essentially a matrix sign operator. Overall, the complexity increase can be rather mild. Experiments on GPT pre-training show that QSD consistently improves validation loss over Muon and recent Muon variants, while achieving up to an $8.49\%$ wall-clock speedup at matched validation loss.</code></pre></div>
