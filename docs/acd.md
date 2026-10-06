# Autonomous Cyber Defense · research extension

This is a **fork and extension** of the LLM-driven autonomous defense work by **Castro et al.**, co-developed by **Dor Cohen and Baruh Ifraimov**. The simulator and baseline are upstream contributions.

![Architecture](../assets/acd.svg)

The extension adds semantic action validation (CoSC), structured/schema-constrained outputs and repair, richer observations, telemetry, local model configurations, and explicit quick/strict experimental protocols. See the [contribution map](https://github.com/doric2000/llms-are-acd#what-changed-vs-original-where-and-why), [manuscript](https://github.com/doric2000/llms-are-acd/blob/main/pdf/LaTeX/LLMRL_Baruh_Dor_2026.pdf), and repository run/evaluation artifacts.

The README distinguishes current quick-protocol artifacts from strict-protocol manuscript claims. Results obtained under different protocols, workloads, or episode counts are **not directly comparable**. This portfolio makes no percentage-superiority claim over the original RL baseline. Implemented guardrails and telemetry are separated from measured experimental outcomes.

Preserve the upstream citation and Apache-2.0 license when reusing the work.
