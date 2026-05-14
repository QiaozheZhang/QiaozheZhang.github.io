<!-- -->
- <span class="badge">ICLR 2026</span> **Rényi Sharpness: A Novel Sharpness that Strongly Correlates with Generalization** <br>
  <span class="underline"><b>Qiaozhe Zhang</b></span>, Jun Sun, Ruijie Zhang, Yingzhuang Liu <br>
  The Fourteenth International Conference on Learning Representations (ICLR), 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/pdf/2510.07758" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/QiaozheZhang/RSAM" target="_blank" rel="noopener">code</a>
  <a class="newbadge purple"  href="https://iclr.cc/virtual/2026/poster/10007148" target="_blank" rel="noopener">ICLR</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@misc{zhang2025renyisharpnessnovelsharpness,
      title={R\'enyi Sharpness: A Novel Sharpness that Strongly Correlates with Generalization}, 
      author={Qiaozhe Zhang and Jun Sun and Ruijie Zhang and Yingzhuang Liu},
      year={2025},
      eprint={2510.07758},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.07758}, 
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Sharpness (of the loss minima) is widely believed to be a good indicator of generalization of neural networks. Unfortunately, the correlation between existing sharpness measures and the generalization is not that strong as expected, sometimes even contradiction occurs. To address this problem, a key observation in this paper is: what really matters for the generalization is the \textit{average spread} (or unevenness) of the spectrum of loss Hessian $\mathbf{H}$. For this reason, the conventional sharpness measures, such as the trace sharpness $\operatorname{tr}(\mathbf{H})$, which cares about the \textit{average value} of the spectrum,  or the max-eigenvalue sharpness $\lambda_{\max}(\mathbf{H})$, which concerns the  \textit{maximum spread} of the spectrum, are not sufficient to well predict the generalization. To finely characterize the average spread of the Hessian spectrum, we leverage the notion of \textit{Rényi entropy} in information theory, which is capable of capturing the unevenness of a probability vector and thus can be extended to describe the unevenness for a general non-negative vector (which is the case for the Hessian spectrum at the loss minima). In specific, in this paper we propose the \textit{Rényi sharpness}, which is defined as the negative of the Rényi entropy of loss Hessian $\mathbf{H}$. Extensive experiments demonstrate that Rényi sharpness exhibit \textit{strong} and \textit{consistent} correlation with generalization in various scenarios. Moreover, on the theoretical side, two generalization bounds with respect to the Rényi sharpness are  established, by exploiting the desirable reparametrization invariance property of Rényi sharpness. Finally, as an initial attempt to take advantage of the  Rényi sharpness for regularization, Rényi Sharpness Aware Minimization (RSAM) algorithm is proposed where a variant of Rényi Sharpness is used as the regularizer. It turns out this RSAM is competitive with the state-of-the-art SAM algorithms, and far better than the conventional SAM algorithm based on the max-eigenvalue sharpness. </code></pre></div>
