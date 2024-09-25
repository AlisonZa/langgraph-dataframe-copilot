# Project Structured Data Agentic AI 🤖 [EN]

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

   `output = graph.invoke({"user_query": "Your Query Here"})` 

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



# Projeto de IA Agente com Dados Estruturados 🤖 [PT]

## Visão Geral:
O projeto tem como objetivo construir um agente confiável com LangGraph que ajuda não cientistas de dados em tarefas simples. 🌟

### Funcionalidades
O agente utiliza um REPL Python que pode executar código relacionado a atividades como:
* Visualização de Dados 📊
* Análise Exploratória de Dados (EDA) 🔍

### Conceitos Explorados
* Feedback humano no processo 👥
* Grafos, nós e roteadores do LangGraph 🌐
* Engenharia de prompts 📝
* Saídas estruturadas 📋

### Tecnologias Utilizadas:
* **LangChain** como o Orquestrador de IA 🔗
* **LangGraph** Framework de IA Agente 🧠
* **ChatGroq** como Cliente LLM 💬
* **llama3-groq-70b-8192-tool-use-preview** LLM 🦙
* **Pandas** para manipulação de dados 📈
* **Matplotlib** para visualização de dados 🖼️

## Começando:
1. Abra o notebook no Google Colab.
2. Acesse os Secrets:
   
   ![Demonstração](https://github.com/AlisonZa/langgraph-dataframe-copilot/blob/c13fc398a5f19e890599aa924fbe780e4b535c8f/SecretKeys.png)

Insira duas variáveis Secret: LANGCHAIN_API_KEY e GROQ_API_KEY, no campo de valores, cole suas chaves de API.

4. Na segunda célula, altere o URI para a do seu dataframe.
   
   ![imagem](https://github.com/user-attachments/assets/40149026-d99c-4d26-9cbf-a6c752ff071a)

6. Execute todas as células.

7. Agora, você pode usar o agente para responder perguntas sobre seu dataset com:

   `output = graph.invoke({"user_query": "Sua pergunta aqui"})`

## Melhorias Futuras:
* Fornecer ao analista prompts para quaisquer erros que ocorram. Atualmente, o usuário deve passar manualmente. ⚠️
* Adicionar novas estruturas de dados para aumentar a funcionalidade. 🚀

## Exemplo de Uso:

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

