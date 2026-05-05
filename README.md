# 🚨 Real-Time Disaster Response Summarization using LLM + HPC

> ⚡ A scalable AI-powered system that uses **High Performance Computing (HPC)** and **Large Language Models (LLMs)** to process real-time disaster data and generate meaningful summaries for faster decision-making.

---

## 👩‍💻 Author

**Somavaram J Rishika**  
🎓 B.Tech – Artificial Intelligence & Data Science  
🏫 Amrita Vishwa Vidyapeetham  

## 👥 Team Members

- Harikrishna S – CB.AI.U4AID23011  
- Deepak Kumar – CB.AI.U4AID23012   

---

## 🌟 Project Overview (Clear Explanation)

This project is designed to solve a real-world problem:

👉 During disasters (floods, earthquakes, etc.), huge amounts of data come from different sources.  
👉 It is difficult to process and understand this data quickly.  

### 💡 Our Solution:
We built a system that:

- 📡 Collects disaster-related data from multiple APIs **in real-time**
- ⚡ Uses **parallel computing (HPC)** to process data faster
- 🧹 Cleans and standardizes data into a structured format
- 🗄 Stores it efficiently using MongoDB
- 🤖 Uses **LLMs** to generate meaningful summaries
- 🔍 Uses **RAG (Retrieval-Augmented Generation)** for context-aware responses

➡️ Final Output:  
**Clear, accurate, and real-time disaster summaries for decision-making**

---

## 🎯 Objectives

- Reduce delay in disaster data processing  
- Provide real-time summarized insights  
- Improve decision-making using AI  
- Build a scalable and efficient HPC-based pipeline  

---

## ⚙️ System Workflow

```text
🌐 Multiple APIs (Disaster Data)
        ↓
⚡ Parallel Data Collection (AsyncIO)
        ↓
🧹 Data Cleaning & Validation (Pydantic)
        ↓
🗄 MongoDB Storage (Indexed)
        ↓
🧠 HPC Processing (Multiprocessing)
        ↓
🔍 RAG Pipeline (Retrieval + LLM)
        ↓
📊 Real-Time Summarized Output
        ↓
☁️ Docker + Cloud Deployment
