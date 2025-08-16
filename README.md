# Hugging Face Transformers – NLP Projects

This repository contains my learning and practice projects using the **Hugging Face Transformers** library.  
Currently, it includes:

## 📌 Contents
### 1. **Pipelines Project**  
Demonstrates the use of `transformers.pipeline` for multiple NLP tasks, grouped under:
- **Encoder Models** 
- **Decoder Models** 
- **Encoder–Decoder Models** 

**Implemented Tasks & Example Models**
| Task | Example Models |
|------|----------------|
| Sentiment Analysis | `distilbert-base-uncased-finetuned-sst-2-english` |
| Zero-Shot Classification | `facebook/bart-large-mnli` |
| Question Answering | `distilbert-base-cased-distilled-squad` |
| Text Generation | `gpt2` |
| Summarization | `facebook/bart-large-cnn` |
| Translation | `Helsinki-NLP/opus-mt-en-fr` |

---
(UPCOMING)
### 2. **Fine-tuning: Resume Screening Model**  
Fine-tunes a Transformer model to classify resumes into categories for recruitment screening.

- **Base Model:** `bert-base-uncased` (can be replaced as needed)  
- **Approach:** Hugging Face **Trainer API**  
- **Dataset:** Custom dataset with labeled resumes (structured text format)  
- **Workflow:**
  1. Data preprocessing & tokenization
  2. Model training & evaluation
  3. Save & load fine-tuned model  
- **Goal:** Automate initial resume shortlisting for recruiters.

---
## Technologies Used
- **Python 3.9+**
- **Hugging Face Transformers**

---

##  Installation
```bash
pip install transformers

---

## **How to Run**

### 1. NLP Pipelines
1. Open `pipelines/pipelines.ipynb` in Google Colab
2. Install dependencies:
   pip install transformers datasets
3. Run all cells to view outputs for Sentiment Analysis, Zero-Shot Classification, Question Answering, Text Generation, Summarization, and Translation. 

(UPCOMING)
### 2. Fine-Tuning – Resume Screening
1. Open `fine_tuning/resume_screening_trainer.ipynb` in Google Colab
2. Install dependencies:
   pip install transformers datasets
3. Upload your dataset or load it from the Hugging Face Hub.
4. Run all cells to train and evaluate the model.
