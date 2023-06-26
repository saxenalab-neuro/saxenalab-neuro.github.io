---
title: "Saxena Lab - Research"
layout: textlay
excerpt: "Saxena Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

We are broadly interested in topics on the interface of statistical inference, recurrent neural networks, control theory, and neuroscience.


**BRAIN INITIATIVE R01: ELUCIDATING PRINCIPLES OF SENSORIMOTOR CONTROL USING DEEP LEARNING.**
How do distributed neural circuits drive purposeful movements from the complex musculoskeletal system? This understanding and characterization will be critical towards the application of principled neurostimulation to specific brain regions to study the effect of neural circuit perturbations on behavior, and conversely towards predictions of the neural activity during perturbations in the behavior.

Breakneck advances in hardware and machine learning techniques have led to vast improvements in our ability to record and model large-scale multi-regional neural data. Our broad research goal is to advance the current state-of-the-art for modeling the neural control of movements by incorporating large-scale measurements and biological constraints into theoretical models of sensorimotor control.

To that end, we are developing biologically-inspired goal- and data- driven artificial intelligence methods to elucidate the neurodynamical basis of sensorimotor control. Using these tools, we hope to elucidate principles of sensorimotor control by incorporating recorded neural data in succinct and interpretable biologically-inspired models of the relationships between the measured biological data and the corresponding behavior.

This is a critical step towards (a) elucidating the computational role of neural activity from different brain regions in controlling complex behavior, (b) allowing us to further refine theoretical models of movement generation based on data, and (c) understanding where and how to stimulate the brain in order to efficiently apply neurostimulation for achieving desired behavior. 


**NSF COLLABORATIVE GRANT: ROLE OF SPONTANEOUS MOVEMENTS DURING DECISION-MAKING.** 
Cognitive tasks such as decision-making are performed by different subjects in different ways. An important manifestation of this subject-to-subject variability is through spontaneous movements during task performance. For example, people may tap the floor or move their eyes while learning a cognitive task; similarly, mice display idiosyncratic whisker, facial, or other movements.

Since both spontaneous movements and cognitive tasks modulate cortical activity, modeling and interpreting neural activity during decision-making is a major challenge. Deciphering the function and quantifying the neural origin of spontaneous movements while explicitly modeling individual neural dynamics is a crucial first step in understanding the neural basis of cognitive behaviors. Elucidating the role of spontaneous movements in cognition will also be important for assessing and developing novel therapies for neurobehavioral disorders such as attention deficit hyperactivity disorder.

It has not been possible to fully understand large-scale neural and behavioral data during cognitive tasks because neural activity is strongly modulated by movements during the task, and the effect of spontaneous, uninstructed movements on learning and cognition is not well understood. A significant challenge in disentangling the neural dynamics related to movements from those related to cognitive tasks is the presence of subject-to-subject variability. Traditionally, the variability is resolved by focusing on the representations that are present across a large number of subjects. In contrast, we want to explicitly model spontaneous movements and subject-to-subject variability by decoupling it from the across-subject part of the task. For this, we plan to leverage across-subject similarity in neural activity in mice by learning subject-independent dynamical models, while separately quantifying subject-specific dynamics.

Furthermore, the next generation of neurostimulation algorithms should not require extensive training on each subject. For this goal, we will use a trained across-subject model as the initial model for new subjects, while refining it further with individual data. This transfer learning approach will lead to effective model-based control strategies to design closed-loop neurostimulation. In an integrative computational and experimental approach, these models will be used to investigate the contribution of high-dimensional cortical activity to spontaneous movements and cognitive tasks.

