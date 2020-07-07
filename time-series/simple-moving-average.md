---
layout: default
title: Simple Moving Average
parent: Time Series
nav_exclude: false
usemathjax: true
---

## Table of contents
{:.no_toc .text-delta}

1. TOC
{:toc}

# {{ page.title }}

## Definition

The **simple moving average** of order $$2q + 1$$ centred on $$t$$ is given by the transformation

$$
\begin{equation}
MA(t) = \frac{1}{2q + 1}(X_{t-q} + \ldots + X_t + \ldots + X_{t+q})
\end{equation}
$$
