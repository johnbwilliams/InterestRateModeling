### Interest Rate Modeling README

Nine modeling techiques illustrated & compared:   Nelson-Siegel, polynomial, Svensson, Vasicek, Cox-Ingersoll-Ross, local polynomial, cubic B-spline, and smoothing spline. 

U.S. treasury yields on May 31, 1990 are modeled, data located in file Diablod_Li_data.txt

InterestRate.Rmd written in Rmarkdown, R programming & Latex,  knitted to Pdf with Rstudio and knitr package

InterestRate.Rmd expects Diablod_Li_data.txt to exist in a "data" subdirectory

R packages used to knit InterestRate.Rmd into InterestRate.pdf:

attached base packages:

splines stats graphics grDevices utils datasets methods base

other attached packages:

servr_0.3 KernSmooth_2.23-15 minpack.lm_1.2-0 ggplot2_2.1.0 knitr_1.12.3

packages loaded via a namespace (and not attached):

Rcpp_0.12.3 digest_0.6.9 plyr_1.8.3 grid_3.2.4 gtable_0.2.0 formatR_1.3 magrittr_1.5 evaluate_0.8.3 scales_0.4.0 highr_0.5.1 stringi_1.0-1 rmarkdown_0.9.5 labeling_0.3 tools_3.2.4 stringr_1.0.0 munsell_0.4.3 httpuv_1.3.3 yaml_2.1.13 colorspace_1.2-6 htmltools_0.3


