---
layout: page
title: Neural Response Prediction using RNN
description: Using the Steinmetz dataset, we predict the neural responses in the midbrain of a mouse based on activity from other brain areas.
img: assets/img/steinmetz.jpeg
importance: 1
category: work
related_publications:
---

This project was undertaken as the final assignment for the Deep Learning course at Neuromatch Academy. Our team trained an RNN to predict the neural responses in the midbrain using data from other brain regions. Subsequently, we utilized the latent variables from this RNN to train an SVM, aiming to predict wheel direction. We achieved commendable results in both tasks.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rnn-test.png" title="RNN Test Results" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/svm-results.png" title="SVM Prediction Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The results indicate successful predictions for both the RNN and SVM models.
</div>

### Repository
For a detailed look into our code and methodologies, check out our [GitHub repository](https://github.com/IAmirKhani/Neural-response-prediction-using-RNN/).
