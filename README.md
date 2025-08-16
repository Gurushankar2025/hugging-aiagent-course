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

**##  How to Run**

This repo contains **Google Colab notebooks** for each project.  
No local setup is required — just open in Colab and run.

**### 1 NLP Pipelines (Multiple Tasks in One Notebook)**
**File:** `pipelines/pipeline.ipynb`  

**Run:**
1. Open the notebook in Google Colab.
2. Select `Runtime` → `Run all`.
3. Each section in the notebook will demonstrate one task.

---

**### 2 Fine-tuning: Resume Screening Model**
**File:** `fine_tuning/resume_screening_trainer.ipynb`


**Run:**
1. Open the notebook in Colab.
2. Upload your dataset or use a sample.
3. Run all cells to train and evaluate the model.