**INTERPRETABLE DIMENSIONALITY REDUCTION OF NEURAL POPULATION ACTIVITY, AND DECODING ITS RELATIONSHIP TO HIGH-DIMENSIONAL BEHAVIOR**
![]({{ site.url }}{{ site.baseurl }}/images/respic/LocaNMF.png){: style="width: 250px; float: left; margin: 0px  10px"}
Dimensionality reduction methods for neural population activity are becoming essential with the advent of novel recording techniques that can simultaneously record the activity of thousands of neurons in the brain [1]. While recording from multiple regions of the brain, how does one best incorporate prior information about anatomical regions while accurately representing the data? Widefield calcium imaging methods offer a global view of the activity of the mouse dorsal cortex, with temporal resolution of around 30Hz. In order to study inter-areal interactions across multiple recording days and multiple subjects, we need to transform these signals into a common subspace while respecting anatomical region specificity. To perform such interpretable dimensionality reduction, we developed LocaNMF (Localized semi-Nonnegative Matrix Factorization), an efficient algorithm to robustly decompose widefield calcium activity into region-based components [2]. Using LocaNMF, we analyzed the neural correlates of task and behavior variables across mice and revealed, for the first time, that the inter-areal correlations across mice are very similar while the mice are performing the same task. We also developed efficient dimensionality reduction and segmentation methods for mouse behavioral videos into ‘behavioral syllables’, across different recording sessions and subjects. These methods comprise Behavenet, a behavioral analysis toolbox [3], using which we can now efficiently decode the relationship between the multi-regional neural activity and the ongoing behavior.

[1] Saxena S., Cunningham J.P. “Towards the Neural Population Doctrine” Current Opinion in Neurobiology, vol. 55, 2019.

[2] Saxena S., et al. “Localized semi-nonnegative matrix factorization (LocaNMF) of widefield calcium imaging data.” PLOS Computational Biology, 2020. Featured on the cover page!

[3] Batty E., Whiteway M., Saxena S., et al. “BehaveNet: nonlinear embedding and Bayesian neural decoding of behavioral videos” Advances in Neural Information Processing Systems (NeurIPS), 2019.

**COMPUTATIONAL PRINCIPLES UNDERLYING SPEED CONTROL IN THE PRIMARY MOTOR CORTEX**
How do we make the same movement but faster? Getting a clear answer to this question will help us design neuroprosthetic devices that can flexibly generate movements at different speeds. In a collaboration with Mark Churchland, we trained recurrent neural networks (RNNs) to directly generate the muscle activity during cycling movements at different speeds (experimental data collected in Mark Churchland’s laboratory). Surprisingly, we find that the networks made qualitative and quantitative predictions for the neural activity in the primary motor cortex of non-human macaques. We examine differences in the dynamics displayed by neural and muscle signals during movement at different speeds, using both computational and theoretical models.

Saxena S., Russo A., Cunningham J., Churchland M. “Network principles predict motor cortex population activity across movement speeds” eLife, 2022.

**FUNDAMENTAL LIMITATIONS OF THE SENSORIMOTOR CONTROL SYSTEM**
Is there a limit to how fast we can move? We examined the fundamental limitations of the sensorimotor control system, specifically while tracking fast movements. The ability to move fast and accurately track moving objects is constrained by the biophysics of neurons and dynamics of the muscles involved. Yet, the corresponding tradeoffs between these factors and tracking motor commands have not been rigorously quantified. We use feedback control principles to identify performance limitations of the sensorimotor control system to track fast periodic movements [1]. Moreover, given neural trajectories in the motor and premotor cortices of a nonhuman primate during complicated reach and grasp behaviors, we can learn these systems-level models accurately and efficiently [2]. This body of work has important implications in sensorimotor control. For example, if the primary motor cortex is compromised due to disease or damage, the theory suggests ways to manipulate muscle dynamics by adding the necessary compensatory forces using an assistive neuroprosthetic device to restore motor performance and, more important, fast and agile movements. Just how one should compensate can be informed by theory developed in [1].

[1] Saxena S., Sarma S.V., Dahleh M. “Performance Limitations in Sensorimotor Control: Trade-offs between Neural Computing and Accuracy in Fast Tracking.” Neural Computation, 2020.

[2] Saxena S., D’Aleo R., Schieber M., Dahleh M., Sarma S.V. “Reconstructing Neural Activity and Kinematics Using a Systems-Level Model of Sensorimotor Control” Proceedings of the IEEE Engineering in Medicine and Biology Conference, 2018.

