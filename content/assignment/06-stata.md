---
title: "Pooled Time Series Analysis"
linktitle: "6: Pooled Time Series Analysis"
date: "2020-09-29"
menu:
  assignment:
    parent: Stata
    weight: 6
type: docs
---


For the substantive assignment [click here](https://posc6013.science/assignment/05-substance/). 

## `Stata` Assignment #6

1. Go through the following steps:

- Using the `life_exp_gdp.dta` dataset examine the role of GDP per capita on life expectancy over time. 
- `xtset` your data and use the "xt" suite of commands to summarize the data.
- Estimate both a random- and fixed-effects model and calculate the Hausman test. Which model does the test suggest?
- Compute an interpret a test for a panel unit root
- Look at the help file for panel-corrected standard errors (`help xtpcse`) and choose a dynamic specification and estimate the model. Note that you can also use the time series operators (e.g., `L.life`) with this command once the data are "xtset."
- Finally, estimate the model with time fixed effect. 
- Copy your code, interpretations, and output to a Word document and save as a PDF. E-mail the PDF to Dr. Wimpy by next Monday @11:59 p.m. Note, if you use a Stata log file, you can just save that as a PDF and send it to Dr. Wimpy instead of a Word document. 