# econometrics-tutorials
Interactive Quarto tutorials for an introductory econometrics course.

**Author:** Nicolás González Raposo

| Folder | Contents |
| --- | --- |
| [exercises](exercises/) | Worksheets to complete in R and Quarto. |
| [solutions](solutions/) | Corresponding worked examples. |
| [notes](notes/) | Supplementary note on adjusted R squared. |
| [data](data/) | CEP 90 data and dictionary, and the simulated breakfast dataset. |
| [images](images/) | Original formula images. |

Requires R and [Quarto](https://quarto.org/). Install the R packages once:

```r
install.packages(c("tidyverse", "truncnorm", "lmtest", "sandwich",
                   "stargazer", "wooldridge", "nnet", "MASS", "ivreg",
                   "knitr", "rmarkdown"))
```

Render a worked example from the repository root:

```sh
quarto render "solutions/Sesion 2, Modelo lineal simple.qmd"
```

Data paths are relative to each document's folder. Worksheets contain blanks to complete before execution.

## References

- Wooldridge, J. M. (2019). [*Introductory econometrics: A modern approach*](https://www.cengage.com/c/introductory-econometrics-a-modern-approach-7e-wooldridge/9781337558860) (7th ed.). Cengage Learning.
- Wooldridge, J. M. (2010). [*Econometric analysis of cross section and panel data*](https://mitpress.mit.edu/9780262232586/econometric-analysis-of-cross-section-and-panel-data/) (2nd ed.). MIT Press.
- Long, J. S. (1997). [*Regression models for categorical and limited dependent variables*](https://www.sagepub.com/shop/buy-a-book/regression-models-for-categorical-and-limited-dependent-variables-1-6071). SAGE Publications.
