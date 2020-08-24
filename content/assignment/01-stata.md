---
title: "Up and Running with Stata"
linktitle: "1: Stata"
date: "2020-08-20"
menu:
  assignment:
    parent: Stata
    weight: 1
type: docs
---

# `Stata` Assignment #1

1. Make sure you can download and install `Stata` from the [A-State software downloads page](https://www.astate.edu/a/its/software-downloads/).

2. Create a new Do file and add this header (with your relevant information):

<pre class="sh_stata">
```{Stata}
version 16.1
clear
log using "filename.smcl", replace
cd "~/Desktop/"		

*==============================================================================
*==============================================================================
*=     File-Name:      filename.do                                           == 
*=     Date:           8/25/2020                                             ==
*=     Author:         Cameron Wimpy (cwimpy@astate.edu)                     ==
*=     Purpose:                                                              == 
*=     Input File 1:   filename.dta                                          ==
*=     Input File 2:   filename.do                                           ==
*=     Output File:    filename.smcl                                         ==
*=     Data Output:    n/a                                                   ==
*=     Previous file:  n/a                                                   ==
*=     Software:       Stata 16.0                                            ==
*=     Machine:        Macbook Pro                                           == 
*=     System:         10.15.3                                               ==
*==============================================================================
*==============================================================================
```
</pre>

3. Open the `auto` dataset and estimate a linear regression model with `mpg` as the dependent variable and `weight` as the predictor. 

4. Interpret the model.

5. Create a scatterplot with a line of best fit for the model. 

6. Now add `foreign` to as a predictor.

7. Interpret the model. 

8. Create a high-quality regression table (hint: There are `Stata` packages that can do this for you). 

9. Submit your work as a PDF to Dr. Wimpy. Be sure to show all of your work.