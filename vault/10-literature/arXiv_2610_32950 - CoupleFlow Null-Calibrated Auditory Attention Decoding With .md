---
aliases: ["CoupleFlow: Null-Calibrated Auditory Attention Decoding With Time-Locked Brain-Speech Coupling and Flow-Matching Likelihood Ratios"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.32950"
url: "http://arxiv.org/abs/2610.32950v1"
published: "2026-10-23T17:44:09Z"
ingested: "2026-10-26T12:19:15Z"
authors:
  - "Ali Alavi"
  - "Donald S. Williamson"
---

# CoupleFlow: Null-Calibrated Auditory Attention Decoding With Time-Locked Brain-Speech Coupling and Flow-Matching Likelihood Ratios

## Abstract

> Auditory attention decoding (AAD) seeks to identify the attended talker from brief noninvasive
> brain recordings by comparing neural responses with competing speech streams. Recent
> electroencephalography (EEG) decoders report nearly perfect accuracy from one second of data,
> yet we show that this performance fails to generalize to unseen speech because models exploit
> trial leakage, eye gaze, and acoustic cues instead of speech evoked neural activity. We
> introduce CoupleFlow, which decodes attention through temporal coupling between neural and
> acoustic embeddings. Its predictions remain at chance when the brain signal contains no
> informative coupling, preventing shortcuts based on speech content or talker identity. A
> conditional flow matching head implements a likelihood ratio decision rule based on pointwise
> mutual information between brain and speech. This rule is Bayes optimal when the recording
> depends only on the attended talker and removes preferences for speech that is likely a priori.
> We evaluate CoupleFlow with content disjoint splits recovered from the audio and null tests that
> distinguish genuine temporal coupling from trial recognition. Across nine EEG and
> magnetoencephalography (MEG) datasets processed through a common pipeline, spanning four
> languages, high density EEG recordings, listeners with hearing impairment, and a room with
> multiple talkers, CoupleFlow outperforms linear and deep baselines while all null tests remain
> at chance. Finally, we derive an evidence accumulation law that predicts accuracy across window
> lengths from a single parameter per dataset and predicts that parameter from the strength of
> neural speech tracking. This law identifies recording signal to noise ratio as a limit on
> decoding speed and reliability and estimates the window length required to reach a target
> accuracy.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

