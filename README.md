# Uncertainty-XAI-CNN

Research-oriented project for analyzing the relationship between predictive uncertainty and explainability methods in convolutional neural networks.

---

# Scientific Question

Can explainability methods provide stable and meaningful explanations when a neural network is uncertain about its predictions?

This project investigates the relationship between:

* predictive confidence;
* Monte Carlo Dropout uncertainty estimation;
* attribution-based explainability methods;
* similarity between explanation maps.

The main objective is to evaluate whether uncertainty correlates with the consistency and reliability of neural network explanations.

---

# Project Overview

The notebook implements:

* CNN image classification;
* Monte Carlo Dropout uncertainty estimation;
* Grad-CAM visualization;
* Integrated Gradients attribution;
* similarity analysis between explanation methods;
* statistical evaluation of attribution consistency.

The project focuses on interpretable and trustworthy AI research.

---

# Methods Used

## Neural Network

* Convolutional Neural Network (CNN)

## Uncertainty Estimation

* Monte Carlo Dropout

## Explainability Methods

* Grad-CAM
* Integrated Gradients

## Evaluation Metrics

* Cosine similarity
* Attribution consistency analysis
* Confidence vs uncertainty comparison

---

# Obtained Results

The experiments demonstrated several important observations:

1. High-confidence predictions generally produced more stable and concentrated attribution maps.

2. Predictions with higher uncertainty often generated noisier and less consistent explanations.

3. Monte Carlo Dropout successfully identified uncertain predictions and helped distinguish unstable model behavior.

4. Similarity metrics between explanation methods revealed correlations between prediction confidence and attribution agreement.

5. Explainability methods behaved differently depending on the confidence level of the neural network.

These results suggest that interpretability quality may depend on predictive uncertainty.

---

# Conclusion

This project demonstrates that uncertainty estimation and explainability should not be treated as independent components of trustworthy AI systems.

The experiments indicate that:

* uncertainty affects explanation stability;
* confident predictions tend to produce more reliable explanations;
* attribution consistency can be used as an additional signal for model reliability.

The work supports the idea that explainability methods should be evaluated together with uncertainty estimation techniques.

---

# Possible Improvements

Future development directions include:

* support for ResNet and EfficientNet architectures;
* additional uncertainty estimation methods;
* calibration metrics;
* SHAP and LIME explainability methods;
* larger benchmark datasets;
* quantitative evaluation pipeline;
* reproducibility improvements;
* modular project structure;
* web-based visualization dashboard.

---

# Technologies

* Python
* PyTorch
* NumPy
* Matplotlib
* Captum
* Scikit-learn

---

# Future Goal

The long-term goal of this project is to build a small experimental framework for uncertainty-aware explainable AI research.

---

# Repository Structure

Currently the project is provided as a research notebook prototype.

Future versions will include:

* modular source code structure;
* training scripts;
* experiment configuration system;
* reusable evaluation pipeline.

---

# Author

Research project focused on uncertainty-aware explainable AI and trustworthy neural networks.

---

## Academic Context

This project originated as an early research direction for a bachelor's/master's thesis focused on uncertainty-aware explainable AI systems.

Although the final thesis topic evolved in a different direction, the experimental work developed during the research process was preserved and published as an independent project.
