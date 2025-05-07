---
title: "Analytics, Data Science, And AI"
permalink: "/DataScience/"
layout: page
---

# 📊 Analytics, Data Science, and AI  
_Projects in Machine Learning & Applied Data Science_  
**Durham University & MIT Applied Data Science Program**

This repository showcases hands-on data science projects completed during my studies at Durham University and the MIT Applied Data Science Program. Each project demonstrates key data science skills—data cleaning, modeling, visualization, and interpretation—across multiple domains such as finance, genetics, affective computing, and natural language processing.

> ⚠️ *Some original datasets used are not publicly available due to licensing restrictions.*

---

## 🔹 Affective AI: Facial Emotion Recognition

![Face](/assets/face.png)

**[Facial Emotion Recognition Project](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/c7b8338f8652429e9c0ba01395e977b079f8055f/Affective_AI_Project.html)**  
A deep learning model built with TensorFlow and Keras to classify facial emotions (happy, sad, neutral, surprise) using a dataset of over 20,000 images.

- Achieved **80.02% accuracy**.
- Implemented dropout, early stopping, and data augmentation.
- 📄 [Read Full Report (PDF)](https://github.com/Amberisfree/data-science-and-analytic/blob/d1c61ebed36a1940e0723951de937b0edf4e2b6c/Deeo%20learninig%20and%20Affective%20Computing/Final%20Submission.pdf)

---

## 🔹 Regression Analysis on Gene Expression

![Gene](/assets/gene.png)

**[Gene Expression Regression Report](https://github.com/Amberisfree/data-science-and-analytic/blob/d1c61ebed36a1940e0723951de937b0edf4e2b6c/regression%20analysis%20on%20gene%20expression/reg_sum.pdf)**  
Explored regression methods for risk factor identification across thousands of genes.

- Used **Lasso Regularization**, **PCA**, and cross-validation to reduce dimensionality.
- Applied non-parametric smoothing (locopoly, B-spline, additive models).
- Evaluated models using R², residual diagnostics, and bootstrap CI.

---
## 🔹 Finance: Personal Loan Classification

![Finance](/assets/finance.png)

**[Loan Classification Analysis](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/main/Bank_loan_Analysis/bank_loan.html)**  
Classification model to predict which liability customers are likely to accept a personal loan offer.

- Techniques: decision trees, bagging, boosting, random forest.
- Reduced **false negative rate from 0.13 to 0.08** using MLR3 threshold tuning.
- Identified variable correlations for client segmentation.

---
## 🔹 Unsupervised Learning: Generative Models

![Generative](/assets/generative.png)

**[Generative Modeling & Clustering](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/main/UL%20ASML/UL-Summative.html)**  
Used Kernel Density Estimation and Gaussian Mixture Models to identify latent clusters in the data.

- Synthesized new data points from fitted distributions.
- Clustering via Expectation-Maximization (EM).
- Focused on High Density Regions.

---

## 🔹 Shakespeare Network & Text Analysis

![Hamlet](/assets/hamlet.png)

**[Hamlet Character Network](https://nbviewer.org/github/Amberisfree/data-science-and-analytic/blob/main/Hamlet%20Network%20Analysis/Hamlet%20character%2002.ipynb)**  
Analyzed character relationships in *Hamlet* through dynamic network graphs.

- Built a graph from lines spoken per act.
- Applied community detection to trace plot evolution and key figures.

---
### 🧠 Skills Highlighted

- Data Cleaning & Preprocessing  
- Supervised & Unsupervised Learning  
- Dimensionality Reduction  
- Deep Learning with CNNs  
- Network & Text Mining  
- Visualization & Reporting  

---

Feel free to explore the notebooks and reports. If you'd like to collaborate or have questions, feel free to [connect with me](mailto:youremail@example.com)!



## 1. Finance Data and Decision Tree Classification Analysis

![Finance](/assets/finance.png)

* [Personal Loan Analysis](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/main/Bank_loan_Analysis/bank_loan.html)
* The classification goal is to predict the likelihood of a liability customer buying personal loans. Our bank wants a new marketing campaign; so that we need information about the correlation between the variables given in the dataset. The objective of this analysis is to utilize finance data to gain insights and make informed decisions in classifying our clients into our banks’ potential candidates for selling personal loans in the near future.
* Explored tree algorithms and ensembled methods, such as bagging, boosting, and random forests
* Anaylzed its ROC CURVE and tuned its decision threshold to reduced false negative rate from 0.13 to 0.08 powered by MLR3




## 2. Affective AI and Facial Emotion Recognition with Deep Learning
![Face](/assets/face.png)

* [Facial Emotion Recognition](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/c7b8338f8652429e9c0ba01395e977b079f8055f/Affective_AI_Project.html): Developed an image-processing model to classify facial emotions accurately, such as sad, happy, neutral, and surprise from 20000+ dataset using convolutional neural network and achieved 80.02 accuracy.
* RePerformed Drop out, data augmentation, and early stopping to fine-tune the convolutional neural network powered by Tensorflow and Keras
* [Report](https://github.com/Amberisfree/data-science-and-analytic/blob/d1c61ebed36a1940e0723951de937b0edf4e2b6c/Deeo%20learninig%20and%20Affective%20Computing/Final%20Submission.pdf)

## 3. Regression Analysis on Gene Expression Profiles

![Gene](/assets/gene.png)

* [Regression Anaysis](https://github.com/Amberisfree/data-science-and-analytic/blob/d1c61ebed36a1940e0723951de937b0edf4e2b6c/regression%20analysis%20on%20gene%20expression/reg_sum.pdf)
* Performed Lasso Reularization, cross-validation, and PCA to do risk factor selection and reduced 7000 genes to only 17 dimesion.
* Implemented non-parametric smoothing techniques, such as locopoly, B-spline,and Additive model, to make fewer assumptions than linear regression.
* Used residaul diagnostic and r-squared to assesss regressors' and data's fitness and bootstrap confidence interval to effectively quantify the uncertainty of our estimated parameters.

## 4. Unsupervised Learning: Kernel Density Estimation and Gaussian Mixture Model

![Generative](/assets/generative.png)

* [Generative Method for clustering](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/main/UL%20ASML/UL-Summative.html):Synthesized new data by sampling from the generative model  
* Clustering based on EM algorithm from the estimated probability Distribution
* High Density Region


## 5. Network and Text Analysis: Shakespeare Network Analysis

![Hamlet](/assets/hamlet.png)

*  [Investigation into a time-varying Hamlet network](https://nbviewer.org/github/Amberisfree/data-science-and-analytic/blob/main/Hamlet%20Network%20Analysis/Hamlet%20character%2002.ipynb): Build a network of relationship between characters based on a player’s lines within each act 
* Community Detection: Identify Key figures in Evolution of the plot and Detect personas within each Community





