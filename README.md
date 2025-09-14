## Local AI Agent – Restaurant Review Assistant

This project is a local AI-powered chatbot that answers customer questions about a pizza restaurant using real customer reviews. It uses LangChain, Ollama, and Chroma for embeddings, retrieval, and LLM Response.

## Features

1.Uses Llama 3.2 (via Ollama) for generating answers.

2.Stores and retrieves restaurant reviews using Chroma Vector Database.

3.Embeds customer reviews with mxbai-embed-large model.

4.Interactive Q&A chatbot in the terminal.

5.Runs fully locally — no external API needed.

## Create and activate virtual environment

 python -m venv venv
 venv\Scripts\activate 

## Install dependencies

pip install -r requirements.txt

## Make sure Ollama is installed

ollama pull llama3.2
ollama pull mxbai-embed-large
