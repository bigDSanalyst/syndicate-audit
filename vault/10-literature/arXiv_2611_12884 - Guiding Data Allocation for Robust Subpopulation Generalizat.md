---
aliases: ["Guiding Data Allocation for Robust Subpopulation Generalization"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.12884"
url: "http://arxiv.org/abs/2611.12884v1"
published: "2026-11-09T18:59:40Z"
ingested: "2026-11-10T14:24:24Z"
authors:
  - "Zhaoying Pan"
  - "Yipei Wang"
  - "Shenyu Lu"
  - "Xiaoqian Wang"
---

# Guiding Data Allocation for Robust Subpopulation Generalization

## Abstract

> Machine learning models often achieve high average accuracy in the training data while
> performing poorly on test data due to subpopulation shift. A common data-centric solution is to
> enforce balanced subgroup proportions, but full balance can be costly, infeasible, and not
> always necessary. In this work, we study whether balanced training data is the unique optimal
> configuration for robust subpopulation generalization. We extend a Gaussian feature-model
> framework to theoretically characterize the performance landscape across general training
> subgroup distributions. We show that multiple configurations, including substantially imbalanced
> ones, can perform comparably to the balanced one. We further derive gradient-based directions
> for adjusting subgroup proportions to improve adjusted accuracy and worst-group accuracy more
> efficiently. These findings suggest that strategically allocating data offers a more flexible
> and principled path to robust performance than simple balancing. The code is available at
> https://github.com/zhaoyingpan/subpop-data-allocation.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

