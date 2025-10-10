---
title: "Hawkes Processes in Finance: An Application in Modeling Transactions in EUA Futures"
collection: publications
category: manuscripts
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-08-28
venue: 'Contemporary Mathematics'
paperurl: 'https://ojs.wiserpub.com/index.php/CM/article/view/7184/3423'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Hawkes processes are stochastic point processes with self-exciting behavior, where the occurrence of an event increases the probability of subsequent events. In this paper, we provide a concise yet comprehensive introduction to Hawkes processes, focused on applications. We then employ marked Hawkes processes to model the occurrences of transactions in European Union Allowances (EUA) futures. The models are trained using an innovative and efficient Maximum Likelihood Estimation (MLE) implementation, that leverages PyTorch library to parallelize computations and exploit automatic differentiation. We evaluate and compare different excitation functions using Akaike Information Criterion (AIC), Bayesian Information Criterion (BIC), and Quantile-Quantile (Q-Q) plots based on the Random Time Change theorem. Additionally, we analyze the distribution of the calibrated parameters across different trading hours, finding a consistent relationship, to our knowledge never described before, between the self-exciting intensity parameter α and the decay parameter β . Furthermore, we identify two clusters: one characterized by transactions with a strong self-exciting effect, but that decays very quickly, and another with a less intense effect, that persists over longer time. Using logistic regression, we analyze the characteristics of the clusters and provide possible interpretations. We consider Hawkes processes very promising yet underutilized techniques for studying financial markets, and we believe this work can encourage researchers and practitioners to dive further into these models.