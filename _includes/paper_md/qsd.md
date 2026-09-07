<!-- -->
- <span class="badge">Preprint</span> **TITLE** <br>
  <span class="underline"><b>Qiaozhe Zhang</b></span>, Jun Sun, Yingzhuang Liu <br>
  ArXiv  <br>
  <div class="newbadges" id="tabs" data-open="">
  <!--  <button class="newbadge green"  type="button" data-tab="bib">bib</button> -->
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="URL" target="_blank" rel="noopener">arXiv (coming soon)</a>
  <a class="newbadge red"  href="URL" target="_blank" rel="noopener">code (coming soon)</a>
  </div>
  <!-- <div id="bib" class="bibbox"><pre><code class="language-bibtex">BIB</code></pre></div> -->
  <div id="abstract" class="bibbox"><pre><code class="language-bibtex">Muon can be interpreted as optimizing a linear local objective over a spectral-norm ball. This gives a matrix-sign update that preserves the singular directions of the gradient and assigns the same magnitude to all active singular modes. We ask whether these two properties remain optimal when local curvature is taken into account. To answer this question, we keep Muon's spectral-norm constraint unchanged and replace the linear local model with a quadratic one. We call the resulting method \emph{Quadratic Spectral Descent} (QSD). We show that curvature can change both the singular values and the singular directions of the optimal update. To make QSD practical, we approximate curvature with Kronecker-factored statistics and solve the constrained quadratic with a small number of Frank--Wolfe steps, each of which has a closed-form matrix-sign subproblem. We further provide an optimality certificate, a comparison with Muon under the same quadratic surrogate, and an $O(1/K)$ convergence rate for the inner solver. Experiments on GPT pre-training show that QSD consistently improves validation loss over Muon and recent Muon variants, and reduces wall-clock training time by up to $8.49\%$ at matched validation loss.</code></pre></div>
