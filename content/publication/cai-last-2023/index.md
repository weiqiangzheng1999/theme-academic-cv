---
title: Last-Iterate Convergence Properties of Regret-Matching Algorithms in Games
authors:
- Yang Cai
- Gabriele Farian
- Julien Grand-Cl{\'e}ment
- Christian Kroer
- Chung-Wei Lee
- Haipeng Luo
- Weiqiang Zheng
date: '2023-11-15'
publishDate: '2023-11-26T02:45:28.681796Z'
publication_types:
- manuscript
publication: 'Working Paper'
abstract: Algorithms based on regret matching, specifically regret matching+ (RM+), and its variants are the most popular approaches for solving large-scale two-player zero-sum games in practice. Unlike algorithms such as optimistic gradient descent ascent, which have strong last-iterate and ergodic convergence properties for zero-sum games, virtually nothing is known about the last-iterate properties of regret-matching algorithms. Given the importance of last-iterate convergence for numerical optimization reasons and relevance as modeling real-word learning in games, in this paper, we study the last-iterate convergence properties of various popular variants of RM+. First, we show numerically that several practical variants such as simultaneous RM+, alternating RM$^+$, and simultaneous predictive RM+, all lack last-iterate convergence guarantees even on a simple {{< math >}}$ 3 \times 3 ${{< /math >}} game. We then prove that recent variants of these algorithms based on a *smoothing* technique do enjoy last-iterate convergence -> we prove that *extragradient RM+* and *smooth Predictive RM+*  enjoy asymptotic last-iterate convergence (without a rate) and {{< math >}}$ O(\frac{1}{\sqrt{T}}) ${{< /math >}} best-iterate convergence. Finally, we introduce restarted variants of these algorithms, and show that they enjoy linear-rate last-iterate convergence.

tags:
- Computer Science - Computer Science and Game Theory
- Computer Science - Machine Learning
links:
- name: arXiv
  url: https://arxiv.org/abs/2311.00676
---
