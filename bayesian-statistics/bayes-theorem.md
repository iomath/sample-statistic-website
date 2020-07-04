---
layout: default
title: Bayes theorem
parent: Bayesian Statistics
nav_exclude: false
has_toc: true
usemathjax: true
---

## Table of contents
{:.no_toc .text-delta}

1. TOC
{:toc}

# {{ page.title }}

## Definition

For two events *A* and *B*, the conditional probabilities *P(A\|B)* and *P(B\|A)* are related by **Bayes' theorem**:

$$
\begin{equation}
P(A|B) = \frac{P(B|A) P(A)}{P(B)}
\end{equation}
$$

where the probability *P(B)* may be obtained using the formula

$$
\begin{equation}
P(B) = P(B|A) P(A) + P(B|\textit{not }A) P(\textit{not }A)
\end{equation}
$$
