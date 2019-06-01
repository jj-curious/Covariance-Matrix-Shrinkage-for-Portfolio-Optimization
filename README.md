# Covariance-Matrix-Shrinkage-for-Portfolio-Optimization
Comparison of using the Ledoit-Wolf and the Oracle Approximating Shrinkage Estimators to estimate singular covariance matrices in the context of portfolio optimzation. Includes an experiment where 

**Description:**  
This notebook demonstrates how and when estimation errors of the covariance matrix occur and approaches to reduce these errors. Inspired by the work of Ledoit & Wolf - Honey, I Shrunk the Sample Covariance Matrix, the covariance matrix of historical stock returns is:
* estimated via the Ledoit-Wolf Shrinkage Estimator and the Oracle Approximating Shrinkage Estimator and
* used to compute the Markowitz' mean-variance portfolio.
* The results are then compared to the sample covariance and evaluated for 24 different time periods.  
  

**Contents:**
1. Get Stock Price Data
2. Markowitz Portfolio Optimization
3. Singular Matrix
4. Shrinkage  
  

**Note:** Sometimes github fails to load/render the juypter notebooks. In this case you can copy-paste the link from the notebook into https://nbviewer.jupyter.org/ or just access the notebook via https://nbviewer.jupyter.org/github/jj-curious/Covariance-Matrix-Shrinkage-for-Portfolio-Optimization/blob/master/Covariance_Shrinkage_Portfolio.ipynb
