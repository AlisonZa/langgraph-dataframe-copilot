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
   ![Uploading image.png…]()
  Insert two secrets variables: LANGCHAIN_API_KEY and GROQ_API_KEY, in the values field, paste your API keys

3. On the second cell, change the uri to the one of your dataframe
   `df = pd.read_csv('https://gist.githubusercontent.com/kevin336/acbb2271e66c10a5b73aacf82ca82784/raw/e38afe62e088394d61ed30884dd50a6826eee0a8/employees.csv')` 
4. Run all the cells
5. Now, you can use the agent to answer questions about your dataset with:
   `# Invoke the graph
    output = graph.invoke({"user_query": "Your Query Here"})` 

## Future Improvements:
* Provide the analyst with prompts for any errors that occur. Currently, the user must pass them manually. ⚠️
* Add new data structures to enhance functionality. 🚀

