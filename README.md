# econometrics-tutorials
Interactive Quarto tutorials for an introductory econometrics course.

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
