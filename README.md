# Project Structured Data Agentic AI 🤖

## Overview:
The project aims to build a reliable LangGraph agent that helps non-data scientists with simple tasks. 🌟

### Features
The agent uses a Python REPL that can run code related to activities such as:
* Data Visualization 📊
* Exploratory Data Analysis (EDA) 🔍

### Explored Concepts
* Human-in-the-loop feedback 👥
* LangGraph graphs, nodes, and routers 🌐
* Prompt engineering 📝
* Structured outputs 📋

### Technologies Used:
* **LangChain** as the AI Orchestrator 🔗
* **LangGraph** Agentic AI Framework 🧠
* **ChatGroq** as LLM Client 💬
* **llama3-groq-70b-8192-tool-use-preview** LLM 🦙
* **Pandas** for data manipulation 📈
* **Matplotlib** for data visualization 🖼️

## Getting Started:
1. Open the notebook on Google Colab.
2. Acess the Secrets:
   
   ![Demonstration](https://github.com/AlisonZa/langgraph-dataframe-copilot/blob/c13fc398a5f19e890599aa924fbe780e4b535c8f/SecretKeys.png)

Insert two secrets variables: LANGCHAIN_API_KEY and GROQ_API_KEY, in the values field, paste your API keys

4. On the second cell, change the uri to the one of your dataframe
   
   ![image](https://github.com/user-attachments/assets/40149026-d99c-4d26-9cbf-a6c752ff071a)


6. Run all the cells

7. Now, you can use the agent to answer questions about your dataset with:

   `# Invoke the graph
    output = graph.invoke({"user_query": "Your Query Here"})` 

## Future Improvements:
* Provide the analyst with prompts for any errors that occur. Currently, the user must pass them manually. ⚠️
* Add new data structures to enhance functionality. 🚀

## Example Usage

Initial query: output = graph.invoke({"user_query": "Plot me a chart of the salary by Manager"})

Output: 
![image](https://github.com/user-attachments/assets/e933d58c-809c-4aa0-89a0-c26f8d4c3d51)

Feedback: change the color to red

Output: 
![image](https://github.com/user-attachments/assets/a79a0977-9bb2-4c4d-a62d-df6272dfacba)


Feedback: rotate the xticks and change the title of the plot to Mean salary by Manager ID

Output: 
![image](https://github.com/user-attachments/assets/0d35c3ab-241e-4539-8219-7c5f7c130164)

Feedback: Put the mean salary as a line chart in this 

Output: 
![image](https://github.com/user-attachments/assets/8664162b-d8df-4464-be9f-e47ca0be9ab7)
