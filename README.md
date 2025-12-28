# Explainable-LLM-Enhanced-Phishing-Detection-Using-Transformer-Based-Models
This project presents an explainable and context-aware phishing detection framework for email security, combining transformer-based language models with large language model (LLM) reasoning. The system performs accurate phishing classification while generating human-readable explanations to support security analysis and decision-making.
<div align="center">

# 🛡️ Explainable LLM-Enhanced Phishing Detection  
## Using Transformer-Based Language Models

**An explainable and context-aware framework for email phishing detection  
combining Transformers and Large Language Model (LLM) reasoning**

<br/>

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Transformer](https://img.shields.io/badge/Model-Transformer-success)
![LLM](https://img.shields.io/badge/LLM-Mistral-orange)
![XAI](https://img.shields.io/badge/Explainable%20AI-XAI-critical)
![Status](https://img.shields.io/badge/Status-Research%20Ready-brightgreen)

</div>

---

## 📌 Overview

This project presents an **explainable and context-aware phishing detection framework**
for email security, combining **transformer-based language models** with
**Large Language Model (LLM) reasoning**.

Unlike traditional phishing detection systems that rely on static rules or
handcrafted features, the proposed framework learns **semantic intent,
contextual manipulation, and social engineering patterns** directly from
email content.

Beyond classification, the system generates **human-readable explanations**,
transforming black-box predictions into **transparent security insights**
to support security analysts and decision-makers.

---

## 🔥 Why This Matters

Modern phishing attacks are no longer simple spam messages.
They are carefully crafted, linguistically persuasive, and often multilingual.

Traditional approaches struggle because they:

- ❌ Depend on fixed keyword lists  
- ❌ Fail to model long-range contextual dependencies  
- ❌ Lack interpretability for security analysts  

This project directly addresses these limitations by combining:

> **Contextual language understanding + LLM-based reasoning + explainable outputs**

---

## 🧠 Core Contributions

- ✅ High-accuracy phishing detection using transformer models  
- ✅ Binary and multi-class phishing classification  
- ✅ Explainable AI (XAI) pipeline powered by LLMs  
- ✅ Hybrid analysis combining textual context and technical security indicators  
- ✅ Web-based deployment for real-time email analysis  

---

## 🏗️ System Architecture

Email Subject + Body
↓
Text Preprocessing
↓
Transformer Encoder (XLM-RoBERTa)
↓
Binary / Multi-Class Classification
↓
Technical Signal Extraction (URL, TLDs, etc.)
↓
LLM Reasoning Module (Mistral)
↓
Explainable Security Report

---

## 🧪 Models & Design Rationale

### 🔹 Transformer Encoder — XLM-RoBERTa

XLM-RoBERTa was selected after extensive benchmarking against:

- BERT  
- BERT-TURK  
- RoBERTa  
- ELECTRA  
- DistilBERT  
- mDeBERTa  

**Result:**
- 🎯 **99.21% accuracy** in binary phishing detection  
- 🌍 Superior performance on multilingual content  
- 🛡️ Low false-negative rate (critical for security systems)  

---

### 🔹 Large Language Model — Mistral-7B

The LLM is used strictly as an **explanation engine**, not as a classifier.

It transforms:
- Model predictions  
- URL-based technical indicators  
- Linguistic and contextual cues  

into **clear, natural language explanations** describing *why* an email is
classified as phishing or legitimate.

---

## 🔍 Explainable AI (XAI) Strategy

Instead of opaque confidence scores, the system explains decisions using:

- Suspicious URL structures  
- Abnormal top-level domains (TLDs)  
- Social engineering keywords  
- Contextual inconsistencies in email content  

These signals are synthesized by the LLM into
**analyst-friendly and user-readable explanations**.

---

## 📊 Experimental Results

| Metric | Value |
|------|------|
| Binary Classification Accuracy | **99.21%** |
| Phishing Recall | High |
| Precision–Recall Balance | Stable |
| Multi-Class Separation | Meaningful |

---
