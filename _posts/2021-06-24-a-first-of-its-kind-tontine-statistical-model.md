---
title: "A First of its Kind Tontine Statistical Model"
excerpt: "'What is now proved was once only imagined.' ~ William Blake"
categories:
  - Research
  - Explainer
tags:
  - tontines
  - tech
  - projection
  - model

classes: wide

header:
  teaser: /assets/images/thumb/nuovalo-thisisengineering.png


---

> “What is now proved was once only imagined.” ~ William Blake (1757-1827)

We have been working on a model that decomposes the sources of risk within a modern fair tontine and computes the risk-contribution of each source to survivor credit and payout variability. The model supports a broad degree of different product designs, and is useful to anyone who wishes to design a longevity risk-sharing solution or understand the components that drive such a product's outcomes.

As far as we know, the model is the first of its kind to use closed-form solutions rather than having to rely on Monte Carlo simulation.  So in addition to being insightful, it is also lightning fast!

There are a number of factors that govern the degree of idiosyncratic longevity risk diversification, primarily:
- Pool membership size (which is likely to vary over time, depending on whether the scheme is open-ended or closed and other design decisions)
- Cohort effects (ages, genders, relative size of account balances across cohorts, whether a single cohort or multiple cohorts)
- The distribution of investor contribution amounts

Naturally, the selection of mortality rates and mortality improvement rates is an important input.

The model can also project the probability distribution of payouts for any given member -- again, without the use of simulation.  The characteristics of the selected investment portfolio is an important input here, along with the design of the payout mechanism.  We envision this will be useful not only for product designers, but also for individuals who are considering an investment and those who have already made investments and want to quickly look up what their up-to-the-moment payout projections.

The model is rigorously tested and ready to use with our clients.  Over time, we will create tools that wrap new functionality and user interfaces around it.

![Lightening](/assets/images/thumb/nuovalo-lightening.jpg)
