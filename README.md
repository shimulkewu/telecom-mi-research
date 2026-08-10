# telecom-mi-research
Toward Robust and Causal Mechanistic Interpretability in LLMs for Safety-Critical Network Fault Diagnosis

# Causal Mechanistic Interpretability for Telecom Network Fault Diagnosis

**Researcher:** Md. Yakub Hossan Khan (Shimul)  
**Program:** Master of Computing (Research), Multimedia University (MMU)  
**Supervisor:** Dr. Tan  
**Domain:** Mechanistic Interpretability | Trustworthy AI | Telecom Network Fault Diagnosis  

---

## 📌 Research Overview

This repository contains the complete code, experiments, and documentation for my Master's research on **causal mechanistic interpretability** applied to **safety-critical telecom network fault diagnosis**.

### The Problem

Modern telecom networks (5G, 6G, cloud infrastructure, enterprise networks) generate massive diagnostic data. Fault diagnosis—detecting problems, identifying root causes, and resolving them—is **safety-critical** because these networks support:

- Emergency response systems
- Healthcare infrastructure
- Banking and financial services
- Critical national infrastructure

**Current challenges:**

| Challenge | Description |
|-----------|-------------|
| **Black-box LLMs** | Models produce results without explaining *how* or *why* |
| **Behavioral-only evaluation** | F1/accuracy scores don't reveal internal reasoning |
| **Fragility under OOD conditions** | Models fail on real-world noise (log format variations, missing data, timestamp inconsistencies) |

### The Gap

No existing work combines:

1. **Domain-confined feature/circuit discovery** (Sparse Autoencoders tailored to telecom language)
2. **Causal validation** (activation patching, ablation, Causal Scrubbing)
3. **Robustness testing** (out-of-distribution, adversarial, noisy inputs)

...applied specifically to telecom network logs and configurations.

### The Contribution

This study is the **first** to:

- Apply domain-confined Sparse Autoencoders to telecom log data
- Validate discovered circuits causally using activation patching and ablation
- Stress-test circuits under realistic OOD conditions
- Benchmark against both behavioural baselines (LogPrompt, LogExpert) and causal MI baselines (MIB, Causal Scrubbing)

---

## 🎯 Research Questions

| RQ | Question |
|----|----------|
| **RQ1** | How effective are existing mechanistic interpretability methods in explaining LLM behaviour on telecom log analysis? |
| **RQ2** | What are the principal limitations of current approaches in terms of causal validity and robustness? |
| **RQ3** | Can a causal-intervention-based framework provide significantly more reliable and stable insights than standard correlational analysis? |

---

## 🗂️ Repository Structure

