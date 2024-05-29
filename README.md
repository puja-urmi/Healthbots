# MedBot
MedBot is an innovative healthcare chatbot project that leverages large Language Models along with Retrieval-Augmented Generation (RAG) from trusted databases created from PubMed datasets to facilitate seamless and intuitive communication in the realm of medical assistance. Designed to enhance the interaction between users and healthcare information, MedBot offers immediate responses to inquiries related to health, wellness, and medical queries. This intelligent chatbot employs RAG, natural language processing, and understanding to provide accurate and personalized responses, making it a reliable companion for individuals seeking information on symptoms, medications, and general healthcare advice. MedBot aims to bridge the gap between users and healthcare knowledge, offering a convenient and accessible platform for health-related conversations.

## Project Overview
This project utilizes Large Language Models with Retrieval-Augmented Generation (RAG), trained on reliable medical datasets collected from PubMed. The bot demonstrates impressive performance metrics, including:

96.7% Content Precision
95% Context Recall
85% Faithfulness
73% Answer Relevancy
69.4% Answer Correctness

<img width="499" alt="Screen Shot 2024-05-29 at 12 30 15 PM" src="https://github.com/puja-urmi/MedBot-LLM-RAG/assets/150852458/8d1a6b24-f5b0-4cc2-9c94-02a6d9ca77a7">

### Example Responses
<img width="1009" alt="Screen Shot 2024-05-29 at 12 28 17 PM" src="https://github.com/puja-urmi/MedBot-LLM-RAG/assets/150852458/73340c9a-f732-40de-9570-c9c23c375d94">

## Notebook Breakdown of 'MedBot.ipynb':

### Importing Required Resources including Data
Identifying and bringing in all necessary tools and resources required for the project, including programming languages, machine learning frameworks, data collection tools, and other dependencies. Collecting and preparing data relevant to the project, including data cleaning, preprocessing, and structuring the data in a format suitable for analysis or modeling.

### Creating a Vector Database Using Only the Contexts
Transforming the collected data into numerical vectors while preserving semantic meaning, typically using word embedding models or contextual embedding models to represent words or sentences as dense vectors.

### Testing the Vector Database: 
Validating the effectiveness of the vector database by querying it with known inputs and verifying that the retrieved vectors match expectations.

### Testing the Vector Database with Paraphrased Questions 
Assessing the robustness of the vector database to handle paraphrased queries and verifying its ability to accurately retrieve relevant vectors even when the query is rephrased or expressed differently.

### Creating the Retrieval-Augmented Generation (RAG) Pipeline Using LANGCHAIN 
Building a pipeline that integrates retrieval and generation techniques using LANGCHAIN, based on the vector database.

### Evaluating the RAG Pipeline Using RAGAS
Assessing the effectiveness of the RAG pipeline in generating relevant responses to queries using RAGAS (Retrieval Augmented Generation Assessment Suite) or a similar evaluation framework.

### Performance Measures and Evaluation
Calculating various metrics to assess the efficiency and effectiveness of the RAG pipeline, including faithfulness, context precision, context recall, answer similarity, answer relevancy, and answer correctness. Summarizing and analyzing the evaluation results, highlighting the performance of the RAG pipeline based on the calculated metrics.
