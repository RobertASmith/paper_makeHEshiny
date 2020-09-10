## Making health economic models Shiny: A tutorial

[![GitHub release](https://img.shields.io/badge/R-HEDS-green)](https://img.shields.io/badge/R-hello-green)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/RobertASmith/paper_makeHEshiny?color=red&style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/RobertASmith/paper_makeHEshiny?style=plastic)
![GitHub repo size](https://img.shields.io/github/repo-size/RobertASmith/paper_makeHEshiny?style=plastic)
[![GitHub forks](https://img.shields.io/github/forks/RobertASmith/paper_makeHEshiny?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/RobertASmith/paper_makeHEshiny/network/)



This is the repo for the paper [Making health economic models Shiny: A tutorial](https://wellcomeopenresearch.org/articles/5-69/v2) published in Wellcome Open Research.

This can be cited as: 

Smith R and Schneider P. Making health economic models Shiny: A tutorial. Wellcome Open Res 2020, 5:69 (https://doi.org/10.12688/wellcomeopenres.15807.2)

Authors: [Robert Smith](https://www.linkedin.com/in/robert-smith-53b28438) and [Paul Schneider](https://www.sheffield.ac.uk/scharr/staff-pgrs/studentprofiles/paulschneider)

Institution: School of Health and Related Research, University of Sheffield, Regents Court, Sheffield, S1 4DA, UK

Corresponding author: Robert Smith (rasmith3@sheffield.ac.uk)

Website: [Dark Peak Analytics](https://www.darkpeakanalytics.com)

### Abstract

Health economic evaluation models have traditionally been built in Microsoft Excel, but more sophisticated tools are increasingly being used as model complexity and computational requirements increase. Of all the programming languages, R is most popular amongst health economists because it has a plethora of user created pack-ages and is highly flexible. However, even with an integrated development environment such as R Studio, R lacks a simple point and click user interface and therefore requires some programming ability. This might make the switch from Microsoft Excel to R seem daunting, and it might make it difficult to directly communicate results with decisions makers and other stakeholders. The R package Shiny has the potential to resolve this limitation. It allows programmers to embed health economic models developed in R into interactive webbrowser based user interfaces. Users can specify their own assumptions about model parameters and run different scenario analyses, which, in case of a regular Markov model, can be computed within seconds. This paper provides a tutorial on how to wrap a health economic model built in R into a Shiny application. We use a four-state Markov model developed by the Decision Analysis in R for Technologies in Health (DARTH) group as a case-study to demonstrate main principles and basic functionality.

### Repository Description:

This repository contains the extended data and the two functions which were referred to in the text but not included in the manuscript:

f_gen_psa: Generates PSAs 

f_MM_sicksicker: Runs model for one set of PSA inputs

f_wrapper: Model wrapper used in Shiny app

shinyApp: Shiny application user interface and server function.

### Funding: 
Rob and Paul are joint funded by the Wellcome Trust Doctoral Training Centre in Public Health Economics and Decision Science [108903] and the University of Sheffield.

