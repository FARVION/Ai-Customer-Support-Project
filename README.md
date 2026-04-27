# 🚀 AI Customer Support Intelligence System (ML + GenAI)

## 📌 Overview

An end-to-end AI system that automates customer support operations by combining **Machine Learning** and **Generative AI (RAG)**.

This project predicts ticket priority, estimates resolution time, and generates intelligent responses using past resolved tickets.

---

## 🎯 Problem Statement

Customer support teams face:

* High ticket volume
* Slow response times
* Inconsistent replies

This system solves these issues by:

* Automating ticket classification
* Predicting resolution time
* Generating accurate AI-based responses

---

## 🧠 Features

* 🔹 Ticket Priority Prediction (ML - Classification)
* 🔹 Resolution Time Estimation (ML - Regression)
* 🔹 Smart Response Generation (GenAI - RAG)
* 🔹 Knowledge Retrieval using FAISS
* 🔹 End-to-End Pipeline

---

## ⚙️ Tech Stack

### 🔸 Data Science

* Python
* Pandas, NumPy
* Scikit-learn

### 🔸 GenAI

* OpenAI API
* Sentence Transformers
* FAISS (Vector Database)

### 🔸 Visualization

* Matplotlib
* Seaborn

---

## 📂 Project Structure

```
project/
│
├── data/
│   └── customer_support_tickets.csv
│
├── notebook.ipynb
├── app.py
├── requirements.txt
└── README.md
```

---

## 🔄 Workflow

```
User Query
   ↓
TF-IDF Vectorization
   ↓
ML Models
   → Predict Priority
   → Estimate Resolution Time
   ↓
FAISS Retrieval (RAG)
   ↓
LLM (OpenAI)
   ↓
AI Generated Response
```

---

## 📊 ML Models

### 1️⃣ Priority Prediction

* Algorithm: Logistic Regression
* Input: Ticket Description
* Output: Priority (Low / Medium / High / Critical)

### 2️⃣ Resolution Time Prediction

* Algorithm: Linear Regression
* Input: Ticket Description
* Output: Estimated resolution time (in days)

---

## 🧠 GenAI (RAG)

* Uses past ticket resolutions as knowledge base
* Converts text into embeddings
* Retrieves similar issues using FAISS
* Generates context-aware responses using LLM

---

## 🧪 Example Output

```
Input:
"My product is not working after setup"

Output:
Priority: High  
Estimated Resolution: 2.3 days  
AI Response: Please restart the device and ensure proper setup...
```

---

## ⚡ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Project

### Jupyter Notebook

```bash
Open notebook.ipynb in Google Colab
```

### Streamlit App

```bash
streamlit run app.py
```

---

## 🔑 API Key Setup

Replace with your OpenAI API key:

```python
client = OpenAI(api_key="YOUR_API_KEY")
```

---

## 📈 Future Improvements

* 🔹 Use advanced models (XGBoost, BERT)
* 🔹 Add sentiment analysis
* 🔹 Real-time dashboard (Streamlit / Power BI)
* 🔹 Database integration (MongoDB / PostgreSQL)
* 🔹 Multi-language support

---

## 💼 Resume Impact

**Built an AI-powered customer support system combining ML (classification & regression) with RAG-based GenAI to automate ticket prioritization, resolution prediction, and intelligent response generation.**

---

## 🤝 Contribution

Feel free to fork, improve, and contribute.

---

## 📜 License

MIT License
