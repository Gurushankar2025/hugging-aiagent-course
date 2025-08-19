## **Hugging Face Transformers – NLP Projects**
---

This repository contains my learning and practice projects using the Hugging Face Transformers library.
Currently, it includes:

## **📌 Contents**
**1. Pipelines Project**

Demonstrates the use of transformers.pipeline for multiple NLP tasks, grouped under:

Encoder Models

Decoder Models

Encoder–Decoder Models

## **Implemented Tasks & Example Models**

| Task | Example Models |
|------|----------------|
| Sentiment Analysis | distilbert-base-uncased-finetuned-sst-2-english |
| Zero-Shot Classification | facebook/bart-large-mnli |
| Question Answering | distilbert-base-cased-distilled-squad |
| Text Generation | gpt2 |
| Summarization | facebook/bart-large-cnn |
| Translation | Helsinki-NLP/opus-mt-en-fr |


----

### **2. Fine-Tuning: Resume Screening Model**

Fine-tunes a Transformer model to classify resumes into categories for recruitment screening.

**Base Model:** bert-base-uncased (can be replaced as needed)

**Approach:** Hugging Face Trainer API

**Dataset:** Ai_Resume_Screening.csv | available in the same repo dataset folder for download

**Workflow:**

Data preprocessing & tokenization

Model training & evaluation

Save & load fine-tuned model

Goal: Automate  resume shortlisting for recruiters.

------

##  **🛠 Technologies Used**

Python 3.9+

Hugging Face Transformers, dataset, and evaluate.

-------

##  **💻 Installation**
pip install transformers datasets

-----

## **🚀 How to Run**
**1. NLP Pipelines**

Open pipelines/pipelines.ipynb in Google Colab or Kaggle.

Install dependencies (if needed):

pip install transformers datasets


Run all cells to view outputs for Sentiment Analysis, Zero-Shot Classification, Question Answering, Text Generation, Summarization, and Translation.

**2. Fine-Tuning – Resume Screening**

Open fine_tuning/resume_screening_bert.ipynb in Kaggle (recommended).

The notebook is already coded and ready to run.

If your dataset is not included, upload it manually in Kaggle.

Run all cells to train and evaluate the model.

Save the fine-tuned model output for later use.
