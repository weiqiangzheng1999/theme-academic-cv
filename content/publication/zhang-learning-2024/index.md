---
title: Learning Thresholds with Latent Values and Censored Feedback
authors:
- Jiahao Zhang
- Tao Lin
- Weiqiang Zheng
- Zhe Feng
- Yifeng Teng
- Xiaotie Deng
date: '2024-1-16'
publishDate: '2024-01-16T02:45:28.681796Z'
publication_types:
- paper-conference
publication: 'The Twelfth International Conference on Learning Representations (ICLR 2024)'
abstract: In this paper, we investigate a problem of *actively* learning threshold in latent space, where the *unknown* reward {{< math >}}$g(\gamma, v)${{< /math >}} depends on the proposed threshold {{< math >}}$\gamma${{< /math >}} and latent value {{< math >}}$v${{< /math >}} and it can be *only* achieved if the threshold is lower than or equal to the *unknown* latent value. 

This problem has broad applications in practical scenarios, e.g., reserve price optimization in online auctions, online task assignments in crowdsourcing, setting recruiting bars in hiring, etc.
We first characterize the query complexity of learning a threshold with the expected reward at most {{< math >}}$\eps${{< /math >}} smaller than the optimum and prove that the number of queries needed can be infinitely large even when {{< math >}}$g(\gamma, v)${{< /math >}} is monotone with respect to both {{< math >}}$\gamma${{< /math >}} and {{< math >}}$v${{< /math >}}. On the positive side, we provide a tight query complexity {{< math >}}$\tilde{\Theta}(1/\eps^3)${{< /math >}} when {{< math >}}$g${{< /math >}} is monotone and the CDF of value distribution is Lipschitz. Moreover, we show a tight {{< math >}}$\tilde{\Theta}(1/\eps^3)${{< /math >}} query complexity can be achieved as long as {{< math >}}$g${{< /math >}} satisfies right Lipschitzness, which provides a complete characterization for this problem. Finally, we extend this model to an online learning setting and demonstrate a tight {{< math >}}$\Theta(T^{2/3})${{< /math >}} regret bound using continuous-arm bandit techniques and the aforementioned query complexity results.
tags:
- Computer Science - Computer Science and Game Theory
- Computer Science - Machine Learning
links:
- name: arXiv
  url: https://arxiv.org/abs/2312.04653
- name: Openreview
  url: https://openreview.net/forum?id=qaKRfobbTg&noteId=imTyA8JVvG
---
