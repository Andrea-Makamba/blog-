---
title: Kaggle Home Equity Project
author: ~
date: '2018-06-18'
slug: kaggle-home-equity-project
categories: []
tags: []
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

The 'Home Credit Default Risk' competition on Kaggle aims to model whether an individual will default on their home loan based on numerous characteristics ranging from their credit card balance to marital status to the results of previous loan applications. 
Using this data, I decided to use a linear model, incorporating all these charasteristics in order to produce an accurate model. In future iterations, I hope to eliminate certain attributes that don't contribute to the output in a method known as 'Human Factor Engineering'. I also hope to be able to assign weights to each characteristic, so that the things that matter more such as the individual's income or the number of times the individual has defaulted on previous loans.
