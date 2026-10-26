---
aliases: ["Shared clones make random cell halves look reproducible in pooled screens"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.32962"
url: "http://arxiv.org/abs/2610.32962v1"
published: "2026-10-23T17:53:14Z"
ingested: "2026-10-26T12:19:15Z"
authors:
  - "Xuanrui Huang"
---

# Shared clones make random cell halves look reproducible in pooled screens

## Abstract

> Single-cell perturbation screens are used to train and evaluate models that predict perturbation
> effects, and model scores are judged against how reproducible the measured effects are.
> Reproducibility is usually judged by splitting each perturbation's cells into two random halves.
> This assumes that the halves are independent replicates. In pooled screens such as Perturb-seq,
> however, the cells carrying a guide RNA descend from a limited number of transduced cells, so
> two random halves contain the same clones: pseudoreplication whose unit is not marked in the
> data. Using perturbations that should have no effect as controls, we compared random halves with
> independent replicates from separate transductions, and tested directly with halves that differ
> only in their clones. In a genome-scale screen of primary T cells, null perturbations agreed
> between random halves almost always and between independent replicates only half the time, the
> rate expected from noise alone; measuring more cells did not remove this agreement. Splitting
> the cells into halves that share no clone, by the T-cell receptor constant region or by a clone
> barcode, largely removed the excess agreement. Its size equals the share of expression
> differences set by clones divided by the effective number of clones per perturbation; across 16
> screens it was largest in T cells transferred into mice and in a genome-scale primary T-cell
> screen, one to two orders of magnitude smaller in cell lines, and smallest in non-dividing
> neurons. Shared clones inflate benchmark ceilings and reliability labels, and when a model's
> input and its scoring answer come from one transduction, published models that predict
> perturbation effects in a new cell state appear better than a baseline that ignores the
> perturbation; against cells from another transduction, most fall below it. Reproducibility
> should be judged across separate transductions.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

