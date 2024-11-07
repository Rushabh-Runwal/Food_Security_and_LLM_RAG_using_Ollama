# Food Security Research with LLM RAG using Ollama

This notebook demonstrates how to build a research assistant for food security analysis using Local Large Language Models (LLMs) with Retrieval Augmented Generation (RAG) through Ollama.

## Overview

This project implements a specialized research assistant that helps analyze food security documents using local LLMs, providing accurate and contextual responses based on the provided research materials.

## Steps in the Notebook

1. **Environment Setup**
   - Installation of required dependencies
   - Setting up Ollama and necessary Python packages
   - Configuration of working environment

2. **Data Preparation**
   - Loading food security research documents
   - Text preprocessing and cleaning
   - Document chunking for efficient retrieval

3. **Vector Database Implementation**
   - Creation of vector embeddings
   - Setting up Chroma DB for document storage
   - Implementation of similarity search functionality

4. **RAG Pipeline Configuration**
   - Integration with Ollama LLM
   - Setup of retrieval chain
   - Configuration of prompt templates

5. **Query Interface**
   - Implementation of research query system
   - Response generation with context
   - Result formatting and presentation

## Usage

The notebook provides a step-by-step implementation that allows users to:
- Load their own food security research documents
- Create a knowledge base using vector embeddings
- Query the system with research questions
- Receive contextual responses based on the provided documents

## Requirements

- Python 3.8+
- Ollama
- ChromaDB
- LangChain
- Required research documents in text format

## Getting Started

1. Install Ollama on your system
2. Clone this repository
3. Install the required dependencies
4. Run the notebook cells sequentially
5. Start querying your research documents

## Output

The system provides:
- Contextual answers to research questions
- Source citations from the documents
- Confidence scores for responses
- Related document references

This implementation enables researchers to efficiently analyze food security documents and extract relevant insights using local LLM capabilities.
