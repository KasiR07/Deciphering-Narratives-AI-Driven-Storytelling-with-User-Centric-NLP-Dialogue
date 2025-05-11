# Deciphering Narratives: AI- Driven Storytelling with User - Centric NLP Dialogue

## Overview
This project demonstrates an AI-driven storytelling system that creates immersive narratives based on user input. It showcases the system's responsiveness, adaptability, and seamless integration of user creativity into story generation.

## Demonstration Setup
- **Environment**: Deployed on AWS using Amazon SageMaker for optimal efficiency.
- **Backend**: Utilizes Facebook AI Similarity Search (FAISS) for efficient context retrieval.

## Description of Modules

### 📖 Large Language Model
Core of the system using **Mistral-7B-Instruct** for narrative generation.

### 🔍 Context Retrieval
Involves storing data in **S3**, extracting using **Amazon Textract**, and searching with **FAISS**.

### 📦 Packages Used
- **AWS SageMaker**: Model training and deployment.
- **Lang Chain**: Manages user queries and responses.
- **Amazon Textract**: Extracts text from documents.
- **FAISS**: Efficient similarity search and clustering.

## Interactive Story Creation
Participants interact through a text-based interface, influencing the storyline with prompts. The system dynamically generates narrative content using advanced NLP techniques.

### Key Features:
1. **Initial Prompt Response**: Users provide a starting prompt, and the system generates an introductory passage.
2. **Story Evolution**: As users interact, the narrative adapts based on their inputs.
3. **Visualization Tools**: Key processes, like context retrieval and narrative branching, are displayed to enhance understanding.

## Query and Output
The demonstration includes analyzing generated outputs, showcasing the system's capabilities in interactive storytelling.

## Readability Analysis
Multiple readability scores are utilized to evaluate text generated, including:
- **Flesch Reading Ease**
- **Flesch-Kincaid Grade Level**
- **SMOG Index**
- **Coleman-Liau Index**
- **Automated Readability Index (ARI)**
- **Dale-Chall Readability Score**

## Similarity Score
FAISS is used for efficient similarity search, measuring how closely narrative elements relate to user inputs.

