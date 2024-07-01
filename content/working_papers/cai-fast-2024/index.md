---
title: Fast Last-Iterate Convergence of Learning in Games Requires Forgetful Algorithms
authors:
- Yang Cai
- Gabriele Farian
- Julien Grand-Clément
- Christian Kroer
- Chung-Wei Lee
- Haipeng Luo
- Weiqiang Zheng
date: '2024-06-15'
publishDate: '2024-06-15'
publication_types:
- manuscript
publication: 'Working Paper'
abstract: Self-play via online learning is one of the premier ways to solve large-scale two-player zero-sum games, both in theory and practice. Particularly popular algorithms include optimistic multiplicative weights update (OMWU) and optimistic gradient-descent-ascent (OGDA). While both algorithms enjoy {{< math >}}$ O(1/T) ${{< /math >}} ergodic convergence to Nash equilibrium in two-player zero-sum games, OMWU offers several advantages, including logarithmic dependence on the size of the payoff matrix and {{< math >}}$ O(1/T) ${{< /math >}} convergence to coarse correlated equilibria even in general-sum games. However, in terms of last-iterate convergence in two-player zero-sum games, an increasingly popular topic in this area, OGDA guarantees that the duality gap shrinks at a rate of {{< math >}}$ O(1/\sqrt{T}) ${{< /math >}}, while the best existing last-iterate convergence for OMWU depends on some game-dependent constant that could be arbitrarily large. This begs the question: is this potentially slow last-iterate convergence an inherent disadvantage of OMWU, or is the current analysis too loose? Somewhat surprisingly, we show that the former is true. More generally, we prove that a broad class of algorithms that do not forget the past quickly all suffer the same issue: for any arbitrarily small {{< math >}}$ \delta > 0 ${{< /math >}}, there exists a {{< math >}}$ 2 \times 2 ${{< /math >}} matrix game such that the algorithm admits a constant duality gap even after {{< math >}}$ 1/\delta ${{< /math >}} rounds. This class of algorithms includes OMWU and other standard optimistic follow-the-regularized-leader algorithms.

tags:
- Computer Science - Computer Science and Game Theory
- Computer Science - Machine Learning
- Mathematics - Optimization and Control
links:
- name: arXiv
  url: https://arxiv.org/abs/2406.10631
---
