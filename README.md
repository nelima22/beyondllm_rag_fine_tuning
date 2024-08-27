# Advanced RAG: Fine-Tune Embeddings for Resume Information Retrieval

This project demonstrates the use of fine-tuned embeddings to enhance the contextual understanding of a language model for retrieving and generating relevant information from a resume PDF. By leveraging Beyond LLM and the `FineTuneEmbeddings` class, this project customizes embeddings to better capture the nuances and domain-specific language within the resume.

## Project Overview

The goal of this project is to retrieve specific information from a resume PDF by fine-tuning an open-source embedding model, `BAAI/bge-small-en-v1.5`, on the resume data. This fine-tuning process improves the accuracy and relevance of the Retrieval-Augmented Generation (RAG) pipeline, making it more effective for resume analysis and information extraction.

## Why Fine-Tuning Embeddings?

Fine-tuning embeddings with your specific dataset enhances the contextual understanding of the language model, making it better suited for retrieving and generating relevant information. This process adapts the embeddings to the nuances and domain-specific language present in your data, thereby improving the accuracy and relevance of RAG pipelines.

## Key Features

- **FineTuneEmbeddings Class**: Fine-tune embeddings on a specific dataset to better capture the nuances of the data.
- **BAAI/bge-small-en-v1.5**: Utilizes an open-source embedding model from HuggingFace, fine-tuned for the resume data.
- **Improved RAG Pipeline**: Combines fine-tuned embeddings with a RAG pipeline to achieve accurate and context-aware information retrieval from resumes.

## How It Works

1. **Embedding Generation**: The model generates a dataset of pairs from the resume data for fine-tuning.
2. **Fine-Tuning**: The embeddings are fine-tuned on the specific dataset using the `FineTuneEmbeddings` class.
3. **Resume Information Retrieval**: The fine-tuned embeddings are used in a RAG pipeline to retrieve specific information from the resume PDF.
