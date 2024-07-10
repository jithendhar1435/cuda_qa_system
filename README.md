CUDA Documentation Q&A System

Project Description
This project implements a sophisticated web crawler, data chunking, vector database creation, retrieval, re-ranking, and question answering system. The system is designed to scrape data from the CUDA documentation website, process and chunk the data based on semantic similarity, store the chunks in a vector database using MILVUS, and provide a user interface for querying the data and receiving answers.

Table of Contents
Installation
Usage
Components
Web Crawler
Data Chunking
Vector Database Creation
Retrieval and Re-ranking
Question Answering
User Interface
Configuration
Contributing
License
Installation
Clone the repository

Install necessary libraries

pip install requests beautifulsoup4 gensim milvus bert-serving-client sklearn sentence-transformers streamlit gradio pymilvus transformers




 code
git clone https://github.com/jithendhar1435/cuda_qa_system.git
cd cuda_qa_system
Create and activate a virtual environment


 code
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
Install the required dependencies


 code
pip install -r requirements.txt
Usage
Run the Web Crawler


 code
python web_crawler.py
Run the Data Chunker


 code
python data_chunker.py
Run the Vector Database Creation


 code
python vector_database.py
Run the Retrieval and Re-ranking


 code
python retriever_reranker.py
Run the Question Answering


 code
python question_answering.py
Run the User Interface (Streamlit)


 code
streamlit run user_interface.py
Run the User Interface (Gradio)


 code
python gradio_interface.py
