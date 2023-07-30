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

<img src="{{ "/assets/img/RL_img.png" | absolute_url }}" alt="{{ Image }}"  style="width:200px;height:200px;" />

Reinforcement Learning (RL) has shown great empirical success in various settings with complex models and large state-action spaces. However, the existing analytical results typically focus on settings with a small number of state-actions or simple models, such as linearly modeled state-action value functions. To derive RL policies that efficiently handle large state-action spaces with more general value functions, some recent works have explored nonlinear function approximation using kernel ridge regression. In this <a href="https://arxiv.org/abs/2306.07745" target="_blank" rel="noopener"> paper </a>, we introduce a kernel based optimistic least-squares value iteration policy that achieves order optimal regret bounds for a common class of kernels. Our results show a significant improvement over the state of the art.


## Shortest Path Diffusion

<img src="{{ "/assets/img/SPD.png" | absolute_url }}" alt="{{ Image }}"  style="width:200px;height:200px;" />

Denosing diffusion models have shown significant advancements in image generation. We introduce a novel approach where images are perturbed with noise along the shortest path from the distribution of images to the distribution of noise. We propose the Fisher metric for the path length, measured in the space of probability distributions. Referred to as Shortest Path Diffusion (SPD), this approach uniquely determines the complete spatiotemporal structure of the corruption process. We demonstrate that SPD surpasses strong baseline methods without requiring any hyperparameter tuning. 
