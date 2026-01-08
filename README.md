# ieeecs
# 🎓 Intelligent Campus Assistant (LLM + RAG + Agentic AI)
#### Google Colab Link - https://colab.research.google.com/drive/1M8HlN9tMNGz-Ys8DKag0qE2pATM-LFGK?usp=sharing

## 📌 Objective
To build an intelligent AI assistant that helps students navigate campus life by answering questions related to rules, schedules, facilities, and general queries using modern AI techniques.

The project is designed in **three progressive levels**, evolving from a basic LLM assistant to a knowledge-aware and agentic system.

---

## 🧠 System Architecture

### 🔹 Level 1: Basic AI Assistant (Foundation)
- Uses a pre-trained Large Language Model (LLM)
- Handles simple question–answer interactions
- No external knowledge source

**Flow:**  
User Query → LLM → Natural Language Response

---

### 🔹 Level 2: Knowledge-Aware Assistant (RAG)
- Ingests campus-specific documents (rules, schedules, FAQs)
- Converts documents into embeddings
- Stores embeddings in a vector database (ChromaDB)
- Retrieves relevant context before answering

**Flow:**  
User Query → Vector Search → Context → LLM → Answer

---

### 🔹 Level 3: Agentic Campus Assistant
- Decides when to retrieve documents
- Uses tools (retrieval + LLM)
- Maintains short-term conversational memory
- Handles multi-step reasoning for complex queries

---

## 🛠️ Technologies Used
- Python
- HuggingFace Transformers
- Sentence-Transformers
- ChromaDB (Vector Database)
- Jupyter Notebook

---

## 🚀 How to Run
1. Open the notebook via Link Provided
2. Install dependencies
3. Run all cells sequentially

---

## 🎯 Outcome
This project demonstrates:
- Practical use of LLMs
- Retrieval-Augmented Generation (RAG)
- Basic agentic decision-making
- Scalable AI system design

