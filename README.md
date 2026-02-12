# Next-Gen-NLP-Classifier-Using-Transformer-Models

This project aims to build a **scalable and robust NLP text classification system** that leverages **state-of-the-art transformer models** (e.g., BERT, RoBERTa) to automatically categorize text into multiple classes with high accuracy and minimal manual feature engineering. Transformers model long-range dependencies and semantic context far better than traditional approaches like bag-of-words or TF-IDF.  

The current workflow performs **data loading, preprocessing, and exploratory data analysis (EDA)**, setting the stage for transformer-based fine-tuning in the next steps.

---

## 📌 Project Objectives

- **Preprocess text data** by combining titles with full text and cleaning out missing or empty entries.  
- **Explore the dataset** to understand class balance, text length distributions, and sample content per label.  
- **Visualize key characteristics** such as class distributions and word count histograms.  
- **Prepare the dataset** (train/validation split) for later use with transformer models.  
- **Set up a scalable NLP pipeline** that can later be extended with transformer models for classification.

---

## 🛠️ Get Started

### Installation

```bash
git clone https://github.com/thanusri1601/Scalable-NLP-Classification-System-using-Transformer-Models
cd Scalable-NLP-Classification-System-using-Transformer-Models
pip install -r requirements.txt
