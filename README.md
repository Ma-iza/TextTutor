# TextTutor 📚

TextTutor is a local AI-powered study assistant that uses Retrieval-Augmented Generation (RAG) to answer questions from study materials such as lecture PDFs.

The project uses a locally running Llama 3.2 model through Ollama, allowing questions to be answered using the content retrieved from the user's study material.

## Current Features

* Load lecture notes and study material from PDF files
* Extract and split PDF content using `PyPDFLoader`
* Generate embeddings locally using `nomic-embed-text`
* Store document embeddings using an in-memory vector store
* Retrieve relevant sections of study material based on a question
* Use a local Llama 3.2 model to generate answers from retrieved context
* Answer multiple questions from the loaded study material


## Project Status

🚧 **Currently in development**

The current version focuses on implementing and testing the RAG-based question-answering pipeline.

### Planned Improvements

* [ ] Support multiple uploaded PDFs in a single knowledge base
* [ ] Automatic question and quiz generation
* [ ] Answer evaluation and scoring
* [ ] Interactive quiz mode
* [ ] Streamlit-based user interface
* [ ] Study history and performance tracking
* [ ] Improve retrieval and answer accuracy
* [ ] Deploy the completed application

## Learning Goals

This project is being developed to gain practical experience with:

* Large Language Models (LLMs)
* Retrieval-Augmented Generation (RAG)
* Embeddings and semantic search
* Vector stores
* LangChain
* Local LLM deployment with Ollama
* Building AI-powered applications

## Future Vision

The goal of TextTutor is to evolve from a simple document-based question-answering prototype into an interactive AI study assistant that can understand a student's study material, generate practice questions, evaluate answers, and help identify areas that need revision.
