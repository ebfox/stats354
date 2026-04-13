---
layout: default
title: Home
seo:
  type: Course
  name: "{{ site.title }}"
nav_order: 1
---

# {{ site.tagline }}

While modern machine learning models often achieve superhuman performance on biohealth benchmarks, they frequently fail to generalize to new hospitals, patient populations, or biological contexts. This course investigates the theoretical and practical foundations of **generalizable inference** in biomedicine, focusing on the critical gap between predictive performance and mechanistic validity. We will examine how to build world models that leverage biological structure, enabling generalization beyond the training distribution.

We will study ML models for clinical applications using EHR, imaging, and wearable data, as well as virtual cell models spanning imaging and omics modalities. Modeling frameworks will include sequence models, flow-matching generative models, vision transformers and language models, neural ODEs, variational autoencoders, and&mdash;in a forward-looking module&mdash;foundation models and agentic systems.

Key topics include:
- **Inductive biases** and biologically relevant priors
- **Causal representation learning** (discovering latent state variables)
- **Hybrid models** (e.g., combining mechanistic ODEs with neural networks)
- **Learning from interventional data** (from perturbation screens to policy learning)
- Causal **transportability** and external validity
- **Frontier foundation and agentic models** in biohealth

## Teaching Team

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Logistics

**When**: Class is Mondays and Wednesdays 10:30–11:50am.

**Where**: Building 380, Room 380-F.

**Links**:
- [Ed](https://edstem.org/us/dashboard): This is the main way that you and the teaching team should communicate: we will post all important announcements here, and you should ask all course-related questions here.
- [Canvas](https://canvas.stanford.edu/courses/227405): The course Canvas page contains links and resources only accessible to students.

**Course Grade**: The course grade will be based on the following components.
- Class participation (20%)
- Paper presentation (30%)
- Final project (50%)
