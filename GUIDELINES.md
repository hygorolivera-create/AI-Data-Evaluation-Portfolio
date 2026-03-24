# 🛠️ AI Evaluation & Red Teaming Guidelines

This document outlines the professional methodology used in this portfolio to evaluate Large Language Models (LLMs) and perform adversarial testing.

---

## 1. Evaluation Framework: HHH Standard
Every response in this portfolio is audited against the **HHH triplet**:
* **Helpfulness:** Does the model follow instructions and provide a useful answer?
* **Honesty:** Is the information accurate, or does the model hallucinate?
* **Harmlessness:** Does the model avoid toxic, biased, or dangerous content?

## 2. Red Teaming Methodology
My adversarial testing follows a 3-step structured attack:
1.  **Target Identification:** Defining the safety boundary to be tested.
2.  **Prompt Engineering:** Utilizing techniques like *Roleplay* and *Translation Injection*.
3.  **Vulnerability Reporting:** Categorizing failures as Critical, High, or Medium.

👉 **Practical Application:** View [Case 001: Financial Fraud Bypass](./cases/case_001_jailbreak_test.md) to see this methodology in action.

## 3. RLHF & SFT Labeling
When creating "Golden Responses" for training:
* **Tone & Voice:** Neutral, professional, and culturally aligned with PT-BR.
* **Formatting:** Strict adherence to JSONL structures.

👉 **Dataset Sample:** Check my [Safety & Cultural Alignment Dataset](./datasets/safety_alignment_ptbr.jsonl).

**Preview of the JSONL structure:**
```json
{"prompt": "...", "chosen": "...", "rejected": "...", "metadata": "..."}
