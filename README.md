# What is Langchain

Langchain is an open-source framework for developing applications powered by larger language models(LLMs)

If you want to build an application based on an LLM, LangChain is the framework that helps you build it

Let's say you want to build a PDF reader app with an AI chat assistant. Whatever questions you ask, they will be answered based on your PDF
<img width="2283" height="927" alt="image" src="https://github.com/user-attachments/assets/53034c84-6e32-4471-9b72-31e5029f3d48" />

Architecture to build this app 
<img width="933" height="1340" alt="image" src="https://github.com/user-attachments/assets/b9474f05-f108-4a0e-b6cc-558a13d4980c" />
<img width="2341" height="1122" alt="image" src="https://github.com/user-attachments/assets/2a55e830-5e6b-46b3-84c4-5641c7d7bc09" />
so Orchestrating Multiple Components (The Role of LangChain)

The system involves many moving components such as AWS S3, text splitters, embedding models, vector databases, and LLM APIs. It also includes multiple tasks like loading documents, splitting text, generating embeddings, managing databases, retrieving relevant data, and interacting with the LLM.

Manually coding these interactions from scratch is complex, especially when switching providers (for example, changing from OpenAI to Google’s LLM or from AWS to GCP, or replacing embedding models). LangChain provides built-in functionalities that enable plug-and-play interaction between components. It handles boilerplate code and orchestration, allowing developers to focus on their core business ideas instead of infrastructure.

---

## Benefits of LangChain

### 1. Chains Concept

LangChain allows developers to chain multiple components and tasks into structured pipelines. The output of one component automatically becomes the input for the next. This simplifies workflows such as document loading, text splitting, embedding, and retrieval.

### 2. Model-Agnostic Development

It enables easy switching between different LLMs or embedding models with minimal code changes. This flexibility allows developers to focus more on business logic rather than technical dependencies.

### 3. Complete Ecosystem

LangChain offers a wide variety of document loaders, text splitters, embedding models, and vector database integrations. It ensures compatibility with multiple tools and services, making development faster and smoother.

### 4. Memory and State Handling

LangChain helps solve the problem of LLMs forgetting previous context. It allows applications to maintain conversational memory so models can understand follow-up questions without users needing to repeat context.

---

## What Can You Build with LangChain?

### 1. Conversational Chatbots

These chatbots handle first-level customer communication for internet-based companies. They can manage large-scale customer queries and reduce support costs. When they cannot resolve an issue, they escalate it to human agents.

### 2. AI Knowledge Assistants

These are chatbots trained on company-specific or user-specific data. For example, a chatbot on an educational platform that answers student questions based on course content.

### 3. AI Agents

These are advanced systems that not only chat but also perform actions and use tools. For example, an AI agent that books flights based on simple commands. AI agents are considered one of the most important future trends in AI.

### 4. Workflow Automation

LangChain can automate personal, professional, and enterprise workflows using LLMs.

### 5. Summarization and Research Tools

These tools simplify research papers, books, and large documents. They overcome context-length limitations and allow companies to build private AI tools that securely process internal data.

---

## Alternatives to LangChain

Components on langchain

<img width="1648" height="813" alt="image" src="https://github.com/user-attachments/assets/8c04aa6b-4883-44ec-b0fd-699177c3e90d" />


LangChain is not the only framework for building LLM applications. Two popular alternatives are:

- LlamaIndex
- Haystack

The choice of framework depends on factors like pricing, infrastructure, scalability, and specific project needs.

# MODELS

<img width="1767" height="113" alt="{96FCA285-DB73-4EAA-B46F-AE80EA94D3D0}" src="https://github.com/user-attachments/assets/3e69ac8b-60c3-4b8c-9400-9d9b1ba21b6c" />

 It addresses the problem of different LLM providers having different API implementations by offering a unified way to communicate, making it easy to switch between models with minimal code changes. LangChain supports two types of models:

<img width="2410" height="1244" alt="image" src="https://github.com/user-attachments/assets/63e28e3e-8122-4dee-8a7f-f6117b5ab250" />


LangChain supports two types of models:

- **2 types of language models**
- **Language Models (LLMs):** These are text-in, text-out models used for applications like chatbots and AI agents. it sloves the problem of NLU & CATG
- **CHAT MODELS:. A Chat Model is an LLM fine-tuned specifically for conversation, using dialogue history and instruction-following to provide interactive, coherent, and context-aware responses, such as in chatbots or virtual assistants**

<img width="2216" height="1239" alt="image" src="https://github.com/user-attachments/assets/b8020ef0-9816-41bb-a649-b99bb4f3aeab" />


- **Embedding Models:** These models take text as input and output a vector, primarily used for semantic search.

<img width="2822" height="1372" alt="image" src="https://github.com/user-attachments/assets/1f33fb78-9a31-42db-9a8a-928d2f07cb5d" />

<img width="1117" height="1391" alt="image" src="https://github.com/user-attachments/assets/1e663e64-77d4-4711-898e-6655c4c64105" />



.
