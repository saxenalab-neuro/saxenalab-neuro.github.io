---
layout: page
title: Disentangled Multi-subject Behavioral Representations
description: NSF funded project
img: assets/img/funding_nsf/mice.png
importance: 4
category: Current Interests
---
[(see funding)]({{ site.url }}{{ site.baseurl }}/fundings) 
Cognitive tasks such as decision-making are performed by different subjects in different ways. An important manifestation of this subject-to-subject variability is through spontaneous movements during task performance. For example, people may tap the floor or move their eyes while learning a cognitive task; similarly, mice display idiosyncratic whisker, facial, or other movements.

Effectively modeling and quantifying behavior is essential for our understanding of the brain. Modeling behavior in naturalistic settings in social and multi-subject tasks remains a significant challenge. Modeling the behavior of different subjects performing the same task requires partitioning the behavioral data into features that are common across subjects, and others that are distinct to each subject. Modeling social interactions between multiple individuals in a freely-moving setting requires disentangling effects due to the individual as compared to social investigations. To achieve flexible disentanglement of behavior into interpretable latent variables with individual and across-subject or social components, we build on a semi-supervised approach to partition the behavioral subspace, and propose a novel regularization based on the Cauchy-Schwarz divergence to the model. Our model, known as the constrained subspace variational autoencoder (CS-VAE) [1], successfully models distinct features of the behavioral videos across subjects, as well as continuously varying differences in social behavior. Our approach vastly facilitates the analysis of the resulting latent variables in downstream tasks such as uncovering disentangled behavioral motifs [3], the efficient decoding of a novel subject's behavior, and provides an understanding of how similarly different animals perform innate behaviors [2].

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/csvae.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/funding_nsf/na.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

[1]Yi, D., Musall, S., Churchland, A. , Padilla-Coreano, N., Saxena, S., "Disentangled multi- subject and social behavioral representations through a constrained subspace variational autoencoder (CS-VAE)" eLife (To Appear), 2023.

[2]Yi, D., Saxena, S., "Neural Correlations Across Mice During Spontaneous and Task-Related Behaviors" IEEE NER, 2023

[3] Batty E., Whiteway M., Saxena S., et al. “BehaveNet: nonlinear embedding and Bayesian neural decoding of behavioral videos” Advances in Neural Information Processing Systems (NeurIPS), 2019.

