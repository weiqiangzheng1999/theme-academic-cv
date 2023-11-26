---
title: Accelerated Single-Call Methods for Constrained Min-Max Optimization
authors:
- Yang Cai
- Weiqiang Zheng
date: '2023-1-15'
publishDate: '2023-11-26T02:45:28.692023Z'
publication_types:
- paper-conference
publication: 'Proceedings of the 11th International Conference on Learning Representations (ICLR 2023)'
abstract: We study first-order methods for constrained min-max optimization. Existing
  methods either require two gradient calls or two projections in each iteration,
  which may be costly in some applications. In this paper, we first show that a variant
  of the *Optimistic Gradient* (OG) method, a *single-call single-projection*
  algorithm, has {{< math >}}$ O(\frac{1}{\sqrt{T}}) ${{< /math >}} best-iterate convergence
  rate for inclusion problems with operators that satisfy the weak Minty variation inequality (MVI). 
  Our second result is the first single-call single-projection algorithm -- the *Accelerated
  Reflected Gradient* (ARG) method that achieves the *optimal* {{< math >}}$ O(\frac{1}{T}) ${{< /math >}} last-iterate
  convergence rate for inclusion problems that satisfy negative comonotonicity. Both
  the weak MVI and negative comonotonicity are well-studied assumptions and capture
  a rich set of non-convex non-concave min-max optimization problems. Finally, we
  show that the *Reflected Gradient* (RG) method, another *single-call single-projection*
  algorithm, has {{< math >}}$ O(\frac{1}{T}) ${{< /math >}} last-iterate convergence rate for constrained convex-concave
  min-max optimization, answering an open problem of [Hsieh et al., 2019]. Our convergence
  rates hold for standard measures such as the tangent residual and the natural residual.
links:
- name: arXiv
  url: https://arxiv.org/abs/2210.03096
- name: Openreview
  url: https://openreview.net/forum?id=HRwN7IQLUKA
---
