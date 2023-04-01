# GPT-Document-Trained-Chatbot-Builder

GPT-Document-Trained-Chatbot-Builder is a powerful tool that enables users to create AI chatbots capable of answering questions based on the content of provided documents. The chatbots are built using OpenAI's GPT-3.5 and text-embedding-ada-002 models for text understanding and processing. The embeddings generated by text-embedding-ada-002 are stored using Pinecone, a high-performance vector search and storage service.

This tool allows users to upload documents in various formats (such as PDF, Word, or Markdown), extract the text, and train the AI chatbot to understand and respond accurately based on the information in those documents.

## Technology Used

OpenAI GPT-3.5: A powerful language model for generating text and answering questions.
Text-embedding-ada-002: An embedding model used for converting text into numerical vectors.
Pinecone: A scalable, high-performance vector storage and search service.
Python: The backend programming language for processing and training the chatbot.
Flask: A lightweight web framework used for creating the web interface for users to interact with the chatbot.

## Features

Document upload: Users can upload documents in various formats like PDF, Word, Markdown, etc.
Text extraction: The tool automatically extracts text from the uploaded documents.
AI chatbot training: The extracted text is used to train the AI chatbot based on GPT-3.5 and text-embedding-ada-002 models.
Pinecone storage: The embeddings generated by text-embedding-ada-002 are stored in Pinecone for efficient retrieval and matching.
Multilingual support: The chatbot can be trained and answer questions in multiple languages.
Customizable chatbot: Users can provide specific instructions for the chatbot to follow when answering questions.

## Future Scope

Integration with popular chat platforms like Discord, WhatsApp, and Telegram.
Support for more file formats and content sources for training the chatbot.
API access for developers to easily integrate the chatbot into their applications.
Enhanced customization options for the chatbot, including adjusting response style and tone.
Improved performance and scalability for handling large numbers of documents and users.

## Requirements
Python 3.7 or newer
Flask web framework
OpenAI API key
Pinecone API key
Additional Python libraries: pandas, numpy, pdfplumber, docx2txt, markdown2, and requests
To get started, clone the repository and follow the installation instructions in the provided documentation.