# ClusterPredictiveLURM

# Estimation and Inference in Cluster-Based Predictive Local Unit Root Regression using Permutation Methods

## Description (Work-in-Progress)

### Drafted December 2021

In this R project we extend the methodology proposed in the R package [‘PermLURM’](https://github.com/christiskatsouris/PermLURM) and ['ivxPredictive'](https://github.com/christiskatsouris/ivxPredictive)) to develop an econometric framework for estimation and inference purposes in Cluster-Based Predictive Local Unit Root Regression Models. Moreover, emphasis will be given in the estimation of covariance matrices under network or cluster dependence as well as in dealing with short-memory versus long-memory processes under abstract degree of persistence. Specifically, the framework of nonstationary predictive regression models take into consideration two important features discussed in the predictability literature: (i) the possibly highly persistent autoregressive dynamics of regressors and (ii) the strong contemporaneous correlation of regressors'innovations with those of the dependent variable. In addition we aim to investigate the presence of clustering effects both in empirical studies as well as via related asymptotic theory analy Specifically, the predictability literature has not previously given much attention to data clusters in which we have to expect that units within these clusters influence one another or are influenced by the same shocks.  

## Methodology

Notice that using conventional hypothesis testing methods can result to critical values of test statistics and the corresponding critical values to be incorrect under the presence of cluster dependence. Therefore, it is important to develop new asymptotic theory and modified test statistics to accommodate these features. 

## Key References

- Müller, U. K., & Watson, M. W. (2022). Spatial Unit Roots.

- Abadie, A., Athey, S., Imbens, G. W., & Wooldridge, J. (2017). When should you adjust standard errors for clustering? (No. w24003). National Bureau of Economic Research.

- Basu, Sumanta, and Suhasini Subba Rao (2022). "Graphical models for nonstationary time series." Annals of Statistics (forthcoming).

- Hagemann, A. (2022). "Permutation inference with a finite number of heterogeneous clusters". Review of Economics and Statistics (forthcoming).  
 
- Hagemann, A. (2017). "Cluster-robust bootstrap inference in quantile regression models". Journal of the American Statistical Association, 112(517), 446-456.

- Hansen, B. E., & Lee, S. (2019). "Asymptotic theory for clustered samples". Journal of econometrics, 210(2), 268-290.

- Krampe, J., Paparoditis, E., & Trenkler, C. (2022). Structural inference in sparse high-dimensional vector autoregressions. Journal of Econometrics.

- Krampe, J., Kreiss, J. P., & Paparoditis, E. (2021). Bootstrap based inference for sparse high-dimensional time series models. Bernoulli, 27(3), 1441-1466.

- Katsouris, C. (2021). Optimal Portfolio Choice and Stock Centrality for Tail Risk Events. arXiv preprint arXiv:2112.12031.

-  Kostakis, A., Magdalinos, T., & Stamatogiannis, M. P. (2015). "Robust econometric inference for stock return predictability". The Review of Financial Studies, 28(5), 1506-1553.
 
- Kojevnikov, D., Marmer, V., & Song, K. (2021). "Limit theorems for network dependent random variables". Journal of Econometrics, 222(2), 882-908.

- Kojevnikov, D. (2021). "The bootstrap for network dependent processes". arXiv preprint arXiv:2101.12312.

- Phillips, P. C., & Magdalinos, T. (2007). "Limit theory for moderate deviations from a unit root". Journal of Econometrics, 136(1), 115-130.

- Schennach, S. M. (2018). "Long memory via networking". Econometrica, 86(6), 2221-2248.

- Zhu, X., Pan, R., Li, G., Liu, Y., & Wang, H. (2017). Network vector autoregression. The Annals of Statistics, 45(3), 1096-1123.

- Zhu, X., Wang, W., Wang, H., & Härdle, W. K. (2019). Network quantile autoregression. Journal of econometrics, 212(1), 345-358.

- Zhu, X., & Pan, R. (2020). Grouped network vector autoregression. Statistica Sinica, 30(3), 1437-1462.


# Code of Coduct

Please note that the [ClusterPredictiveLURM](https://github.com/christiskatsouris/ClusterPredictiveLURM) R project will be released with a Contributor Code of Coduct (under construction). By contributing to this project, you agree to abide by its terms.

# Acknowledgments

The author greatfully acknowledges financial support from the [Department of Economics](http://business-school.exeter.ac.uk/about/departments/economics/) of the [Faculty of Environment, Science and Economy](https://www.exeter.ac.uk/departments/ese/) at the University of Exeter, United Kingdom. 

Christis G. Katsouris is a Lecturer in Economics at the [University of Exeter Business School](http://business-school.exeter.ac.uk/). He is also a member of the [Time Series and Machine Learning Group](https://www.personal.soton.ac.uk/cz1y20/Reading_Group/mlts-group-2022.html) at the [School of Mathematical Sciences](https://www.southampton.ac.uk/about/faculties-schools-departments/school-of-mathematical-sciences) (Statistics Division) of the University of Southampton. 

# Declarations

The author (Christis G. Katsouris) declares no conflicts of interest.

Notice that the academic research presented here is considered to be as open access to the academic and non-academic community. Therefore, we would appreciate it if appropriate acknolwedgement is given to statistical methodologies and econometric procedures developed by academic researchers and made available to the wider applied data scientist community.   

# Historical Background

> Standing on the shoulders of giants.
> 
> $\textit{''If I have been able to see further, it was only because I stood on the shoulders of giants."}$
> $- \text{Isaac Newton, 1676}$ 
