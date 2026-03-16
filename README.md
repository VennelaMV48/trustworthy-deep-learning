# 🧠 Trustworthy Deep Learning

Deep learning experiments focusing on **trustworthy AI principles**, including fairness, robustness, and explainability in machine learning models.

This project explores how machine learning systems can be designed to produce **reliable, transparent, and ethically responsible predictions**.



## Problem

Modern machine learning systems can produce highly accurate predictions, but they may also exhibit:

- bias in decision making
- vulnerability to noisy inputs
- lack of transparency

These issues raise concerns about the **trustworthiness of AI systems** in real-world applications.

Developing reliable models requires evaluating more than just accuracy.



## Project Objectives

This project investigates techniques for improving the reliability of deep learning models by focusing on three key aspects:

- fairness
- robustness
- explainability

The goal is to evaluate how model behaviour changes when these factors are considered during training and evaluation.



## Model Training Pipeline

<p align="center">
<img src="model_pipeline.png" width="600">
</p>

The experimental workflow includes:

1. dataset preprocessing
2. model training
3. fairness evaluation
4. robustness testing
5. explainability analysis

This pipeline allows systematic evaluation of model reliability.



## Fairness Evaluation

<p align="center">
<img src="fairness_evaluation.png" width="500">
</p>

Fairness analysis examines whether the model produces consistent predictions across different groups in the dataset.

Metrics evaluated include:

- prediction parity
- error rate comparison
- group performance differences

This helps identify potential **bias in model behaviour**.



## Robustness Testing

The model was evaluated under different perturbation scenarios to analyse stability.

Examples of robustness tests:

- noisy input data
- slight feature variations
- adversarial-like perturbations

These experiments assess whether the model maintains stable predictions under uncertainty.



## Explainability Analysis

<p align="center">
<img src="explainability_results.png" width="500">
</p>

Explainability techniques were used to interpret model predictions.

Methods explored include:

- feature importance analysis
- model interpretation techniques
- visual explanation of predictions

These approaches help make model decisions more transparent.



## Tools Used

| Tool | Purpose |
|--|--|
Python | model development |
PyTorch | deep learning training |
Scikit-learn | evaluation metrics |
Jupyter Notebook | experimentation |



## Key Insights

Experiments showed that:

- model performance must be evaluated beyond accuracy
- fairness metrics can reveal hidden bias
- explainability techniques improve interpretability
- robustness testing highlights model stability limitations

These insights contribute to the development of **more reliable AI systems**.



## Future Work

Future extensions could include:

- fairness-aware model training
- adversarial robustness methods
- improved model explanation techniques
- evaluation across larger datasets



## Author

Vennela Mangala Venkatesha  
Master of Artificial Intelligence  
University of Auckland
