---
title: Doubly Optimal No-Regret Learning in Monotone Games
authors:
- Yang Cai
- Weiqiang Zheng
date: '2023-07-01'
publishDate: '2023-11-26T02:45:28.699142Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 40th International Conference on Machine Learning*'
abstract: We consider online learning in multi-player smooth monotone games. Existing
  algorithms have limitations such as (1) being only applicable to strongly monotone
  games; (2) lacking the no-regret guarantee; (3) having only asymptotic or slow 
  {{< math >}}$ 1/\sqrt{T} ${{< /math >}}
  last-iterate convergence rate to a Nash equilibrium. While the (1𝑇√)O(1T)mathcalO(frac1sqrtT)
  rate is tight for a large class of algorithms including the well-studied extragradient
  algorithm and optimistic gradient algorithm, it is not optimal for all gradient-based
  algorithms. We propose the accelerated optimistic gradient (AOG) algorithm, the
  first doubly optimal no-regret learning algorithm for smooth monotone games. Namely,
  our algorithm achieves both (i) the optimal (𝑇‾‾√)O(T)mathcalO(sqrtT) regret in
  the adversarial setting under smooth and convex loss functions and (ii) the optimal
  (1𝑇)O(1T)mathcalO(frac1T) last-iterate convergence rate to a Nash equilibrium in
  multi-player smooth monotone games. As a byproduct of the accelerated last-iterate
  convergence rate, we further show that each player suffers only an (log𝑇)O(log⁡T)mathcalO(log
  T) individual worst-case dynamic regret, providing an exponential improvement over
  the previous state-of-the-art (𝑇‾‾√)O(T)mathcalO(sqrtT) bound.
links:
- name: arXiv
  url: https://arxiv.org/abs/2301.13120
- name: PMLR
  url: https://proceedings.mlr.press/v202/cai23g.html

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
