# Vector-Search-Database-and-LLM-Mode

Overview
This project is aimed at creating a production-grade application utilizing natural language processing (NLP) techniques to build a text summarizer and quiz app. The application harnesses the power of a vector search database for efficient querying and incorporates large language models (LLM) for understanding and processing textual data. By following the guidelines and instructions in this README, users will learn how to set up the environment, install necessary packages, process documents, store data in a vector search database, and build interactive NLP applications.

Key Features
Text Summarizer: Utilize OpenAI embeddings and LLM models to create a robust text summarization feature.
Quiz App: Convert textual content into a quiz app that leverages vector search database for efficient retrieval and response.
Prerequisites
Python 3.8 or higher
Knowledge of virtual environments (venv)
Basic understanding of NLP concepts and libraries (e.g., Hugging Face Transformers, Pinecone)
Installation
Create a new Python virtual environment:

create -p venv <environment_name>
Activate the created environment:

activate <environment_name>
Install the required packages from the provided requirements.txt file:

pip install -r requirements.txt
Usage
Loading and Processing Documents:

Load PDF documents from a specified directory using the directory loader.
Split the documents into chunks using the recursive character splitter function.
Convert text chunks into vectors using embedding techniques.
Vector Search Database:

Initialize and store embeddings in the vector database using Pinecone.
Retrieve specific queries and obtain matching results using the vector search capabilities.
Text Summarization and Quiz App:

Convert the processed documents into a quiz app or a text summarizer by implementing the specific functionalities and integration with the vector search database.
