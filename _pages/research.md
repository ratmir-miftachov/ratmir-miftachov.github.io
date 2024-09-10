---
layout: page
title: Research
permalink: /research/
description: 
nav: true
---

#### **Work-in-progress**

**Title:** Risk Premia in the Bitcoin Market 
<br>
**Co-Authors:** Caio Almeida, Maria Grith, Zijin Wang 

**Abstract:** 
We adopt options to analyze risk premia in the Bitcoin market. By decomposing the index risk premium into different segments of the return space, we find that negative returns between -60\% and -20\% explain one-third of the total Bitcoin premium (BP). In contrast to the results for the S\&P 500 market, where moderately negative returns explain 70\% of the equity premium, this result challenges the assumptions of traditional macro-finance models, including those based on long-run risk, habit formation, disaster risk, and disappointment aversion. By clustering data using a collection of risk-neutral densities, we find that risk premia vary over time depending on market conditions, and the risk-neutral variance arises as the leading state variable characterizing these clusters. During low-volatility market states, (i) investors’ appetite for upside risk increases, raising the BP attributable to positive returns; (ii) they exhibit heightened sensitivity to negative returns, steepening the pricing kernel; and (iii) their concern for variance risk intensifies.

**Title:** Early Stopping for Regression Trees
<br>
**Co-Authors:** Markus Reiss



#### **Working-paper**

**Title:** [Shapley Curves: A Smoothing Perspective](https://www.tandfonline.com/doi/full/10.1080/07350015.2024.2365781)  
**Co-Authors:** Georg Keilbar, Wolfgang Härdle 

**Abstract:** 
This paper fills the limited statistical understanding of Shapley values as a variable importance measure from a nonparametric (or smoothing) perspective. We introduce population-level <i>Shapley curves</i> to measure the true variable importance, determined by the conditional expectation function and the distribution of covariates. Having defined the estimand, we derive minimax convergence rates and asymptotic normality under general conditions for the two leading estimation strategies. For finite sample inference, we propose a novel version of the wild bootstrap procedure tailored for capturing lower-order terms in the estimation of Shapley curves.
Numerical studies confirm our theoretical findings, and an empirical application analyzes the determining factors of vehicle prices.

Published at Journal of Business & Economic Statistics

#### **Software**

**Title:** [Python Library for Early Stopping Methods](https://earlystop.github.io/EarlyStopping/)  
**Co-Authors:** Laura Hucker, Bernhard Stankewitz, Eric Ziebell

**Abstract:** 
For iterative estimation procedures applied to statistical inverse problems, it is necessary to choose a suitable iteration index to avoid under- and overfitting. Classical model selection criteria can be prohibitively expensive in high dimensions. In the last few years, it has been shown for several regularisation methods that sequential early stopping can achieve statistical and computational efficiency by halting at a data-driven index depending on previous iterates only.  We are in the process of implementing these residual-based stopping rules for different algorithms like Landweber, conjugate gradients and L2-boosting in our Python package "EarlyStopping". In the future, we will include early stopping for decision trees. We demonstrate its functionality based on several simulation examples.
