---
title: Uncoupled and Convergent Learning in Two-Player Zero-Sum Markov Games with
  Bandit Feedback
authors:
- Yang Cai
- Haipeng Luo
- Chen-Yu Wei
- Weiqiang Zheng
date: '2023-11-01'
publishDate: '2023-11-26T02:45:28.681796Z'
publication_types:
- paper-conference
publication: 'The Thirty-Sixth Annual Conference on Neural Information Processing Systems (NeurIPS 2023)'
abstract: We revisit the problem of learning in two-player zero-sum Markov games,
  focusing on developing an algorithm that is uncoupled, convergent, and rational,
  with non-asymptotic convergence rates. We start from the case of stateless matrix
  game with bandit feedback as a warm-up, showing an {{< math >}}$ O(T^{-1/8}) ${{< /math >}}
  last-iterate convergence rate. To the best of our knowledge, this is the first result
  that obtains finite last-iterate convergence rate given access to only bandit feedback.
  We extend our result to the case of irreducible Markov games, providing a last-iterate
  convergence rate of {{< math >}}$ O(T^{-1/(9+\varepsilon)}) ${{< /math >}} for any {{< math >}}$ \varepsilon > 0 ${{< /math >}}.
  Finally, we study Markov games without any assumptions on the dynamics, and show
  a path convergence rate, which is a new notion of convergence we defined, of {{< math >}}$ O(T^{-1/(10}) ${{< /math >}}.
  Our algorithm removes the coordination and prior knowledge requirement of [Wei et
  al., 2021], which pursued the same goals as us for irreducible Markov games. Our
  algorithm is related to [Chen et al., 2021, Cen et al., 2021] and also builds on
  the entropy regularization technique. However, we remove their requirement of communications
  on the entropy values, making our algorithm entirely uncoupled.
tags:
- Computer Science - Computer Science and Game Theory
- Computer Science - Machine Learning
links:
- name: arXiv
  url: http://arxiv.org/abs/2303.02738
---
