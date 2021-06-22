spavs

spavs is an R package implementing a stochastic partitioning method to relate two high-dimensional data sets using a mixture of regression models with variable selection (Monni and Tadesse, 2009).  The package provides functions to draw posterior configurations and to calculate posterior probabilities. 

Reference: 

S. Monni and M.G. Tadesse. A stochastic partitioning method to associate high-dimensional responses and covariates. 
Bayesian Analysis, 4: 413-436, 2009.
https://doi.org/10.1214/09-BA416

Installation

After downloading the package locally, it can be installed using the following commands:

install.packages(“devtools”)
install.packages(“spavs”, repos=NULL, type=“source”)

Alternatively, it can be installed directly from GitHub using the commands

if(!require(remotes)) install.packages("remotes")
remotes::install_github(“stefanomonni/spavs”)
