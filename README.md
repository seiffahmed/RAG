# RAG
Implementing a Retrieval Augmented Generation (RAG) System
# RAG System for Personalized Career Advice

## Overview

This repository contains a prototype RAG (Retrieval-Augmented Generation) system designed to provide personalized skill recommendations and career advice based on job queries. The system integrates data preparation, retrieval using Elasticsearch with ElastiKNN, and generation using Phi-3 - Mini 4k Instruct from Hugging Face Transformers.

## Components

- **Data Preparation:** Cleans and prepares job data for embedding and retrieval.
- **Document Embedding:** Uses Sentence Transformers to encode job details into dense vectors.
- **Retrieval Component:** Utilizes Elasticsearch with ElastiKNN for efficient vector-based search.
- **Generation Component:** Implements Phi-3 - Mini 4k Instruct for generating personalized responses.
- **Integration:** Combines retrieval and generation components into a cohesive RAG system.

## Usage

1. **Setup:** Install dependencies and download required models.
2. **Data Preparation:** Clean and preprocess job data (`sampled_jobs.csv`).
3. **Execution:** Run `rag_system(user_query)` to get personalized career advice.
4. **Evaluation:** Evaluate system performance with test queries (`evaluate_rag_system(test_queries)`).
5. **Documentation:** Refer to this README for detailed system architecture, implementation details, and usage instructions.

## Evaluation Results

### Test Query: How to become a Data Scientist?

- **Recommendation 1:** Strengthen your foundation in mathematics and statistics...
- **Recommendation 2:** Enhance your programming skills in Python and R...
- **Recommendation 3:** Build a strong portfolio of projects showcasing your expertise...

...

## Conclusion

This RAG system demonstrates effective retrieval and generation of personalized career advice. Further optimizations and evaluations can enhance its performance and relevance.

