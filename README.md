# **Question-Answering with Astra DB and LangChain: A Vector Search Demo**

## **Overview**
This project demonstrates how to build a question-answering (QA) system using LangChain, OpenAI, and Astra DB. The system processes a PDF document, stores its content in a vector database, and allows interactive querying to retrieve relevant information.


<img width="1472" alt="Untitled" src="https://github.com/Deba951/Querying-PDF-With-Astra-and-LangChain/assets/83878346/5d2c656d-01c1-4a71-bb62-d251ec6cc27b">


## **Introduction**
This project aims to create an efficient QA system by leveraging advanced NLP (Natural Language Processing) techniques. It uses:
- LangChain: A framework for building applications with large language models (LLMs).
- OpenAI: Provides language models and embeddings to process and understand the text.
- Astra DB: A scalable, cloud-native database that stores and retrieves text chunks as vectors.


## **Prerequisites**
To run this demo, ensure you have the following:
1. Serverless Cassandra with Vector Search Database on Astra DB:
       ```
        https://accounts.datastax.com/session-service/v1/login
       ```
    - Obtain a DB Token with the role of Database Administrator.
    - Copy your Database ID. These connection parameters will be required.
    - For detailed instructions, refer here:
           ```
            https://docs.datastax.com/en/astra-db-serverless/get-started/quickstart.html#_prepare_for_using_your_vector_database
           ```
2. OpenAI API Key:
    - You will need an API key from OpenAI for this demo to function.
            ```
            https://cassio.org/start_here/#llm-access
            ```


## **Technologies Used**
- LangChain: Framework for building applications with LLMs.
- OpenAI: Provides the GPT models used for embeddings and language understanding.
- Astra DB: Cloud-native database service by DataStax.
- PyPDF2: Library for reading PDF files.
- Datasets: Hugging Face library for loading and processing datasets.


## **Abbreviations and Definitions**
1. **QA (Question-Answering):** A type of information retrieval that involves answering questions posed by users based on a given dataset or document.
2. **NLP (Natural Language Processing):** A field of AI that focuses on the interaction between computers and human languages.
3. **LLM (Large Language Model):** A type of machine learning model trained on a large dataset of text to understand and generate human-like text.
4. **Vector Store:** A database that stores text data as vectors (numerical representations) to enable efficient similarity search.
5. **Embedding:** A representation of text data in a continuous vector space, often used to measure the similarity between different pieces of text.


**Thank you for visiting my repository! Your interest and support are greatly appreciated.**
