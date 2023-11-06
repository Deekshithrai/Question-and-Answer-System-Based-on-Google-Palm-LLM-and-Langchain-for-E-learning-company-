# Question and Answer System Based on Google Palm LLM and Langchain for E-learning company  



## Overview

This is an end-to-end LLM project based on Google Palm and Langchain. We are building a Q&A system for an e-learning company called Codebasics. Codebasics offers data-related courses and bootcamps, serving thousands of learners who use Discord and email to ask questions. Our system provides a Streamlit-based user interface for students to ask questions and get answers.
![Screenshot (1)](https://github.com/Deekshithrai/Question-and-Answer-System-Based-on-Google-Palm-LLM-and-Langchain-for-E-learning-company-/assets/144473857/3b2515df-a140-4ce3-8984-238c4262f169)

## Project Highlights

- Utilizes a real CSV file of FAQs currently used by Codebasics.
- Empowers the Codebasics human staff to assist course learners more efficiently.
- Implements an LLM-based question and answer system to reduce the workload of human staff.
- Enables students to ask questions directly and receive answers within seconds.

## What technologies and concepts we used



- Langchain + Google Palm: Leveraging LLM for Q&A.
- Streamlit: Building the user interface.
- Huggingface instructor embeddings: Using text embeddings.
- FAISS: Working with a vector database.

## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py

```

2.The web app will open in your browser.

- To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created.

- Once knowledge base is created you will see a directory called faiss_index in your current folder

- Now you are ready to ask questions. Type your question in Question box and hit Enter
## Sample Questions
  - Do you guys provide internship and also do you offer EMI payments?
  - Do you have javascript course?
  - Should I learn power bi or tableau?
  - I've a MAC computer. Can I use powerbi on it?
  - I don't see power pivot. how can I enable it?

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.
