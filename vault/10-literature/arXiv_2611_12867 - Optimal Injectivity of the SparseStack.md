---
aliases: ["Optimal Injectivity of the SparseStack"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.12867"
url: "http://arxiv.org/abs/2611.12867v1"
published: "2026-11-09T18:53:30Z"
ingested: "2026-11-10T14:24:24Z"
authors:
  - "Lorenzo Beretta"
  - "Simone Bombari"
  - "Margalit Glasgow"
  - "Raphael Arkady Meyer"
  - "Kijun Shin"
  - "David P. Woodruff"
---

# Optimal Injectivity of the SparseStack

## Abstract

> An Oblivious Subspace Injection (OSI) is a random sketching matrix that reliably preserves the
> minimum singular value of any fixed subspace with high constant probability, requiring only a
> one-sided spectral lower bound without controlling upper singular values. While classical
> Oblivious Subspace Embeddings (OSEs) fundamentally require row sparsity $Ω(\log r)$ at linear
> sketch dimension $k = O(r)$, we show that one-sided injectivity permits strictly sparser
> sketches, establishing matching (up to $\log\log r$ factors) upper and lower bounds of
> $\tildeΘ(\sqrt{\log r})$. First, we prove that the SparseStack sketch achieves constant
> injectivity at linear dimension $k = Θ(r)$ with row sparsity only $ζ= O(\sqrt{\log r})$, well
> below the $Θ(\log r)$ barrier where standard operator-norm concentration fails. Second, we
> establish a matching lower bound: any isotropic random sketching matrix satisfying a mild row-
> overlap condition requires row sparsity $ζ= Ω(\sqrt{\log r / \log \log r})$ to achieve linear-
> dimension injectivity, confirming that the $\sqrt{\log r}$ scale is fundamental. To bypass the
> lack of an operator-norm upper bound when $ζ= O(\sqrt{\log r})$, we decouple the sketch into two
> independent halves and introduce three techniques: (i) a uniform lower bound for flat vectors
> via randomized rounding, controlling discretization error using solely the Frobenius norm; (ii)
> a Gaussian truncation and minimax duality argument showing that all non-flat vectors escaping
> injectivity in the first half concentrate on a single universal coordinate subset $I \subseteq
> [n]$ of size $O(r/ζ)$, bypassing union bounds over supports; and (iii) a two-tier coordinate
> isolation analysis in the second half that suppresses collisions to $e^{-Ω(ζ^2)} \ll 1/r$,
> reliably preserving these heavy coordinates.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

