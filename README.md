# Business-Chat-Bot

## Overview
This project builds a question-answering bot that retrieves information from a PDF document using embeddings and vector search. The implementation uses Langchain, Cohere for embedding generation, and Pinecone for vector indexing.

## Usage
- Place your PDF document in the specified directory.
- Run the script to process the document and index it.
- Use the query_qa_bot function to ask questions.

## Challenges Faced
- Embedding Limitations: Cohere has token limits for embeddings. Managing text chunk sizes effectively is crucial.
- API Key Management: Ensured secure handling of API keys. Used environment variables and secrets management.

