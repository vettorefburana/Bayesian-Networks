# Bayesian-Networks

Inference on coronary artery desease data using bayesian networks

The Rmarkdown script in ```R``` performs the following tasks: 

1) Describe the dataset 
2) Identify a blacklist
3) Learn the optimal structure of the bayesian network using score-based, constraint-based and hybrid methods, as well as model averaging
4) Perform inference using bayesian networks
5) Perform inference using a naive bayesian and a tree-augmented naive bayesian classifier

A Dockerfile for running RStudio Server has been added to the repository to ensure reproducibility. See https://github.com/vettorefburana/Run-Rstudio-Server-from-Docker for instructions on how to run the Docker container.


**References:** 

Højsgaard, S., Edwards, D., & Lauritzen, S. (2012). Graphical models with R. Springer Science & Business Media.
Scutari, M., & Denis, J. B. (2014). Bayesian networks: with examples in R. CRC press.
