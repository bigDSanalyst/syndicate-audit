---
aliases: ["Reframe: Observation-Aligned Multi-Teacher On-Policy Distillation for Agentic Visual Reasoning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.12886"
url: "http://arxiv.org/abs/2611.12886v1"
published: "2026-11-09T18:59:54Z"
ingested: "2026-11-10T14:24:24Z"
authors:
  - "Haozhi Yuan"
  - "Handong Li"
  - "Yifan Zhang"
  - "Qianshan Wei"
---

# Reframe: Observation-Aligned Multi-Teacher On-Policy Distillation for Agentic Visual Reasoning

## Abstract

> Agentic reinforcement learning (RL) and multi-teacher on-policy distillation (MOPD) offer
> complementary routes to post-training. For visual agents, however, tool use presents two related
> challenges. Models may overlook useful tool-returned observations, while poorly grounded actions
> can limit the evidence available for subsequent distillation. We introduce Reframe, a post-
> training framework that treats the observation state, rather than only the output distribution,
> as an object of alignment. First, Ground-Drop-GRPO (GD-GRPO) trains spatial and temporal
> specialists with evidence-aware rewards and stochastic removal of the original visual input,
> encouraging them to acquire grounded evidence and use the returned observations. Second,
> Observation-Gated-MOPD (OG-MOPD) replaces deficient tool actions with canonical ones mid-rollout
> and resumes distillation from the repaired observation. The two stages complement each other, as
> learning to rely on tool-returned observations can help the policy benefit from observation
> repair. Neither stage requires a task-specific SFT cold start. Extensive experiments over 14
> image and video benchmarks demonstrate that Reframe outperforms both Mix-RL and vanilla MOPD.
> Ablation results show that GD-GRPO increases observation dependence and tool gain compared with
> outcome-based GRPO.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

