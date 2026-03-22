---
title: "Module III — Causal Representations & Learning from Interventions"
---

**Objective:** Learn representations that capture causal structure rather than associational shortcuts; leverage interventional data to validate and improve them.

#### Week 4: **Causal Representation Learning**

{: .schedule }
Apr 20
: **Lecture 7**{: .label .label-purple } : **Student presentation**{: .label .label-blue } From pixels and counts to causal state
* Why representation is the bottleneck for both generalization and identification
* Invariance across environments; identifiability of latent causal variables
* Causal disentanglement; representations as hypotheses tested by interventional and OOD probes
* Student paper: hybrid or mechanistic modeling (e.g., structured dynamics, physics-informed approaches to clinical data, or domain-knowledge-constrained learning)

Apr 22
: **Lecture 8**{: .label .label-purple } : **Student presentations**{: .label .label-blue } Causal representation learning (3 papers)
* Invariant/causal representations across environments, or causal foundation models
* Non-identifiability, nuisance leakage, or representation failure
* Causal disentanglement, independent mechanism analysis, or identifiability in single cells

#### Week 5: **Learning from Interventional Data — Perturbation Biology as Causal Inference**

{: .schedule }
Apr 27
: **Lecture 9**{: .label .label-purple } : **Student presentation**{: .label .label-blue } Perturbation biology, multimodal representations, and interpretability
* Estimands in perturbation biology 
* Perturbation screens as the biological analogue of RCTs, with their own identification challenges (batch/plate and CRISPR non-targeting confounders)
* CRISPR as "intent-to-treat": PerturbVI
* Multimodal learning from unpaired data
* Counterfactual inference in single cells; the benchmarking challenge (linear baselines vs. deep models)
* Student paper: perturbation biology (e.g., response prediction, counterfactual inference, or benchmarking)

Apr 29
: **Lecture 10**{: .label .label-purple } : **Student presentations**{: .label .label-blue } Perturbation biology, counterfactual inference & causal discovery (3 papers)
* Perturbation response prediction or counterfactual inference in single cells
* Causal structure learning from interventional data
* Experimental design or active learning for perturbation screens

May 1
: **Project proposal due**{: .label .label-red }
* 1-page proposal (teams of up to 2)

#### Week 6: **Foundation Models, Generative Approaches, and Evaluation**

{: .schedule }
May 4
: **Lecture 11**{: .label .label-purple } : **Guest lecture**{: .label .label-green } : **Student presentation**{: .label .label-blue } CellFlux — flow matching for perturbation prediction
* CellFlux: flow matching for modeling morphological responses to perturbations
* SDE extension with Bayesian treatment for improved generalization and OOD detection
* CellFluxRL: RL-based post-training with biologically anchored rewards
* Student paper: generative modeling or flow matching for biological data

May 6
: **Lecture 12**{: .label .label-purple } : **Student presentations**{: .label .label-blue } Foundation models, evaluation & benchmarking (3 papers)
* Foundation models for single-cell or perturbation data
* Evaluation methodology and benchmarking
* Multimodal biological learning or mechanistic interpretability
