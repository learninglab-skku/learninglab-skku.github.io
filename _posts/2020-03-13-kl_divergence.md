---
title: KL divergence
date: 2020-03-13
comments: true
categories: 
- Math
tags:
- Information Theory
- Machine Learning
---

## Definition
Kullback-Leibler divergence (or distanct) between two probability density functions (PDF) $f$ and $g$ is defined as

$$
D(f||g) = \int f(x) \log \frac{ f(x) }{ g(x) } dx.
$$
