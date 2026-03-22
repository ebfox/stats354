---
title: "Module II — Mechanistic & Hybrid Models"
---

**Objective:** Integrate mechanistic knowledge with ML to improve both identification (constraining models toward causal mechanisms) and generalization (enabling extrapolation beyond the training distribution, e.g., to new interventions and contexts).

#### Week 3: **Inductive Bias and the Hybrid Modeling Toolkit**

{: .schedule }
Apr 13
: **Lecture 5**{: .label .label-purple } : **Student presentation**{: .label .label-blue } Inductive bias taxonomy through case studies
* Taxonomy: architectural / regularization / data / evaluation, with biomedical examples (equivariance, pathway priors, biological data augmentation, benchmark leakage)
* Cautionary tales: Mechanism-aligned bias vs. "bias toward the wrong story"
* How bias choice connects to both failure modes: shift-robust features and mechanism-aligned representations
* Student paper: inductive bias in biomedical ML (e.g., equivariance in molecular models, graph-structured priors, or evaluation-as-bias)

Apr 15
: **Lecture 6**{: .label .label-purple } : **Student presentation**{: .label .label-blue } The hybrid modeling toolkit
* The hybrid spectrum: pure mechanistic → gray-box → pure data-driven
* Neural ODEs, universal differential equations, physics-informed neural networks
* Case studies: glucose dynamics (CGM), pharmacokinetics, wearable biosignals
* When hybrids help (extrapolation, sample efficiency, identifiability, interpretability) vs. when they mislead (compensating errors)
* Student paper: hybrid modeling (e.g., neural ODE for clinical trajectories, PK/PD, mechanistic pathway integration, or gray-box approaches in biological systems)
  
