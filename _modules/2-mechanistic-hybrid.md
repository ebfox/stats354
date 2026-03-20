---
title: "Module II — Mechanistic & Hybrid Models"
---

**Objective:** Integrate mechanistic knowledge (physiology/biology) with ML to enable meaningful generalization to new interventions and domains.

#### Week 3: **Inductive Bias: Biological Priors**

{: .schedule }
Apr 13
: **Lecture 5**{: .label .label-purple }

  * Inductive bias taxonomy: architectural / regularization / data / evaluation
  * Mechanism-aligned bias vs “bias toward the wrong story”
  * How inductive bias interacts with identifiability, robustness, and trustworthiness

Apr 15
: **Lecture 6**{: .label .label-purple }

  * Case studies where inductive bias improves OOD generalization: physiology time series (state constraints, structured dynamics); perturbation biology (pathway/graph priors; compositionality); imaging (equivariance; nuisance suppression)
  * Cautionary tales: when structure increases overconfidence or locks in the wrong invariance


#### Week 4: **Hybrid Modeling: mechanistic cores + learned residuals**
*Just-in-time concepts:* identifiability (structural vs statistical), counterfactual simulation vs observational fit, uncertainty calibration.

{: .schedule }
Apr 20
: **Lecture 7**{: .label .label-purple }

  * Neural ODEs / universal differential equations / gray-box modeling spectrum
  * What counts as a mechanistic commitment (constraints, conserved quantities, known feedback)
  * Biasing towards mechanistic domain knowledge through the loss function
  * When hybrids help (extrapolation, data efficiency, interpretable state) vs when they mislead (non-identifiability, compensating errors)

Apr 22
: **Lecture 8**{: .label .label-purple } : **Student-led paper presentations**{: .label .label-blue }

  * One physiology-centric hybrid paper (e.g., glucose/ICU trajectories)
  * One biology-centric hybrid paper (e.g., dynamics or mechanistic pathway integration)


