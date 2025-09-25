---
layout: page
title: Daily PM25 Prediction
description: Predicting PM2.5 Concentration in Under-Monitored Urban Areas Using Satellite-Derived Predictors and Machine Learning
img: assets/img/PM25_Residual.png
importance: 1
category: work
related_publications: true
---
📄 [Read the Paper (PDF)](assets/pdf/PM25.pdf)  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PM25_monthly.png" title="monthly trend" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PM25_predicted.png" title="Actual vs Predicted" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PM25_Residual.png" title="Residual analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Binned residual analysis evaluating both bias and overall predictive accuracy across low, medium and high pollution levels. The left axis shows mean bias error (MBE) in predicting
    low, medium and high PM2.5 concentrations, where negative values indicate underprediction and positive values indicate overprediction. The right axis reports the prediction errors (RMSE and MAE).
</div>




