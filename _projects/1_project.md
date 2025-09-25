---
layout: page
title: Daily PM25 Prediction
description: Predicting PM2.5 Concentration in Under-Monitored Urban Areas Using Satellite-Derived Predictors and Machine Learning
img: assets/img/PM25_Residual.png
importance: 1
category: work
related_publications: false
---

📄 [Read the Paper (PDF)]({{ '/assets/pdf/PM25.pdf' | absolute_url }})

Sub-Saharan Africa faces severe air quality challenges, yet ground monitoring of PM<sub>2.5</sub> is limited. This study applied machine learning models to estimate daily PM2.5 levels in Nairobi, Kenya using satellite-derived atmospheric and meteorological. The Support Vector Regressor and Extreme Gradient Boosting Regressor achieved the best performance, showing the potential of satellite–machine learning integration for improving air quality monitoring in under-monitored regions.

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
    On the left and middle, the models captured well the monthly (left) and daily (middle) trends in PM<sub>2.5</sub> pollution. 
    On the right, the binned residual analysis evaluates both bias and overall predictive accuracy across low, medium and high pollution levels. 
    The left axis shows mean bias error (MBE) in predicting low, medium and high PM<sub>2.5</sub> concentrations, where negative values indicate underprediction and positive values indicate overprediction. 
    The right axis reports the prediction errors (RMSE and MAE).
</div>
