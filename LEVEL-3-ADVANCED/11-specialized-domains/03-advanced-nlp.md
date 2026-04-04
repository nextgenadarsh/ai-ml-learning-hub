# Advanced NLP — Transformers & Applications

## Overview
Advanced NLP covers transformer architectures, fine-tuning large language models, embeddings, retrieval-augmented generation (RAG), sequence labeling, and evaluation metrics for NLP.

## Learning Objectives
- Understand transformer internals (self-attention, positional encodings)
- Fine-tune pre-trained language models for classification and generation
- Use embeddings and similarity search for retrieval
- Implement RAG using vector stores and chunking strategies
- Apply sequence labeling (NER), summarization, and translation

## Notebooks / Sections
1. Transformer internals — attention, multi-head, FFN
2. Fine-tuning — classification and generation with Hugging Face
3. Embeddings & Vector Stores — building a retrieval pipeline
4. RAG — put it all together (indexing, prompt design)
5. Evaluation — BLEU, ROUGE, perplexity, human eval

## Example: Fine-tuning with Hugging Face
```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification, Trainer, TrainingArguments

model_name = 'distilbert-base-uncased'
tokenizer = AutoTokenizer.from_pretrained(model_name)
model = AutoModelForSequenceClassification.from_pretrained(model_name, num_labels=2)

# Dummy dataset
texts = ["I love this", "I hate this"]
labels = [1, 0]
encodings = tokenizer(texts, truncation=True, padding=True)

# Training loop with Trainer omitted for brevity; follow HF docs
```

## Exercises
- Fine-tune a sentiment classifier on SST-2
- Build a RAG pipeline using FAISS or Pinecone
- Evaluate summarization quality with ROUGE and human checks

---

> Links: Hugging Face, LangChain RAG examples, FAISS documentation.