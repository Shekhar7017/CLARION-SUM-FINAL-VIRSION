# 🧠 CLARION-SUM  
## Clinical Long-context Adaptive Reasoning & Integrated Optimization Network

🚀 A Hierarchical Fact-Aware Self-Refining Framework for Multi-Document Clinical News Summarization

---

## 📌 Overview

CLARION-SUM is a novel AI architecture designed for **multi-document clinical news summarization**.  
It integrates:

- 📊 Salience Graph Modeling  
- 🏗 Hierarchical Transformer Encoding  
- 📚 Long-Context Generation  
- ✅ Factual Verification Head  
- 🔁 Self-Refinement Loop  

Unlike traditional summarization models, CLARION-SUM explicitly optimizes:

- Relevance
- Factual consistency
- Redundancy reduction
- Coherence

---

## 🧪 Evaluated Against 10 Strong Baselines

| Category | Models |
|-----------|--------|
| Extractive | Lead-3, TextRank, BERTSUM |
| Abstractive | PEGASUS, BART, T5 |
| Long-context | Long-T5, LED |
| Hierarchical | HIBERT |
| LLM Reference | Prompt-based LLM |

---

## 📊 Evaluation Metrics

CLARION-SUM is evaluated using:

- ROUGE-L
- BERTScore
- FactScore (factual consistency)
- Redundancy Rate

---

## 🏗 Architecture

Pipeline:

1. Salience Graph Builder  
2. Hierarchical Encoder  
3. Long-context Generator  
4. Fact Verification Head  
5. Self-Refinement Loop  

Full training objective:

L = L_gen + λ1 L_fact + λ2 L_red + λ3 L_refine

---

## 📂 Repository Structure

