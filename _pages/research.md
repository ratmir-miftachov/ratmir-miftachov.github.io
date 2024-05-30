---
layout: page
title: Research
permalink: /research/
description: 
nav: true
---

#### **Work-in-progress**

**Title:** Risk Premiums in the Bitcoin Market 
<br>
**Co-Authors:** Caio Almeida, Maria Grith, Zijin Wang 
**Abstract:** 


**Title:** Early Stopping for Regression Trees
<br>
**Co-Authors:** Markus Reiss


#### **Working-paper**

**Title:** [Shapley Curves: A Smoothing Perspective](https://arxiv.org/pdf/2211.13289.pdf)  
**Co-Authors:** Georg Keilbar, Wolfgang Härdle 

**Abstract:** 
This paper fills the limited statistical understanding of Shapley values as a variable importance measure from a nonparametric (or smoothing) perspective. We introduce population-level <i>Shapley curves</i> to measure the true variable importance, determined by the conditional expectation function and the distribution of covariates. Having defined the estimand, we derive minimax convergence rates and asymptotic normality under general conditions for the two leading estimation strategies. For finite sample inference, we propose a novel version of the wild bootstrap procedure tailored for capturing lower-order terms in the estimation of Shapley curves.
Numerical studies confirm our theoretical findings, and an empirical application analyzes the determining factors of vehicle prices.

Accepted at Journal of Business & Economic Statistics

#### **Software**

**Title:** [Python Library for Early Stopping Methods](https://earlystop.github.io/EarlyStopping/)  
**Co-Authors:** Laura Hucker, Bernhard Stankewitz, Eric Ziebell

**Abstract:** 
For iterative estimation procedures applied to statistical inverse problems, it is necessary to choose a suitable iteration index to avoid under- and overfitting. Classical model selection criteria can be prohibitively expensive in high dimensions. In the last few years, it has been shown for several regularisation methods that sequential early stopping can achieve statistical and computational efficiency by halting at a data-driven index depending on previous iterates only.  We are in the process of implementing these residual-based stopping rules for different algorithms like Landweber, conjugate gradients and L2-boosting in our Python package "EarlyStopping". In the future, we will include early stopping for decision trees. We demonstrate its functionality based on several simulation examples.
