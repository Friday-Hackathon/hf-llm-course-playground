# Hugging Face LLM Course – Learning Playground

🧪 This repo tracks my progress through Hugging Face's LLM course.  
Each chapter is paired with code notebooks, markdown notes, and examples.

## Chapters Completed
- Chapter 1: Transformers & Attention
- Chapter 2: Tokenizers & Sentiment Classification
- Chapter 3: Summarization & Question Answering  
### 📚 Learning Goals
- [x] Hugging Face Chapter 1: Transformers & Attention
- [x] Hugging Face Chapter 2: Tokenizers & Sentiment Classification
- [X] Hugging Face Chapter 3: Pretraining & Masked Language Models
- [ ] Stanford CS224n Lecture 3: Word Window Classification
- [ ] Stanford CS224n Lecture 4: Neural Networks and Backpropagation

### 🛠️ Hands-on Project
- https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/text_classification.ipynb
- [X] Load and fine-tune `bert-base-uncased` using Hugging Face `Trainer`
- [X] Dataset: IMDb (binary classification)
- [X] Compare: `bert-base-uncased` vs `distilbert-base-uncased` accuracy
- [X] Push notebook to `notebooks/bert-finetune-imdb.ipynb`
- [X] Include training args, evaluation metrics, confusion matrix

### 📂 Project Assets
- [X] Model Card: Add `model_card.md` describing training setup and results
- [X] Experiment Log: Document key learnings and performance differences

### ✍️ Blog Post
- [ ] Title: *What I Learned Fine-Tuning BERT for Text Classification*
- [ ] Include:
  - Why BERT works well for sentiment tasks
  - How backpropagation from CS224n helped me understand the loss landscape
  - Trade-offs between BERT and DistilBERT
- [ ] Publish on LinkedIn or Medium

### 🔗 Resources
- 📘 CS224n Lecture Playlist: [YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rOfhqZuo3tORaN6mTq3FRXa)
- 🤗 Hugging Face Course: [Chapter 3](https://huggingface.co/learn/nlp-course/chapter3/3)
- 📁 [Project Repository](https://github.com/Friday-Hackathon/hf-llm-course-playground)

  
  ### 🧠 Reflection
  - [ ] Blog Post: *What I Learned Fine-Tuning BERT for Text Classification*
## Usage
```bash
conda create -n hf-course python=3.10
pip install transformers datasets torch
