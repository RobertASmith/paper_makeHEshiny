## Making health economic models Shiny: A tutorial

Robert Smith and Paul Schneider

School of Health and Related Research, University of Sheffield, Regents Court, Sheffield, S1 4DA, UK

Corresponding author: Robert Smith (rasmith3@sheffield.ac.uk)

### Abstract

Health economic evaluation models have traditionally been built in Microsoft Excel, but more sophisticated tools are increasingly being used as model complexity and computational requirements increase. Of all the programming languages, R is most popular amongst health economists because it has a plethora of user created pack-ages and is highly flexible. However, even with an integrated development environment such as R Studio, R lacks a simple point and click user interface and therefore requires some programming ability. This might make the switch from Microsoft Excel to R seem daunting, and it might make it difficult to directly communicate results with decisions makers and other stakeholders. The R package Shiny has the potential to resolve this limitation. It allows programmers to embed health economic models developed in R into interactive webbrowser based user interfaces. Users can specify their own assumptions about model parameters and run different scenario analyses, which, in case of a regular Markov model, can be computed within seconds. This paper provides a tutorial on how to wrap a health economic model built in R into a Shiny application. We use a four-state Markov model developed by the Decision Analysis in R for Technologies in Health (DARTH) group as a case-study to demonstrate main principles and basic functionality.

### Repository Description:

This repository contains the two functions which were referred to in the text not included in the manuscript:

- f_gen_psa  A function 

- f_MM_sicksicker
