# Smart Shopping Assistant with Retrieval Augmented Generation (RAG)

## Project Description

This project builds a smart shopping assistant using a Retrieval Augmented Generation (RAG) approach. It leverages the LangChain framework and Google Generative AI to answer questions about a product dataset. The system processes a CSV file containing product information, such as availability and price, and stores it in a Pinecone vector database. Users can then query the system with natural language questions, and the system retrieves relevant product information to provide accurate answers.

## Key Features

1. **Data Ingestion and Processing**:

   - Loads product data from a CSV file using LangChain's `CSVLoader`.
   - Splits the data into smaller chunks and creates embeddings using Google Generative AI Embeddings.

2. **Vector Database**:

   - Stores the embeddings in a Pinecone vector database for efficient similarity search and retrieval of relevant product information.

3. **Retrieval Augmented Generation (RAG)**:

   - Uses LangChain's RAG pipeline to retrieve relevant product information from the vector database based on user queries.

4. **Question Answering**:

   - Employs a Google Generative AI chat model to generate answers based on the retrieved information and the user's question.

5. **Natural Language Interface**:
   - Allows users to interact with the system using natural language questions.

## Technical Components

- **LangChain**: A framework for developing applications using large language models.
- **Google Generative AI**: A suite of large language models from Google, including embeddings and chat models.
- **Pinecone**: A vector database for storing and searching embeddings.
- **Python**: The programming language used for the project.

## Potential Use Cases

- **Customer Support**: Provide customers with instant answers to product-related questions.
- **Product Discovery**: Help customers find products that meet their needs.
- **Inventory Management**: Track product availability and pricing.
- **Market Research**: Analyze customer preferences and trends.

## Benefits

- **Improved Customer Experience**: Provide customers with a more convenient and informative shopping experience.
- **Increased Efficiency**: Automate product-related information retrieval and reduce manual effort.
- **Better Decision-Making**: Provide insights into customer behavior and product performance.

## Project Status

The project is currently in the development phase. All core functionalities, including data ingestion, storage, retrieval, and question answering, have been implemented.

### Future Work

- Enhance the system's natural language understanding capabilities.
- Expand the product dataset.
- Deploy the system to a production environment.

---
