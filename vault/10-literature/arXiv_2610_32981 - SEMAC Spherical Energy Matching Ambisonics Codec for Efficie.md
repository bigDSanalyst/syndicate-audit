---
aliases: ["SEMAC: Spherical Energy Matching Ambisonics Codec for Efficient Higher-Order Ambisonics Compression"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.32981"
url: "http://arxiv.org/abs/2610.32981v1"
published: "2026-10-23T17:59:55Z"
ingested: "2026-10-26T12:19:15Z"
authors:
  - "Christoph Hold"
  - "Jan Buethe"
  - "Jean-Marc Valin"
  - "Jan Skoglund"
  - "Toni Hirvonen"
  - "Nils Peters"
---

# SEMAC: Spherical Energy Matching Ambisonics Codec for Efficient Higher-Order Ambisonics Compression

## Abstract

> Higher-order Ambisonics (HOA) is an attractive format for immersive spatial audio, but its high
> channel count and directional properties present significant audio coding challenges. The widely
> deployed Opus audio codec supports HOA through Channel Mapping Families 2 and 3 (RFC 8486),
> which code and transmit every Ambisonics channel, so the bitrate grows quadratically with the
> spherical harmonic order. We introduce SEMAC, which instead represents an Ambisonics signal by a
> quantized full-order directional energy envelope together with fewer CELT-coded transport
> channels. CELT separates a per-band energy envelope from the signal shape and restores it after
> quantization, and SEMAC generalizes this principle to directional signals. Since the reduced
> transport spans only a lower-dimensional subspace, the decoder re-imposes the envelope observed
> at the encoder input, restoring the directional energy distribution at full order. A MUSHRA test
> on fifth-order material compares SEMAC against Opus CMF~3 in matched configurations at 512 and
> 768 kbit/s. SEMAC with 16 of 36 transport channels is rated above full-order CMF~3 at both
> rates, and at equal transport channel count above order truncation. The proposed SEMAC strategy
> of coding fewer transport channels with the directional envelope is found perceptually
> preferable to coding all HOA channels at low precision.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

