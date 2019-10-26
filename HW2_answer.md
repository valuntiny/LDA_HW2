















Marginal Models. For this homework you will need the R package gee.

Part A
------

Read the Analysis requirement in part B. For the both analysis parts (1)
and (2) in part B, clearly set up the model i.e. clearly state

1.  Distribution assumption for the outcome

2.  The systematic component of the model

3.  The canonical link function

4.  The variance function

5.  The correlation structure

Part B
------

In a clinical trial of patients suffering from epileptic seizures,
patients were randomized to receive either a placebo or the drug
progabide, in addition to standard therapy. A baseline count of the
number of epileptic seizures in a 8-week period prior to randomization
was obtained. In addition, counts of the number of epileptic seizures in
each of the four successive 2-week (post baseline) treatment periods
were obtained. The goal of the analysis is to make a comparison between
the two treatment groups in terms of changes in the rates of epileptic
seizures throughout the duration of the study. The data epilepsy.dat is
available on Courseworks. The variables in the data set are

-   Patient ID

-   Treatment (0=Placebo, 1=Progabide)

-   Age at baseline

-   Baseline 8 week seizure count

-   First 2 week seizure count

-   Second 2 week seizure count

-   Third 2 week seizure count

-   Fourth 2 week seizure count

Appendix
--------

    knitr::opts_chunk$set(echo = FALSE, message = FALSE, warning = FALSE, comment = "")
    library(tidyverse)
    options(knitr.table.format = "latex")
    theme_set(theme_bw())
