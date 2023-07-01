---
layout: page
title: Cognitive Underpinnings of Motor Control 
description: Time-Varying Recurrent Neural Network (TV-RNN)
img: assets/img/tvrnn/ov.png
importance: 1
category: Current Interests
---
Shifts in data distribution across time can strongly affect early classification of time-series data. When decoding behavior from neural activity, early detection of behavior may help in devising corrective neural stimulation before the onset of behavior. Recurrent Neural Networks (RNNs) are common models for sequence data. However, standard RNNs are not able to handle data with temporal distributional shifts to guarantee robust classification across time. To enable the network to utilize all temporal features of the neural input data, and to enhance the memory of an RNN, we propose a novel approach: RNNs with time-varying weights, here termed Time-Varying RNNs (TV-RNNs). These models are able to not only predict the class of the time-sequence correctly but also lead to accurate classification earlier in the sequence than standard RNNs. We focus on early sequential classification of brain-wide neural activity across time using TV-RNNs applied to a variety of neural data from mice and humans, as subjects perform motor tasks. We explore the contribution of different brain regions on behavior classification using SHapley Additive exPlanation (SHAP) value, and find that the somatosensory and premotor regions play a large role in behavioral classification[1][2].

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tvrnn/ov.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

[1] Mitelut, C., Zhang, Y.G, Sekino, Y., Boyd, J., Bolanos, F., Swindale, N. V., Silasi, G., Saxena, S.*, Murphy, T. H.* "Mesoscale cortex-wide neural dynamics predict self-initiated actions in mice several seconds prior to movement." eLife, 2022.

[2] Zhang, Y.G, Mitelut, P., Arpin, J., Vaillancourt, P., Murphy, T. H.*, Saxena, S.*, "Behavioral Classification of Sequential Neural Activity Using Time Varying Recurrent Neural Networks" biorxiv, 2023.
