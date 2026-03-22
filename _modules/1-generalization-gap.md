---
title: "Module I — The Generalization Gap in Biohealth: Why “Scale” Fails"
---

**Objective:** Understand why predictive success often fails to translate to deployment for two distinct reasons — generalization failure (models break under distribution shift) and identification failure (models capture associations, not causal mechanisms).

#### Week 1: **Predictive Success vs. Causal Validity**

{: .schedule }
Mar 30
: **Lecture 1**{: .label .label-purple } Why causality matters in biohealth
* Course framing: identification and generalization as scientific validity in real-world clinical and biological practice 
* “World models” vs shortcut predictors; predictive accuracy vs counterfactual validity; getting to mechanistic validity.
* Canonical failure modes across domains: proxy learning, selection/measurement bias, and feedback loops
* Course overview and logistics

Apr 1
: **Lecture 2**{: .label .label-purple } Dataset shift and identification, reframed causally
* Shift taxonomy (covariate/label/concept) : what changed in the data-generating process?
* Selection vs. sampling; collider bias and selection; Berkson's bias
* Feedback and performativity: when deployment changes the data-generating process
* Identification failure within a single population
* RCTs as the gold standard for identification: what they solve (confounding) and what they don't (transportability, mechanism)

#### Week 2: **Foundations & Aspirations** 

{: .schedule }
Apr 6
: **Lecture 3**{: .label .label-purple } : **TA-led**{: .label .label-yellow } Causal inference primer
* DAGs, the do-operator, confounding, d-separation, backdoor criterion
* Identification strategies: adjustment, instrumental variables, front-door criterion
* ATE, ATT, CATE: the estimands that matter in biomedicine

Apr 8
: **Lecture 4**{: .label .label-purple } : **Guest lecture**{: .label .label-green } Virtual cell models — hope vs. hype
* Objectives and evaluation of "virtual cells" / "digital twins"
* Interpolation vs. extrapolation in perturbation space
* Evaluation beyond reconstruction: interventional prediction, transport across labs, mechanistic sanity checks

