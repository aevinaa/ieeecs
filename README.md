# Customer Churn Prediction and Campus Assistant
# 🤖 AI/ML Assignments Portfolio

This repository contains solutions to two AI/ML tasks, demonstrating skills across:
- Data analysis & classical machine learning
- Deep learning & explainability
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Agentic AI system design

Each task is structured in progressive levels to show both conceptual understanding and practical implementation.

---

## 📌 TASK 1: Customer Churn Prediction (AI/ML)
### Google Colab Link - https://colab.research.google.com/drive/1v6lRMwhnRu0oe3eEqA34qIo-SVjzADxq?usp=sharing

### 🎯 Objective
To analyze customer churn data, build predictive models, and explain the key factors influencing churn using classical machine learning and neural networks.

---

### 🧩 Level 1: Data Understanding & Exploratory Data Analysis (EDA)
**Goals:**
- Load and clean the dataset
- Handle missing values and data types
- Explore relationships between churn and key features

**Techniques:**
- Pandas, NumPy
- Matplotlib / Seaborn
- Descriptive statistics & visualizations

**Outputs:**
- Cleaned dataset
- EDA plots showing churn patterns across features like tenure, contract type, etc.

---

### 🧩 Level 2: Classical Machine Learning
**Models Implemented:**
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1-score

**Analysis:**
- Comparison of model performance
- Identification of most influential features driving churn

---

### 🧩 Level 3: Neural Networks & Advanced Modeling
**Approach:**
- Implement a Neural Network classifier
- Benchmark performance against classical ML models
- Analyze strengths and limitations

**Explainability:**
- Use SHAP (or similar methods) to interpret model predictions
- Visualize feature contributions


## 📌 TASK 2: 🎓 Intelligent Campus Assistant (LLM + RAG + Agentic AI)
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

