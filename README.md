# 🛰️ NMT-Transformer-Telugu-English 
### *Neural Machine Translation for Dravidian Languages*

---

![Transformer Architecture](https://jalammar.github.io/images/t/transformer_resideual_layer_norm_2.png)

## 📖 Overview
This repository contains a **from-scratch implementation** of the Transformer architecture (Attention is All You Need) specifically tuned for **Telugu to English translation**. 

In this project, I address the linguistic complexities of Telugu—an agglutinative language—by implementing a custom **Byte Pair Encoding (BPE)** tokenization pipeline and a multi-layer Transformer stack.

---

## 🛠️ Tech Stack & Architecture
* **Framework:** TensorFlow 2.x / Keras
* **Architecture:** Encoder-Decoder Transformer
* **Key Components:** * Multi-Head Scaled Dot-Product Attention
    * Positional Encoding (Sinusoidal)
    * Custom Subword Tokenization (BPE)
    * Label Smoothing & Masked Loss Calculation

## 🚀 Key Features
* **Linguistic Preprocessing:** Handles Telugu Unicode normalization and script-specific regex cleaning.
* **Attention Visualization:** Includes scripts to generate heatmaps showing how the model "attends" to Telugu words during English generation.
* **Inference Pipeline:** A modular `evaluate()` function designed for low-latency translation.

---

## 🏗️ System Flow
1.  **Data Ingestion:** Parallel Telugu-English Corpus.
2.  **Preprocessing:** Tokenization + Start/End sequence padding.
3.  **Training:** Multi-epoch run with Adam Optimizer & Learning Rate Scheduler.
4.  **Inference:** Greedy Search decoding for real-time translation.

---

## 📊 Project Status: Proof of Concept (PoC)
> **Note:** The current notebook demonstrates a verified architecture. To prevent local hardware thermal throttling, the model was trained on a subset of data. **Full convergence** is targeted for a high-compute cloud environment (AWS/GCP).

---

## 🤝 Contact & Portfolio
**ALEX** – AI & NLP Engineer  
*Focusing on LLMs, RAG, and Production-Grade AI Systems.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](www.linkedin.com/in/thelexa)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/The-Lexa)


