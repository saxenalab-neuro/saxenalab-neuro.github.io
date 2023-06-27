---
layout: page
title: INTERPRETABLE DIMENSIONALITY REDUCTION OF NEURAL POPULATION ACTIVITY
description: AND DECODING ITS RELATIONSHIP TO HIGH-DIMENSIONAL BEHAVIOR
img: assets/img/respic/LocaNMF.png
redirect: 
importance: 3
category: Past Research
---
**INTERPRETABLE DIMENSIONALITY REDUCTION OF NEURAL POPULATION ACTIVITY, AND DECODING ITS RELATIONSHIP TO HIGH-DIMENSIONAL BEHAVIOR**
Dimensionality reduction methods for neural population activity are becoming essential with the advent of novel recording techniques that can simultaneously record the activity of thousands of neurons in the brain [1]. While recording from multiple regions of the brain, how does one best incorporate prior information about anatomical regions while accurately representing the data? Widefield calcium imaging methods offer a global view of the activity of the mouse dorsal cortex, with temporal resolution of around 30Hz. In order to study inter-areal interactions across multiple recording days and multiple subjects, we need to transform these signals into a common subspace while respecting anatomical region specificity. To perform such interpretable dimensionality reduction, we developed LocaNMF (Localized semi-Nonnegative Matrix Factorization), an efficient algorithm to robustly decompose widefield calcium activity into region-based components [2]. Using LocaNMF, we analyzed the neural correlates of task and behavior variables across mice and revealed, for the first time, that the inter-areal correlations across mice are very similar while the mice are performing the same task. We also developed efficient dimensionality reduction and segmentation methods for mouse behavioral videos into ‘behavioral syllables’, across different recording sessions and subjects. These methods comprise Behavenet, a behavioral analysis toolbox [3], using which we can now efficiently decode the relationship between the multi-regional neural activity and the ongoing behavior.

[1] Saxena S., Cunningham J.P. “Towards the Neural Population Doctrine” Current Opinion in Neurobiology, vol. 55, 2019.

[2] Saxena S., et al. “Localized semi-nonnegative matrix factorization (LocaNMF) of widefield calcium imaging data.” PLOS Computational Biology, 2020. Featured on the cover page!

[3] Batty E., Whiteway M., Saxena S., et al. “BehaveNet: nonlinear embedding and Bayesian neural decoding of behavioral videos” Advances in Neural Information Processing Systems (NeurIPS), 2019.
