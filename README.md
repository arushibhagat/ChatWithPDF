# Chat with PDF - Retrieval-Augmented Generation (RAG) Application

Chat with PDF is an AI-powered application that allows users to interact with PDF documents via a chatbot interface. By leveraging Retrieval-Augmented Generation (RAG) techniques, the application efficiently extracts relevant information from large PDFs using LangChain, Pinecone vector search, and the Llama 2 model.


## Features
RAG Architecture: Uses retrieval-augmented generation to enhance the accuracy of responses by first retrieving relevant document sections, then generating natural language answers.

Efficient Document Search: Integrates Pinecone vector search for fast and scalable querying over large datasets (up to 500-page documents).

Optimized Embedding Pipeline: Processes document text into vector embeddings for effective search, with performance improvements for faster query responses.

Customizable for Various Use Cases: Easily adapt the chatbot to other document formats by modifying text extraction methods.
