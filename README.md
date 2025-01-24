# NLP and LLM Projects Repository

This repository contains notebooks and resources focused on fine-tuning and utilizing large language models (LLMs) for natural language processing (NLP) tasks. The projects here demonstrate how to apply advanced techniques like LoRA (Low-Rank Adaptation) for efficient fine-tuning, as well as how to implement retrieval-augmented generation (RAG) workflows for question generation and answering.

---

## Notebooks

### 1. **Fine-Tune Gemma Models in Keras using LoRA**
- **Description**:  
  This notebook demonstrates how to fine-tune Gemma models in Keras using **LoRA** (Low-Rank Adaptation). LoRA is a parameter-efficient fine-tuning method that reduces the computational cost and memory requirements of training large models.
- **Key Features**:
  - Fine-tuning large language models with minimal resources.
  - Use of LoRA for low-rank updates.
  - Customizable pipeline for adapting Gemma models to new tasks.

- **Technologies**:
  - Keras
  - LoRA
  - TensorFlow

---

### 2. **Question Generation & Answering from PDF (RAG & LoRA)**
- **Description**:  
  This notebook focuses on implementing a **retrieval-augmented generation (RAG)** pipeline for question generation and answering from PDFs. By combining RAG with LoRA fine-tuning, it enables efficient handling of document-based question-answering tasks.
- **Key Features**:
  - Parsing and extracting content from PDFs.
  - Question generation using LLMs.
  - Retrieval-based answering using relevant document sections.
  - Integration of LoRA for optimized model performance.
  
- **Technologies**:
  - Retrieval-Augmented Generation (RAG)
  - PyPDF2 (or any PDF parsing library)
  - LoRA
  - Hugging Face Transformers

---

