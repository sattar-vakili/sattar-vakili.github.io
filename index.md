---
layout: home
profile_picture:
  src: /assets/img/profile_pic_sattar.jpg
  alt: sattar vakili
---

# Research Interests

<ul>
  <li> Machine learning and AI</li>
  <li> Diffusion models</li>
  <li> Sequential decision making, bandit and RL</li>
  <li> Kernel methods, Gaussian processes and Bayesian optimisation</li>
</ul>



<span style="color:white">Sattar Vakili</span>

<span style="color:white">Machine Learning, Bandit, Reinforcement learning, kernel methods, Google Scholar, LinkedIn, Cornell, MediaTek, MediaTek Research, Cambridge </span>


# Selected Projects

## Kernel-based RL

<img src="{{ "/assets/img/RL_img.png" | absolute_url }}" alt="{{ Image }}"  style="width:250px;height:250px;" />

Reinforcement Learning (RL) has shown great empirical success in various settings with complex models and large state-action spaces. However, the existing analytical results typically focus on settings with a small number of state-actions or simple models, such as linearly modeled state-action value functions. To derive RL policies that efficiently handle large state-action spaces with more general value functions, some recent works have explored nonlinear function approximation using kernel ridge regression. In this <a href="https://arxiv.org/abs/2306.07745" target="_blank" rel="noopener"> paper </a>, we introduce a kernel based optimistic least-squares value iteration policy that achieves order optimal regret bounds for a common class of kernels. Our results show a significant improvement over the state of the art.


## Shortest Path Diffusion

<img src="{{ "/assets/img/SPD.png" | absolute_url }}" alt="{{ Image }}"  style="width:250px;height:250px;" />

Denosing diffusion models have shown significant advancements in image generation. We introduce a novel approach where images are perturbed with noise along the shortest path from the distribution of images to the distribution of noise. We propose the Fisher metric for the path length, measured in the space of probability distributions. Referred to as Shortest Path Diffusion (SPD), this approach uniquely determines the complete spatiotemporal structure of the corruption process. We demonstrate that SPD surpasses strong baseline methods without requiring any hyperparameter tuning. 


## Convergence rate of Nyström method (or SVGP)

<img src="{{ "/assets/img/gp_regression_plot.png" | absolute_url }}" alt="{{ Image }}"  style="width:250px;height:250px;" />

Kernel-based models, including kernel ridge regression and Gaussian processes, are widely utilized in machine learning for regression and optimization tasks. However, these models are often associated with high computational costs, with expenses escalating at a rate of O(n^3) for a dataset of 'n' samples. While existing sparse approximation methods have been successful in significantly reducing these costs, in some cases even to as low as $$O(n)$$, there are still substantial gaps in the analytical bounds on the error due to approximation. In this research, we aim to bridge this gap by introducing novel confidence intervals for the Nyström method and the sparse variational Gaussian process (SVGP) approximation method. These intervals are established through new interpretations of the approximate (surrogate) posterior variance of the models. The result is improved performance bounds in both regression and Bayesian optimization problems, providing a more robust and efficient approach to machine learning applications.

