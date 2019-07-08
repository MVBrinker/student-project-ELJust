# Student project - Eva Lucia Justenhoven

## Abstract

In this notebook, I replicate the results from  "The Importance of School Systems: Evidence from International Differences in Student Achievement." by L. Woessmann (2016). 
The aim is to show that institutional settings, such as external exit exams and school autonomy, positively influence student achievement. In order to do so, Woessmann estimates an education production function in a cross-country dataset of 29 OECD countries with data from PISA 2012.

I add to the analysis by visualizing the identification strategy in the first section, followed by some descriptive statistics in the second section, and a more thourough look into the differences between the 15 and 16 year olds in the sample.


## Visualization & Issues

In this section I visualize the author's identification strategy with Directed Acyclical Graphs and discuss several issues, e.g. potential reverse causality and endogeneity through omitted variables. Last, I also provide a short description of the general criticism that PISA tests are faced with.

## Data & Descriptive Statistics

After a short overview of the data I create a table for mean scores per country and plots to visualize country test score distributions and the effect of an exemplary proxy for school autonomy coupled with external exit exams.

## Replication

Woessmann bases his analysis on three tables. The first is based on the results of a weighted least squares estimation of the education production function, with family backgorund factors, resources, and institutional factors as explanatory variables, and students' math test scores as the dependent variable. The second is a comparison of each of the input factors' relative ability to account for variation in test scores. The third table computes the difference from the international mean and accounted variance in test scores per country. 

## The Age Effect 

Following one of the main criticism, that students of different age are tested, I look more closely into the age effect. I look at differences in test scores and their distribution per age group and check whether countries ranked high have a higher number of sixteen year olds tested in the sample.

[![Build Status](https://travis-ci.org/HumanCapitalAnalysis/student-project-template.svg?branch=master)](https://travis-ci.org/HumanCapitalAnalysis/student-project-template) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](HumanCapitalAnalysis/student-project-template/blob/master/LICENSE)
