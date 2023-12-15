# Selected Projects


## Kernel-based RL

<img src="{{ "/assets/img/RL_img.png" | absolute_url }}" alt="{{ Image }}"  style="width:250px;height:250px;" />

Reinforcement Learning (RL) has shown great empirical success in various settings with complex models and large state-action spaces. However, the existing analytical results typically focus on settings with a small number of state-actions or simple models, such as linearly modeled state-action value functions. To derive RL policies that efficiently handle large state-action spaces with more general value functions, some recent works have explored nonlinear function approximation using kernel ridge regression. In this <a href="https://arxiv.org/abs/2306.07745" target="_blank" rel="noopener"> paper</a>, we introduce a kernel-based optimistic least-squares value iteration policy that achieves order optimal regret bounds for a common class of kernels (that includes Matérn family and Neural Tangent kernel). Our results show a significant improvement over the state of the art.


## Shortest path diffusion

<img src="{{ "/assets/img/SPD.png" | absolute_url }}" alt="{{ Image }}"  style="width:250px;height:250px;" />

Denosing diffusion models have shown significant advancements in image generation. We introduce a novel approach where images are perturbed with noise along the shortest path from the distribution of images to the distribution of noise. We propose the Fisher metric for the path length, measured in the space of probability distributions. Referred to as <a href="https://arxiv.org/abs/2306.00501" target="_blank" rel="noopener"> Shortest Path Diffusion (SPD)</a>, this approach uniquely determines the complete spatiotemporal structure of the corruption process. We demonstrate that SPD surpasses strong baseline methods without requiring any hyperparameter tuning. 


## Convergence rate of Nyström method and SVGP

<img src="{{ "/assets/img/gp_regression_plot.png" | absolute_url }}" alt="{{ Image }}"  style="width:250px;height:250px;" />

Kernel ridge regression and Gaussian processes are widely utilized in machine learning for regression and optimization tasks. However, they often come with high computational demands. While existing sparse approximation methods have effectively cut down these costs, there are still substantial gaps in the analytical bounds on the error due to approximation. In this research project at MediaTek Research, in collaboration with Jonathan Scarlett at the National University of Singapore, we bridged this gap by introducing novel confidence intervals for the Nyström method and the sparse variational Gaussian process (SVGP) approximation method. These intervals are established through new interpretations of the approximate (surrogate) posterior variance of the models. The result is improved performance bounds in both regression and Bayesian optimization problems, providing a more robust and efficient approach to machine learning applications. Our <a href="https://proceedings.mlr.press/v162/vakili22a.html" target="_blank" rel="noopener"> work</a> was accepted at ICML 2022 as a Spotlight presentation. 

## Wireless channel modelling

<img src="{{ "/assets/img/glob3.png" | absolute_url }}" alt="{{ Image }}"  style="width:300px;height:165px;" />

We have introduced a new approach to wireless channel modeling and sampling using generative diffusion models. Compared to the existing GAN-based approaches, the diffusion model offers stable training and generates diverse and high-fidelity samples from the true channel distribution. <a href="https://arxiv.org/abs/2308.05583" target="_blank" rel="noopener"> Our work </a> also demonstrates the feasibility of transfer learning, showcasing the potential of our approach to model real-world channels using limited data.
