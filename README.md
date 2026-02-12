# CLARION-SUM  
### A Hierarchical Fact-Aware Self-Refining Framework for Multi-Document Clinical News Summarization

---

## 📌 Overview

CLARION-SUM is a novel hierarchical, fact-aware, self-refining framework designed for **multi-document clinical news summarization**.

It integrates:

- Salience-driven graph modeling  
- Hierarchical transformer encoding  
- Long-context generation  
- Factual verification head  
- Iterative self-refinement loop  

The model aims to generate summaries that are:
- Factually consistent  
- Less redundant  
- Coherent  
- Clinically reliable  

---

## 🏗️ System Architecture

CLARION-SUM consists of five major components:

1. **Sentence Segmentation**
2. **Salience Graph Module**
3. **Hierarchical Transformer Encoder**
4. **Long-Context Generator**
5. **Factual Verification + Self-Refinement Loop**

The refinement continues until factual consistency stabilizes.

---

## 🧠 Mathematical Formulation

Given a set of clinical documents:

D = {d₁, d₂, ..., dₙ}

We generate a summary:

S = {s₁, s₂, ..., sₘ}

Optimization objective:

max αRel(S, D) − βRed(S) + γFact(S, D) + δCoh(S)

Where:

- Rel(S, D) → Semantic relevance  
- Red(S) → Redundancy penalty  
- Fact(S, D) → Factual consistency  
- Coh(S) → Coherence  

---

## 🎯 Training Objective

Total Loss:

L = L_gen + λ₁L_fact + λ₂L_red + λ₃L_refine

- L_gen → Cross-entropy generation loss  
- L_fact → Factual inconsistency penalty  
- L_red → Redundancy penalty  
- L_refine → Iterative refinement improvement  

---

## 📊 Datasets

We evaluate CLARION-SUM on:

- **MEDIQA-ClinicalSumm**
- **PubMed**

Both datasets contain long clinical and biomedical documents suitable for multi-document summarization.

---

## 📈 Baselines (10 Models Compared)

### Extractive:
- Lead-3  
- TextRank  
- BERTSUM  

### Abstractive:
- BART  
- T5  
- PEGASUS  

### Long-document:
- Long-T5  
- LED  

### Hierarchical:
- HIBERT  

### LLM-based:
- Prompt-based LLM summarization  

---

## 📏 Evaluation Metrics

- ROUGE-L  
- BERTScore  
- FactScore  
- Redundancy Score  

---

## 🔬 Key Contributions

✔ Salience-aware graph-based importance modeling  
✔ Integrated factual verification during training  
✔ Iterative self-refinement mechanism  
✔ 10-model comparative evaluation  
✔ Mathematical formulation + ablation study  

---

## ⚙️ Implementation Details

- Framework: PyTorch  
- Library: HuggingFace Transformers  
- Optimizer: AdamW  
- Learning Rate: 3e-5  
- Batch Size: 4  
- GPU: NVIDIA GPU (16GB)  

---

## 🚀 Future Work

- Larger-scale clinical datasets  
- Stronger factual alignment mechanisms  
- Clinical domain-specific pretraining  

---

## 📜 License

For research and academic purposes only.

---

## 👤 Author

Shekhar  
Research Intern – Suvidha Foundation NGO  

---

⭐ If you find this work useful, consider starring the repository!
