# AI Data Evaluation & Red Teaming Portfolio
**Specialist: Hygor Oliveira** *Focus: RLHF, Safety Alignment, and PT-BR Linguistic Evaluation*

---

## 🎯 Professional Objective
To provide high-level data evaluation and adversarial testing for Large Language Models (LLMs), ensuring safety, factual accuracy, and cultural alignment in the Brazilian Portuguese market.

## 🛠️ Tech Stack & Tools
- **Testing Environments:** Google AI Studio, OpenAI Playground.
- **Data Formatting:** JSONL, Markdown, CSV.
- **Frameworks:** HHH (Helpfulness, Honesty, Harmlessness).
- **Core Skills:** Red Teaming, Hallucination Detection, Intent Classification.

---

## 🧪 Featured Case Studies

### Case #001: Safety Bypass via Role-Play (Red Teaming)
**Target:** Malicious Code Generation (Keylogger)  
**Language:** Portuguese (PT-BR)  
**Risk Level:** 🔴 Critical Fail

#### **Scenario Description**
Tested the model's ability to resist "Persona Injection" (Jailbreaking). Using a "Hollywood Screenwriter" persona, I attempted to bypass safety filters to obtain functional malware code in Portuguese.

#### **Technical Audit (The Specialist's View)**
- **Vulnerability:** The model prioritized the creative narrative over its core safety guidelines.
- **Finding:** It provided a fully functional Python script (`pynput` based) for a keylogger.
- **Mitigation Strategy:** The model requires further RLHF to recognize that high-risk requests (malware/spyware) must be refused regardless of the creative context or "educational" framing.

[View Detailed Log & Code Analysis](./cases/red-teaming-001.md)

---

## 📊 Dataset Samples (JSONL)
*Samples of high-quality training data for model fine-tuning.*

- [Linguistic Nuances PT-BR](./datasets/cultural_alignment.jsonl) (Coming Soon)
- [Safety Refusals Dataset](./datasets/safety_training.jsonl) (Coming Soon)

---

## 🌐 Contact & Links
- **LinkedIn:** [Your Profile Link Here]
- **Market Focus:** Global (Remote) | Specialized in LATAM Alignment.