**DEVELOPING ALGORITHMS FOR REAL-TIME DECODING OF NEURALLY-ENCODED SIGNALS, THAT ENSURE STABILITY IN CLOSED LOOP**
Decoding the digital signal that is transmitted by the neurons in the motor cortex to the muscles benefits the design of reliable prosthetics for rapid movements in uncertain environments. To that end, we developed a non-linear decoder for the neuronal ‘intent of movement’ signal which converges to the desired movement in the presence of neuronal encoding [1]. We also derived conditions for the stability of the movement generation in the presence of feedback as a function of the bandwidth of the movement and biophysical parameters of the neurons and the muscle [2]. The research can be applied towards a Brain-Machine Interface to drive a prosthetic or a compensatory device in a closed loop system involving visual and sensory feedback.

[1] Saxena S., Dahleh M. “Real-Time Decoding of an Integrate and Fire Encoder.” Advances in Neural Information Processing Systems (NIPS), 2014.

[2] Saxena S., Dahleh M. “Analyzing the Effect of an Integrate and Fire Encoder and Decoder in Feedback.” Proceedings of 53rd IEEE Conference on Decision and Control (CDC), 2014.

**INVESTIGATING THE ROLE OF BASAL GANGLIA NEURONS IN MOVEMENT GENERATION AND THEIR MODULATION DUE TO DEEP BRAIN STIMULATION (DBS)**
We performed an in-depth quantitative analysis of the firing pattern of the Globus Pallidus Internus (GPi) nuclei within the basal ganglia. These neurons relay information between the somatosensory and the motor cortex, and are responsible for the planning of movement related activity. Deep brain stimulation at high frequencies applied to these neurons during parkinson’s disease significantly alleviates motor symptoms, but the underlying mechanism is not yet fully known. We developed data-driven point process spiking models to quantify the effect of an input spike train on an output spike train, and applied this approach by modeling the GPi neurons as receiving inputs from their own history, the spike train of the Globus Pallidus externus neurons, and the sequence of DBS pulses [1]. We found that high frequency stimulation (as opposed to low frequency stimulation) to the subthalamic nucleus (STN) affects these neurons in a therapeutic way due to the positioning of the GPi neurons in a recurrent loop. We also modeled the oscillatory activity of the GPi neurons while the subjects were performing a direction-related motor task, and found that the occurrence of gamma oscillations is stronger during the planning of movement in directionally tuned neurons, whereas the occurrence of beta oscillations is stronger during the remainder of the trial [2].

We also developed a number of methods to aid these scientific analyses. Typically, one may record from a number of neurons in a specific area while the subject performs a task. The selection of task relevant neurons to model is an important step, and we developed a novel step-wise method to do so [3]. Moreover, groups of neurons may be acting together to produce a certain output, i.e. they may have the same input-output functionality. We developed a novel method to isolate these groups in recorded populations by building aggregate models of populations of neurons [4]. These methods can be applied to analyze a large variety of neuronal populations to build efficient models that allow us to discover scientific mechanisms.

[1] Saxena S. et al., “Point Process Models show Temporal Dependencies in Basal Ganglia Nuclei under Deep Brain Stimulation.” Proceedings of the IEEE Engineering in Medicine and Biology Conference, 2010.

[2] Saxena S. et al., “Modulations in Oscillatory Activity of Globus Pallidus internus Neurons During a Directed Hand Movement Task – A Primary Mechanism for Motor Planning.” Frontiers in Systems Neuroscience, 2019

[3] Kahn K., Saxena S., Eskandar E.N., Thakor N., Schieber M., Gale J.T., Averbeck B., Eden U. and Sarma S.V. “A Systematic Approach to Selecting Task Relevant Neurons.” Journal of Neuroscience Methods, 2015.

[4] Saxena S., Santaniello S., Gale J.T., Montgomery E. and Sarma S.V. “Aggregate Input-Output Models of Neuronal Populations.” IEEE Transactions on Biomedical Engineering, vol. 59, 2012.