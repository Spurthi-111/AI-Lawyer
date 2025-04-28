# AI-Lawyer Chatbot: A Retrieval-Augmented Generation (RAG) System for PDF Querying
Welcome to AI-Lawyer, a powerful Retrieval-Augmented Generation (RAG) system that allows you to interact with PDFs and get accurate answers to complex questions about your documents. This project integrates the capabilities of Deepseek, LangChain, Streamlit, and Groq Cloud APIs for a user-friendly and intelligent document assistant experience.

## Features
Retrieve answers from PDFs: Chat with your local PDF files and get detailed answers based on the content.

Deepseek-powered reasoning: Leverage Ollama's Deepseek-r1 LLM model, known for its strong reasoning capabilities.

LangChain integration: Enhance the retrieval process using LangChain's powerful pipeline to fetch relevant data.

Interactive UI with Streamlit: A user-friendly interface that allows you to query PDFs in real time.

Cloud Integration: API keys from Groq Cloud are used to integrate cloud-powered computation for improved performance.

## Technologies Used
Deepseek: Ollama's LLM model that helps with strong reasoning.

LangChain: A framework for building RAG pipelines and interacting with various document sources.

Streamlit: A framework to create interactive web applications for real-time querying of PDFs.

Groq Cloud API: Used for accessing powerful cloud resources for enhanced computational performance.

## Getting Started
To run the AI-Lawyer project, follow these steps:

1️⃣ Clone the Project
    
    git clone <url>


2️⃣ Open Terminal & Activate Virtual Environment

    cd filemane
    
    pipenv shell

    
3️⃣ Install & Pull the Ollama Model
   Make sure you have Ollama installed, then pull the required model:

    ollama pull deepseek-r1:1.5b

    
4️⃣ Create a .env File
   In the project root directory, create a file named .env and add your Groq API key:

    GROQ_API_KEY="your GROQ_API_KEY"

    
5️⃣ Run the Vector Database Script

    python vector_database.py


6️⃣ Run the RAG Pipeline Script

    python rag_pipeline.py
    
📝 Note:
If you encounter an error about a missing API key in Command Prompt (cmd.exe), run:

    set GROQ_API_KEY=your GROQ_API_KEY


7️⃣ Launch the Frontend
   Finally, start the Streamlit app:

    streamlit run frontend.py
