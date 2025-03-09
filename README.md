

<h1>Azure & Langchain RAG Pipeline</h1>

<h2>Description</h2>
This is a Retrieval-augmented generation pipeline implementation using Azure Cognitive Search, Langchain and Hugging Face Transformers.

This project aims to implement a more effective search method for large text datasets using a vector database. Instead of relying on simple keyword matching, this approach leverages embeddings—numerical representations of text that capture semantic meaning.

The project is designed as a web application where users can input queries through a text field and retrieve relevant results from the vector database. Additionally, a Large Language Model (LLM) may be integrated to generate responses based on the retrieved data. 

The application communicates with a local Flask endpoint that processes the query. For this project, Azure AI Search serves as the vector database, though an open-source alternative may be considered in the future. The text data is pre-processed before being stored in Azure Blob Storage.

User authentication and management are handled via SQLAlchemy, which simplifies interactions between Python and an SQLite database.

<br />
