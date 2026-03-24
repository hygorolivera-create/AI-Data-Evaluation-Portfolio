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
1.  **Target Identification:** Defining the safety boundary to be tested (e.g., PII leakage, hate speech, or financial advice).
2.  **Prompt Engineering:** Utilizing techniques like *Roleplay*, *Payload Splitting*, and *Translation Injection* (PT-BR nuances).
3.  **Vulnerability Reporting:** Categorizing the bypass as Critical, High, or Medium based on the model's refusal failure.

## 3. RLHF & SFT Labeling
When creating "Golden Responses" for training:
* **Tone & Voice:** Neutral, professional, and culturally aligned with Brazilian Portuguese.
* **Formatting:** Strict adherence to JSONL structures for seamless model fine-tuning.

---

# 🇧🇷 Diretrizes de Avaliação (PT-BR)

Este documento descreve a metodologia profissional utilizada neste portfólio.

### Metodologia de Red Teaming:
1.  **Identificação do Alvo:** Definição da fronteira de segurança (ex: vazamento de dados ou discurso de ódio).
2.  **Engenharia de Prompt:** Uso de técnicas de *Roleplay* e *Injeção de Tradução* (nuances do PT-BR).
3.  **Relatório de Vulnerabilidade:** Classificação da falha entre Crítica, Alta ou Média.
