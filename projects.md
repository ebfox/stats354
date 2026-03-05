---
layout: default
title: Projects
nav_order: 3
---

## Important Dates

- **Mon., April 27, 2026 at 11:59pm**: Project proposal (1 page)
- **Mon., May 18, 2026 at 11:59pm**: Project midway “stress test” report
- **Wed., June 3, 2026 (class time)**: Final project presentations (short talks or poster session — TBD)
- **Mon., June 8, 2026 at 11:59pm**: Final project report

## Your Course Project

Your final project is an opportunity to take a claim that looks strong *in-distribution* (high AUC, low MSE, good reconstructions, etc.) and interrogate whether it is **scientifically and causally meaningful under realistic deployment shift**. In STATS 354, a great project is less about “beating a benchmark” and more about constructing and validating a **generalization argument**:

- What is the *target* deployment distribution, and what shifts are realistic?
- What causal estimand is implied, and under what assumptions is it identified?
- Which components of your model are mechanistic commitments vs. statistical convenience?
- What is the cheapest falsification experiment / stress test that could break your claim?

Projects may be done individually or in teams of **up to two students**. You are welcome to build on the seed ideas below or propose your own, as long as (i) you have data access now and (ii) you can articulate a concrete evaluation plan.

Your project will be evaluated on:

- **Scientific validity under shift**: Are your assumptions explicit, and do your experiments actually probe the claimed generalization?
- **Technical depth**: Are the methods appropriate and thoughtfully implemented (not just “run a package”)?
- **Empirical rigor**: Do you include negative controls, subgroup / worst-case checks, and uncertainty calibration where relevant?
- **Communication**: Is the writeup clear, well-structured, and supported by informative figures and diagnostics?

## Project Proposal

Submit a **1-page maximum** proposal by **Monday, April 27, 2026 at 11:59pm** (submission link TBD).

Include:

- Project title
- Problem setting and *deployment target*
- Dataset(s) and what you can (and cannot) access
- The main causal/generalization claim you want to test
- A concrete evaluation plan including at least one **domain shift** and one **negative control**
- 1–3 relevant papers

## Project Midway “Stress Test” Report

Submit a midway report by **Monday, May 18, 2026 at 11:59pm** (submission link TBD).

This should be a short writeup (suggested **2–3 pages**) describing your first experiments, including:

- One **negative control** (e.g., placebo outcome/exposure, label permutation where appropriate, falsification test)
- One **domain shift / robustness** experiment (e.g., new site, protocol change, perturbation context, missingness pattern, distributional shift)
- What failed, what surprised you, and what you plan to change

## Final Project Report

Submit a final report by **Monday, June 8, 2026 at 11:59pm** (submission link TBD).

Suggested format: **4–6 pages** (plus references). Your report must include a short **Generalization Contract** section:

- What you claim generalizes (and to what target)
- What assumptions your claim requires
- What evidence you provide for those assumptions
- What you explicitly do *not* claim

## Project Ideas

Below are a few curated project directions to get you started (you can also propose your own):

- Hybrid physiological models (digital twins; counterfactual simulation) for clinical decision support
- Representation for policy learning (clinician-informed states; doubly robust OPE; human-in-the-loop evaluation)
- Virtual-cell / perturbation modeling (interventional validity + transport)
- External validity across hospitals (transportability + dataset shift)
- Exploring causal validity of world models
- Other: student-proposed project idea
