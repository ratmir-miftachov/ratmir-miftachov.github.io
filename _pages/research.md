---
layout: page
title: Research
permalink: /research/
description: 
nav: true
---


#### **Publications**

**Title:** [Shapley Curves: A Smoothing Perspective](https://www.tandfonline.com/doi/full/10.1080/07350015.2024.2365781)  
**Co-Authors:** Georg Keilbar, Wolfgang Härdle 

**Abstract:** 
This paper fills the limited statistical understanding of Shapley values as a variable importance measure from a nonparametric (or smoothing) perspective. We introduce population-level <i>Shapley curves</i> to measure the true variable importance, determined by the conditional expectation function and the distribution of covariates. Having defined the estimand, we derive minimax convergence rates and asymptotic normality under general conditions for the two leading estimation strategies. For finite sample inference, we propose a novel version of the wild bootstrap procedure tailored for capturing lower-order terms in the estimation of Shapley curves.
Numerical studies confirm our theoretical findings, and an empirical application analyzes the determining factors of vehicle prices.

Published at Journal of Business & Economic Statistics


#### **Software**

**Title:** [Python Library for Early Stopping Methods](https://earlystop.github.io/EarlyStopping/index.html)  
**Co-Authors:** Laura Hucker, Bernhard Stankewitz, Eric Ziebell

**Abstract:** 
For iterative estimation procedures applied to statistical inverse problems, it is necessary to choose a suitable iteration index to avoid under- and overfitting. Classical model selection criteria can be prohibitively expensive in high dimensions. In the last few years, it has been shown for several regularisation methods that sequential early stopping can achieve statistical and computational efficiency by halting at a data-driven index depending on previous iterates only.  We are in the process of implementing these residual-based stopping rules for different algorithms like Landweber, conjugate gradients and L2-boosting in our Python package "EarlyStopping". In the future, we will include early stopping for decision trees. We demonstrate its functionality based on several simulation examples.


#### **Work-in-progress**

**Title:** Generalized Projection Flow for Regression Trees
<br>
**Co-Author:** Markus Reiß

**Abstract:** 
We introduce the early stopped regression tree estimator using a novel, fully data-driven stopping rule based on the discrepancy principle. Our framework combines the best-first search and the breadth-first search algorithm with the proposed stopping rule and unifies both. We establish an oracle inequality for the early-stopped regression tree under the original CART splitting without any smoothness assumption on the regression function. The leading term is of order $n^{-1/2}$. Thus, we encompass the previous literature's regression tree consistency results, which have a larger order and are less general in the functional class. Finally, a simulation study demonstrates that our approach achieves performance comparable to the state of the art while reducing computational costs by a factor of 10 to 20 and being more interpretable.

**Title:** Early Stopping for Random Forest Classifier
<br>
**Co-Author:** Mustafa Suman

**Abstract:** 
Extended previous work to the random forest classifier. The early stopped forest is computationally efficient, has
significantly fewer nodes, and its prediction performance is on par with the deeply grown forest.

**Title:** [Risk Premia in the Bitcoin Market](https://arxiv.org/abs/2410.15195) 
<br>
**Co-Authors:** Caio Almeida, Maria Grith, Zijin Wang 

**Abstract:** 
Based on options and realized returns we analyze risk premia in the Bitcoin market through the lens of the Pricing Kernel (PK). We identify that: 1) The projected PK into Bitcoin returns is W-shaped and steep in the negative returns region; 2) Negative Bitcoin returns account for 33% of the total Bitcoin index premium (BP) in contrast to 70% of S&P500 equity premium explained by negative returns. Applying a novel clustering algorithm to the collection of estimated Bitcoin risk-neutral densities, we find that risk premia vary over time as a function of two distinct market volatility regimes. In the low-volatility regime, the PK projection is steeper for negative returns and has a more pronounced W-shape than the unconditional one, implying particularly high BP for both extreme positive and negative returns and a high Variance Risk Premium (VRP). In high-volatility states, the BP attributable to positive and negative returns is more balanced and VRP is lower. Overall, Bitcoin investors are more worried about variance and downside risk in low volatility states. 


