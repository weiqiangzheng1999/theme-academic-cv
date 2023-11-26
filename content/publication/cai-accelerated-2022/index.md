---
title: Accelerated Single-Call Methods for Constrained Min-Max Optimization
authors:
- Yang Cai
- Weiqiang Zheng
date: '2022-09-01'
publishDate: '2023-11-26T02:45:28.692023Z'
publication_types:
- paper-conference
abstract: We study first-order methods for constrained min-max optimization. Existing
  methods either require two gradient calls or two projections in each iteration,
  which may be costly in some applications. In this paper, we first show that a variant
  of the emphOptimistic Gradient (OG) method, a emphsingle-call single-projection
  algorithm, has $O(frac1sqrtT)$ best-iterate convergence rate for inclusion problems
  with operators that satisfy the weak Minty variation inequality (MVI). Our second
  result is the first single-call single-projection algorithm -- the emphAccelerated
  Reflected Gradient (ARG) method that achieves the emphoptimal $O(frac1T)$ last-iterate
  convergence rate for inclusion problems that satisfy negative comonotonicity. Both
  the weak MVI and negative comonotonicity are well-studied assumptions and capture
  a rich set of non-convex non-concave min-max optimization problems. Finally, we
  show that the emphReflected Gradient (RG) method, another emphsingle-call single-projection
  algorithm, has $O(frac1sqrtT)$ last-iterate convergence rate for constrained convex-concave
  min-max optimization, answering an open problem of [Hsieh et al., 2019]. Our convergence
  rates hold for standard measures such as the tangent residual and the natural residual.
links:
- name: URL
  url: https://openreview.net/forum?id=HRwN7IQLUKA
---
