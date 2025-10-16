<!-- projects.html -->
<section class="projects">
  <h1>Selected Projects</h1>
  <div class="projects-grid">
    <!-- Project card -->
    <article class="project-card">
      <figure class="project-media">
        <picture>
          <source srcset="{{ '/assets/img/RL_img.webp' | absolute_url }}" type="image/webp">
          <img
            src="{{ '/assets/img/RL_img.png' | absolute_url }}"
            alt="Illustration for kernel-based reinforcement learning"
            loading="lazy"
            decoding="async">
        </picture>
      </figure>
      <div class="project-body">
        <h2 class="project-title">Kernel-based RL</h2>
        <p class="project-desc">
          We introduce a kernel-based optimistic least-squares value iteration policy with
          order-optimal regret for common kernel classes (Matérn, NTK), improving over SOTA.
        </p>
        <div class="project-tags">
          <span>Reinforcement Learning</span><span>Kernels</span><span>Regret</span>
        </div>
        <div class="project-actions">
          <a class="btn" href="https://arxiv.org/abs/2306.07745" target="_blank" rel="noopener">Read paper</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <figure class="project-media">
        <picture>
          <source srcset="{{ '/assets/img/SPD.webp' | absolute_url }}" type="image/webp">
          <img src="{{ '/assets/img/SPD.png' | absolute_url }}"
               alt="Shortest Path Diffusion: plots and samples"
               loading="lazy" decoding="async">
        </picture>
      </figure>
      <div class="project-body">
        <h2 class="project-title">Shortest Path Diffusion</h2>
        <p class="project-desc">
          We perturb images along the shortest path (Fisher metric) from data to noise, yielding
          a hyper-parameter-free corruption schedule that outperforms strong baselines.
        </p>
        <div class="project-tags"><span>Diffusion</span><span>Generative</span></div>
        <div class="project-actions">
          <a class="btn" href="https://arxiv.org/abs/2306.00501" target="_blank" rel="noopener">Read paper</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <figure class="project-media">
        <img src="{{ '/assets/img/gp_regression_plot.png' | absolute_url }}"
             alt="Gaussian process regression plot" loading="lazy" decoding="async">
      </figure>
      <div class="project-body">
        <h2 class="project-title">Nyström & SVGP Rates</h2>
        <p class="project-desc">
          New confidence intervals for surrogate variances tighten performance bounds in regression
          and BO; ICML’22 Spotlight (with J. Scarlett).
        </p>
        <div class="project-tags"><span>GPs</span><span>Approximation</span></div>
        <div class="project-actions">
          <a class="btn" href="https://proceedings.mlr.press/v162/vakili22a.html" target="_blank" rel="noopener">Paper</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <figure class="project-media">
        <img src="{{ '/assets/img/glob3.png' | absolute_url }}"
             alt="Wireless channel globe visual" loading="lazy" decoding="async">
      </figure>
      <div class="project-body">
        <h2 class="project-title">Wireless Channel Modelling</h2>
        <p class="project-desc">
          Stable diffusion-based channel modelling with diverse, high-fidelity samples and
          effective transfer learning from limited real data.
        </p>
        <div class="project-tags"><span>Wireless</span><span>Diffusion</span></div>
        <div class="project-actions">
          <a class="btn" href="https://arxiv.org/abs/2308.05583" target="_blank" rel="noopener">Paper</a>
        </div>
      </div>
    </article>
  </div>
</section>
