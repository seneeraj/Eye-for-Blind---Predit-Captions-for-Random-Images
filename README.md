# README.md

# 👁️ Eye for the Blind – AI Image Captioning System

## 📌 Overview

**Eye for the Blind** is an AI-powered Image Captioning system that generates natural language descriptions for images using deep learning. The system uses a CNN-RNN architecture with an Attention mechanism and can be extended into a web-based accessibility tool for visually impaired users.

---

## 🚀 Features

* 📷 Image Caption Generation
* 🧠 Attention Mechanism Visualization
* 🔤 Greedy Search & Beam Search Decoding
* 📊 BLEU Score Evaluation
* 🔊 (Planned) Audio Narration using Text-to-Speech
* 🌐 (Planned) Web App Interface

---

## 🧠 Model Architecture

* **CNN**: InceptionV3 (Pretrained on ImageNet)
* **Encoder**: Dense layer to embed image features
* **Attention**: Bahdanau Attention
* **Decoder**: GRU-based sequence generator
* **Dataset**: Flickr8k

---

## 📂 Project Structure

```
Eye-for-Blind/
│
├── Images/
├── captions.txt
├── notebook.ipynb
├── model/
├── utils/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/eye-for-blind.git
cd eye-for-blind
pip install -r requirements.txt
```

---

## ▶️ Usage

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📊 Results

* BLEU-4 Score: ~1.7 (single reference)
* Model generates grammatically correct captions
* Attention maps highlight relevant image regions

---

## 🔮 Future Enhancements

* 🌐 Web App (Streamlit / Flask)
* 🔊 Text-to-Speech (Audio Output)
* 🔁 Caption Refinement (Beam Search / LLM)
* 📦 Deployment (Cloud / API)
* 🧠 Transformer-based Models

---

## 📚 Learnings

* Encoder-Decoder Architecture
* Attention Mechanisms
* Sequence Modeling
* Evaluation Metrics (BLEU)
* Model Overfitting Analysis

---

## 👨‍💻 Author

Neeraj Bhatia

