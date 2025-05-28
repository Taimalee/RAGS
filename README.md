# RAG Pipeline

## Overview
This project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) pipeline. It ingests documents (e.g., PDFs) from local storage and AWS S3, creates semantic embeddings, stores them in vector databases, and builds retrieval-based question–answering flows using LangChain and OpenAI models.

## Features
- Document ingestion from local directories and S3 buckets
- Preprocessing and chunking of text for efficient embedding
- Generation of semantic embeddings using OpenAI embeddings
- Storage and indexing in ChromaDB and Pinecone
- Fast similarity search for retrieval
- Customizable RAG chains with LangChain’s retrieval and generation modules
- Flexible prompt templates for dynamic Q&A

## Prerequisites
- Python 3.8 or higher
- AWS credentials configured (for S3 access)
- OpenAI API key
- Pinecone API key (if using Pinecone)
