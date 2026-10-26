---
aliases: ["Low-Complexity Wideband Channel Estimation for ISAC in Analog Millimeter-Wave Systems"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.32953"
url: "http://arxiv.org/abs/2610.32953v1"
published: "2026-10-23T17:47:31Z"
ingested: "2026-10-26T12:19:15Z"
authors:
  - "Hamza Touati"
  - "Raffaele Viterbo"
  - "Mattia Brambilla"
  - "Sandra Roger"
  - "Carmen Botella-Mascarell"
---

# Low-Complexity Wideband Channel Estimation for ISAC in Analog Millimeter-Wave Systems

## Abstract

> Accurate wideband channel estimation is a key enabler for millimeter-wave (mmWave) integrated
> sensing and communication (ISAC) systems. In the narrowband scenario, the Transformed Spatial
> Domain Channel Estimation (TSDCE) method was previously shown to provide fast and accurate angle
> estimation with substantially lower complexity than conventional compressed-sensing approaches
> based on orthogonal matching pursuit (OMP). However, wideband ISAC scenarios additionally
> require delay estimation, making joint angle-delay sparse recovery computationally expensive due
> to the multidimensional dictionary search. In this paper, we propose a wideband extension of
> TSDCE, namely TSDCE-TD, which incorporates time-domain support and decouples angle and delay
> estimation. Two variations are proposed for delay estimation: TSDCE-TD (Dict), which uses a one-
> dimensional delay dictionary, and TSDCE-TD (FFT), which applies Fast Fourier Transform (FFT)
> zero-padding interpolation. Path estimates are iteratively refined through successive
> interference cancellation and alternating angle-delay updates. Simulation results show that the
> proposed methods outperform OMP-based baselines under practical dictionary sizes, while
> achieving comparable performance at high-resolution settings with substantially lower
> computational complexity. Moreover, the angle-delay estimates obtained using the proposed
> approach enable accurate single-anchor indoor localization in a ray-traced environment,
> achieving sub-20 cm positioning errors and satisfying practical indoor positioning requirements.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

