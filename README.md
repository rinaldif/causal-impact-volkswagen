## causal-impact-volkswagen

### Causal Impact Analysis on the VolksWagen Emissions Scandal

`CausalImpact` is an R package for causal inference using Bayesian structural time-series models. It implements an approach to estimate the causal effect of a designed intervention on a time series. 

The package was developed and open sourced by Google, for more information:

* Visit the project's [GitHub page](https://google.github.io/CausalImpact/)
* Read the [documentation and examples](https://google.github.io/CausalImpact/CausalImpact.html)
* Read the [research paper](https://research.google.com/pubs/pub41854.html)

### Dependencies:
```{r message = FALSE, results='asis'}
#install.packages("tseries")
library(tseries)
#install.packages("ggplot2")
library(ggplot2)
#devtools::install_github("google/CausalImpact")
library(CausalImpact)
```
