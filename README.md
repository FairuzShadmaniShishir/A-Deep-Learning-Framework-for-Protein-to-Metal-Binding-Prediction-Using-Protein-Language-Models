# 🧬 A Deep Learning Framework for Protein-to-Metal Binding Prediction Using Protein Language Models

This repository presents an end-to-end deep learning framework to predict protein-to-metal ion binding using modern protein language models. The approach leverages pretrained embeddings from **BioTransformers** and deep learning architectures to identify metal-binding proteins from their amino acid sequences.

---

## 📌 Overview

Understanding protein-metal interactions is crucial for many biological functions, including enzymatic catalysis, structural stability, and signal transduction. This project uses transformer-based protein language models to learn sequence-based features and predict whether a given protein binds to metal ions.

---

## 🧠 Key Features

- ✅ Utilizes **BioTransformers** and **Facebook FAIR's ESM models** for robust protein representation.
- ✅ Employs a **deep learning classifier** (TensorFlow) for binary prediction of metal binding.
- ✅ Includes **data preprocessing**, **model training**, and **evaluation** pipelines.
- ✅ Easy-to-run scripts for **reproducibility** and **scalability**.

---

## 📊 Libraries and Dependencies

| Library        | Version    |
|----------------|------------|
| TensorFlow     | 2.11.0     |
| NumPy          | 1.23.5     |
| Pandas         | 1.5.3      |
| Scikit-learn   | 1.2.2      |
| Matplotlib     | 3.7.1      |
| Seaborn        | 0.12.2     |
| BioTransformers| 0.1.2      |
| fair-esm       | 0.4.0      |
| transformers   | 4.29.2     |
| Ray            | 2.6.3      |

Install using:

```bash
pip install -r requirements.txt


