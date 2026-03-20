# rag-for-student-policy-qa
RAG-based question answering system built on a university student handbook using LangChain, ChromaDB, semantic retrieval, re-ranking and local LLaMA-2 inference

# RAG for Student Policy Question Answering  

This project builds a Retrieval-Augmented Generation (RAG) system designed to help students quickly find accurate answers from a university student handbook using natural language queries.

The system improves response reliability compared to standalone large language models by combining semantic search, re-ranking and local LLM inference.

---

## Project Objective  

University handbooks are often long and difficult to navigate.  
This project aims to design an intelligent assistant that can:

- Understand student queries in natural language  
- Retrieve the most relevant policy sections  
- Generate grounded, context-aware answers  
- Reduce hallucination risk in academic policy interpretation  

---

## System Architecture  

The RAG pipeline includes:

1. PDF ingestion and text preprocessing  
2. Intelligent chunking with contextual overlap  
3. Semantic embedding generation  
4. Vector storage using ChromaDB  
5. Maximum Marginal Relevance retrieval  
6. Cross-encoder re-ranking  
7. Token-safe context construction  
8. Step-back prompting strategy  
9. Response generation using a quantised LLaMA-2 local model  

---

## Evaluation Approach  

The system performance is evaluated through:

- BERTScore similarity analysis  
- ROUGE metric comparison  
- Manual rubric-based answer quality assessment  

Results show improved factual grounding and answer relevance when using the RAG pipeline compared to LLM-only responses.

---

## Tech Stack  

- Python  
- LangChain  
- ChromaDB  
- SentenceTransformers  
- HuggingFace Transformers  
- CTransformers  
- LLaMA-2 (local inference)  
- Pandas  
- Matplotlib  

---

## Repository Structure  
