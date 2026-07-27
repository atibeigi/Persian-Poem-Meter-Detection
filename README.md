# Persian-Poem-Meter-Detection
NLP assignment focused on Persian poem meter detection using XLM-RoBERTa, Bi-GRU with Attention, and Transformer Encoder-Decoder models.
# Persian Poem Meter Detection (وزن عروضی شعر فارسی)

This repository contains the implementation of a Natural Language Processing (NLP) assignment focusing on detecting and predicting the **metrical patterns (وزن عروضی)** of Persian poetry verses.
                                                       ![Persian Poem Scansion Example](Image.png)


---

## 📌 Project Overview
The goal of this project is to analyze Persian hemistichs (مصراع‌ها) and determine their correct poetic meters. Two main paradigms are explored and implemented:
1. **Text Classification Approach:** Using pre-trained transformer models (**XLM-RoBERTa**) to classify verses directly into their corresponding meter classes.
2. **Sequence-to-Sequence (Seq2Seq) Approach:** Treating meter detection as a sequence translation problem using recurrent architectures and encoder-decoder transformers.

---

## 📂 Repository Structure

```text
├── Poem Meter Dataset/
│   ├── train_samples.csv         # Training dataset partition
│   ├── validation_samples.csv    # Validation dataset partition
│   └── test_samples.csv          # Unlabeled test dataset partition
│
└── notebooks/
    ├── XLMRoBERTa_Classification.ipynb  # Encoder-only classification model
    ├── GRU__Attention.ipynb             # Bidirectional GRU with Attention & Search strategies
    └── transformer.ipynb                # Encoder-Decoder Transformer model
