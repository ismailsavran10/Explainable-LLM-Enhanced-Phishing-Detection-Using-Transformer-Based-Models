# Explainable-LLM-Enhanced-Phishing-Detection-Using-Transformer-Based-Models
This project presents an explainable and context-aware phishing detection framework for email security, combining transformer-based language models with large language model (LLM) reasoning. The system performs accurate phishing classification while generating human-readable explanations to support security analysis and decision-making.
🛡️ Explainable LLM-Enhanced Phishing Detection
Using Transformer-Based Language Models

An explainable, context-aware framework for email phishing detection combining Transformers and LLM reasoning

<br/>










</div>
✨ Overview

This project introduces an explainable and context-aware phishing detection framework for email security, built upon transformer-based deep learning models and enhanced with Large Language Model (LLM) reasoning.

Unlike traditional phishing detectors that rely on static rules or shallow features, the proposed system learns semantic intent, contextual manipulation, and social engineering patterns directly from email content.
Beyond classification, it generates human-readable explanations, transforming black-box predictions into transparent security insights.

🔥 Why This Matters

Modern phishing attacks are no longer simple spam messages.
They are carefully crafted, linguistically persuasive, and often multilingual.

Traditional approaches struggle because they:

Depend on fixed keyword lists

Fail to model long-range context

Lack interpretability for security analysts

This project directly addresses these limitations by combining:

Contextual language understanding + LLM-based reasoning + explainable outputs

🧠 Core Contributions

✅ High-accuracy phishing detection using transformer models

✅ Binary and multi-class phishing classification

✅ Explainable AI pipeline powered by LLMs

✅ Hybrid analysis combining textual context and technical security indicators

✅ Web-based deployment for real-time email analysis

🏗️ System Architecture
┌────────────────────┐
│ Email Subject + Body│
└─────────┬──────────┘
          ↓
┌────────────────────┐
│ Text Preprocessing │
└─────────┬──────────┘
          ↓
┌──────────────────────────────┐
│ Transformer Encoder          │
│ (XLM-RoBERTa)                │
└─────────┬────────────────────┘
          ↓
┌──────────────────────────────┐
│ Binary / Multi-Class Output  │
└─────────┬────────────────────┘
          ↓
┌──────────────────────────────┐
│ Technical Signal Extraction  │
│ (URL structure, TLDs, etc.)  │
└─────────┬────────────────────┘
          ↓
┌──────────────────────────────┐
│ LLM Reasoning Module         │
│ (Mistral)                   │
└─────────┬────────────────────┘
          ↓
┌──────────────────────────────┐
│ Explainable Security Report  │
└──────────────────────────────┘

🧪 Models & Design Rationale
🔹 Transformer Encoder — XLM-RoBERTa

XLM-RoBERTa was selected after extensive benchmarking against:

BERT

BERT-TURK

RoBERTa

ELECTRA

DistilBERT

mDeBERTa

📊 Result:
99.21% accuracy in binary phishing detection, with superior performance on:

Multilingual content

Contextual deception

Low false-negative rates (critical for security systems)

🔹 Large Language Model — Mistral-7B

The LLM serves as an explanation engine, not a classifier.

It transforms:

Model predictions

URL-based technical indicators

Linguistic cues

into clear, natural language explanations that justify why an email is considered phishing or safe.

🔍 Explainable AI (XAI) Strategy

Instead of opaque confidence scores, the system explains decisions using:

Suspicious URL patterns

Abnormal top-level domains (TLDs)

Social engineering keywords

Contextual inconsistencies

These signals are synthesized by the LLM into analyst-friendly explanations, making the system suitable for both end-users and cybersecurity professionals.

📊 Experimental Results
Metric	Value
Binary Accuracy	99.21%
Phishing Recall	High
Precision–Recall Balance	Stable
Multi-Class Separation	Meaningful

The results confirm that contextual transformer models, when paired with explainable reasoning, are highly effective against sophisticated phishing attacks.
