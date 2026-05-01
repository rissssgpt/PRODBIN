# 🧬 PRODBIN – Protein-DNA Binding Prediction

## 📌 Overview

**PRODBIN** is a machine learning-based project for predicting protein–DNA binding sites using sequence information.
This project is built upon the **CLAPE (Contrastive Learning And Pre-trained Encoder)** framework and adapted for practical usage and experimentation.

---

## 👨‍💻 Author

**Rishabh**
GitHub: https://github.com/rissssgpt

---

## 🎯 Objective

The goal of this project is to:

* Predict protein–DNA binding sites from FASTA sequences
* Utilize deep learning and pre-trained protein language models
* Provide an easy-to-use prediction pipeline

---

## ⚙️ Technologies Used

* Python
* PyTorch
* HuggingFace Transformers
* ProtBert Model

---

## 📂 Project Structure

```
PRODBIN/
│── clape.py
│── example.fa
│── requirements.txt
│── README.md
│── models/
│── data/
```

---

## 🚀 Installation

### Step 1: Clone the repository

```
git clone https://github.com/rissssgpt/PRODBIN.git
cd PRODBIN
```

### Step 2: Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the prediction:

```
python clape.py --input example.fa --output output.txt
```

---

## 📊 Parameters

| Parameter   | Description          |
| ----------- | -------------------- |
| --input     | Input FASTA file     |
| --output    | Output file          |
| --ligand    | DNA / RNA / AB       |
| --threshold | Prediction threshold |

---

## 🧠 How It Works

* Uses **ProtBert**, a pre-trained protein language model
* Applies contrastive learning for feature extraction
* Predicts binding sites based on sequence patterns

---

## 📌 Features

* Supports DNA, RNA, and antibody binding prediction
* Easy command-line interface
* Based on state-of-the-art research

---

## 📚 Reference

This project is inspired by:

Protein–DNA binding site prediction using contrastive learning and protein language models (Briefings in Bioinformatics, 2024)

---

