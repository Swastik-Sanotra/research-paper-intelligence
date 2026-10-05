# Research Paper Intelligence System

## 1. Problem

Researchers and students often need to read and compare many research papers to find specific information such as methodologies, datasets, evaluation metrics, results, and limitations.

Traditional keyword search is often insufficient because the relevant information may be expressed using different terminology.

This project aims to build an AI-powered research assistant that allows users to search, question, and compare a collection of research papers using semantic retrieval and Retrieval-Augmented Generation (RAG).

## 2. Target Users

* Students
* Researchers
* ML/AI practitioners
* Anyone studying a technical research topic

## 3. Initial Domain

The initial paper collection will focus on AI/ML research, with particular emphasis on:

* MRI reconstruction
* CG-SENSE
* MoDL
* U-Net
* fastMRI
* ISTA-based reconstruction
* Variational and model-based deep learning methods

## 4. Core Features

1. Upload and process research papers.
2. Extract text and document metadata.
3. Split papers into meaningful chunks.
4. Generate vector embeddings.
5. Perform semantic retrieval.
6. Answer questions using retrieved paper content.
7. Provide citations containing the paper, page, and relevant passage.
8. Refuse to answer when sufficient evidence cannot be found.
9. Compare information across multiple papers.
10. Extract structured information such as datasets, methods, metrics, and limitations.

## 5. Success Criteria

The system should:

* Retrieve relevant passages for research questions.
* Provide answers grounded in the uploaded papers.
* Provide accurate citations.
* Identify questions that cannot be answered from the available papers.
* Support comparison across multiple papers.
* Be evaluated using a manually constructed question-and-answer benchmark.

## 6. Planned Technology

* Python
* PyMuPDF
* Sentence Transformers
* FAISS
* BM25
* Cross-encoder reranking
* LLM API
* Pydantic
* FastAPI
* Streamlit
* Docker
* GitHub Actions

## 7. Important Constraint

This project is an educational and research prototype. Its answers should be grounded in the provided papers, and its limitations and evaluation results will be documented honestly.
