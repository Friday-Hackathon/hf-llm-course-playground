# Hugging Face LLM Course – Learning Playground

🧪 This repo tracks my progress through Hugging Face's LLM course.  
Each chapter is paired with code notebooks, markdown notes, and examples.

## Chapters Completed
- Chapter 1: Transformers & Attention
- Chapter 2: Tokenizers & Sentiment Classification
- Chapter 3: Summarization & Question Answering
  
### 📚 Week3: Learning Goals
- [x] Hugging Face Chapter 1: Transformers & Attention
- [x] Hugging Face Chapter 2: Tokenizers & Sentiment Classification
- [X] Hugging Face Chapter 3: Pretraining & Masked Language Models
- [X] Stanford CS224n Lecture 3: Word Window Classification
- [X] Stanford CS224n Lecture 4: Neural Networks and Backpropagation

### 🛠️ Hands-on Project
- [Week3 Notebook](https://github.com/Friday-Hackathon/hf-llm-course-playground/blob/main/Week3/Text_Classification_on_GLUE.ipynb)
- [X] Load and fine-tune `bert-base-uncased` using Hugging Face `Trainer`
- [X] Dataset: IMDb (binary classification)
- [X] Compare: `bert-base-uncased` vs `distilbert-base-uncased` accuracy
- [X] Push notebook to `notebooks/bert-finetune-imdb.ipynb`
- [X] Include training args, evaluation metrics, confusion matrix

### 🔗 Resources
- 📘 CS224n Lecture Playlist: [YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rOfhqZuo3tORaN6mTq3FRXa)
- 🤗 Hugging Face Course: [Chapter 3](https://huggingface.co/learn/nlp-course/chapter3/3)
- 📁 [Project Repository](https://github.com/Friday-Hackathon/hf-llm-course-playground)

## ✅ Week 4: Attention, Transformers & First Retrieval-Augmented Generation (RAG) Build

### 📚 Learning Goals
- [ ] **CS224n Lecture 5:** Dependency Parsing and Introduction to Attention
- [ ] **CS224n Lecture 6:** Transformers and Self-Attention in Detail
- [X] **Hugging Face Course Chapter 4:** Transformers API (BERT, GPT-2, etc.)
- [X] Read the paper: *Attention is All You Need* (focus on Section 3: The Transformer architecture)

### 🛠️ Hands-on Project
- [ ] Load and experiment with `pipeline()` for text-generation and question-answering tasks using GPT-2 and BERT
- [ ] Build a **basic RAG pipeline**:
  - Use a small document set (e.g., product FAQs, knowledge base)
  - Create embeddings with `sentence-transformers` or `OpenAIEmbeddings`
  - Implement retrieval with `faiss` or `Chroma`
  - Feed retrieved context into a transformer model for Q&A

### 📂 Project Assets
- [ ] Save notebooks:
  - `notebooks/transformer_api_examples.ipynb` (transformer experiments)
  - `notebooks/basic_rag_pipeline.ipynb` (retrieval-augmented generation)
- [ ] Add `requirements.txt` for easy replication
- [ ] Optional: Deploy RAG pipeline demo to Hugging Face Spaces

### ✍️ Blog Post
- [ ] Title: *"From Transformers to RAG: Building Context-Aware LLMs"*
- [ ] Sections:
  1. What is Attention?  
  2. How Transformers changed NLP  
  3. What is Retrieval-Augmented Generation and why it matters  
  4. My first RAG build and lessons learned
- [ ] Include diagrams: attention mechanism, RAG architecture

### 🔗 Resources
- 📘 [CS224n Lecture 5 Slides](https://web.stanford.edu/class/cs224n/slides/cs224n-2021-lecture5-dep-parsing.pdf)
- 📘 [CS224n Lecture 6 Slides](https://web.stanford.edu/class/cs224n/slides/cs224n-2021-lecture6-transformers.pdf)
- 🤗 [Hugging Face Course Chapter 4](https://huggingface.co/transformers)
- 📄 [Attention is All You Need Paper](https://arxiv.org/abs/1706.03762)
