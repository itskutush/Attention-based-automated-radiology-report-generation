# 🩺 Radiology Report Generation & English-to-Hindi NMT

This repository presents an end-to-end deep learning pipeline that automates **radiology report generation** from medical images and translates the generated reports from **English to Hindi** using a **Transformer-based Neural Machine Translation (NMT)** model.

The system bridges the gap between **medical imaging** and **linguistic accessibility**, ensuring that radiological findings are both accurately generated and linguistically inclusive for non-English-speaking regions.

## 📊 Results

* **BLEU Score (Translation Model):** `0.64`
* The Transformer-based NMT demonstrates strong translation performance within the **medical domain**, ensuring accurate and context-aware English-to-Hindi report translation.

## 🚀 Key Features

### 🧬 Radiology Report Generation

* Uses CNN/Transformer-based encoders (trained on datasets like **IU X-Ray** or **MIMIC-CXR**)
* Generates detailed, clinically coherent medical reports directly from **chest X-ray images**
* Capable of domain-specific fine-tuning for improved report accuracy

### 🌐 English-to-Hindi Translation (NMT)

* Implements a **Transformer architecture** fine-tuned for **medical report translation**
* Achieved a **BLEU score of 0.64**, reflecting strong translation quality
* Handles specialized radiology terminology effectively

### 🧠 Vision-Language Integration

* Combines **visual features** (from X-ray encoders) and **linguistic features** (from Transformer decoders)
* Enables a unified, multimodal AI system for healthcare language generation

### 📏 Evaluation Metrics

* **Report Generation:** BLEU
* **Translation:** BLEU = 0.64
* Supports custom dataset evaluation and fine-tuning


