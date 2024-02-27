# PYCACHU-chronology
This repository contains the code and data to perform an age-depth bayesian model for the core TRAM21-1B presented in Julián-Posadas et al. (link).

# Description

This R code utilizes the rbacon package to perform the estimation of accumulation rates and the calibration of original dates in the TRAM21_pub.csv file.

# Requirements
To run this code, you will need to have R installed on your computer, as well as the following R packages: rbacon, dplyr, and tidyverse. You can install them by running the following code in your R console:

install.packages("rbacon")
install.packages("dplyr")
install.packages("tidyverse")

# Usage

Before running the code, make sure to set your working directory using setwd() so that the files are saved in the correct location. This code requires you to specify certain parameters, such as core thickness (thick), ring(sample spacing (d.by), and core name (core.name). Additionally, you must provide values for the acc.mean, acc.shape, mem.strength, and mem.mean parameters, which control the accuracy of the data analysis. The ones presented here under "params" were those finally used in Julián-Posadas et al. The code also includes functions to create accumulation rate plots and to calibrate original dates. The results are saved in an output file named "tram21.v4_calibrated.csv".

If you have any questions or issues with this code, please feel free to contact me or open an issue on the GitHub repository of the rbacon package.
