# LangChain Mastery: Building Context-Aware AI Applications


## Overview

LangChain is a framework designed to simplify the creation of applications using large language models (LLMs). This repository covers everything from basic chains to advanced autonomous agents, specifically integrating with **Google Gemini** and **OpenAI**.

## Tech Stack

* **Framework:** LangChain (Python/JS)
* **LLMs:** Google Gemini (Gemini 1.5 Pro/Flash), OpenAI GPT-4
* **Orchestration:** LangGraph (for cyclic workflows)
* **Vector Databases:** Pinecone / ChromaDB / FAISS
* **Tools:** n8n for automation, DuckDuckGo Search, Wikipedia API

## 🧩 Key Features Implemented

### 1. Model I/O
Managing prompts, connecting to different LLMs, and parsing the output into structured formats (JSON, Pydantic).

### 2. Retrieval Augmented Generation (RAG)
Building a "Chat with your Data" system:
* **Document Loaders:** PDF, CSV, and Web URLs.
* **Text Splitters:** Recursive Character Splitting for better context.
* **Embeddings:** Using Google Generative AI Embeddings.
* **Vector Stores:** Efficient storage and retrieval.

### 3. Chains & LCEL
Using **LangChain Expression Language (LCEL)** to compose complex chains with a declarative syntax.

### 4. Agents & Tools
Creating autonomous agents that can:
* Search the web for real-time information.
* Execute Python code for mathematical calculations.
* Interact with external APIs via n8n.
```text
 I am tauheed


## 📁 Repository Structure

```text
├── 01_Prompt_Templates/      # Crafting effective prompts
├── 02_RAG_Systems/           # PDF Chatbots & Knowledge bases
├── 03_Agentic_Workflows/     # Autonomous agents with tools
├── 04_Memory/                # Managing conversation history
└── requirements.txt          # Project dependencies


`Tauheed Ahmad Shah`
