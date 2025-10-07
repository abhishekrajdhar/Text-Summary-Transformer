# 🧠 Pegasus Fine-Tuning on SAMSum Dataset

Fine-tuning **Google’s Pegasus model** for **abstractive text summarization** of conversational data (dialogues) using the **SAMSum dataset**.

---

## 🚀 Project Overview
This project fine-tunes the **`google/pegasus-large`** model to generate human-like summaries of dialogues from the **SAMSum dataset**.  
It uses the Hugging Face `transformers`, `datasets`, and `evaluate` libraries with full **GPU acceleration** and supports both **Colab** and local environments.

---

## 📊 Dataset
- **Name:** [SAMSum](https://huggingface.co/datasets/samsum)  
- **Description:** A collection of ~16k English dialogues with corresponding human-written summaries.  
- **Usage:**
  ```python
  from datasets import load_dataset
  dataset = load_dataset("samsum")
👤 Author

Abhishek Dubey
AI/ML Engineer | Data Scientist | CV Engineer
