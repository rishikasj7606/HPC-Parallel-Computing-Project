# 🚨 Real-Time Disaster Response Summarization using LLM + HPC

> ⚡ A High-Performance Computing (HPC) powered AI system for real-time disaster data ingestion, processing, and intelligent summarization using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG).

---

## 👥 Team Members

- **Harikrishna S** – CB.AI.U4AID23011  
- **Deepak Kumar** – CB.AI.U4AID23012  
- **Somavaram J Rishika** – CB.AI.U4AID23038  

---

## 🌟 Overview

This project focuses on building a **scalable, real-time disaster intelligence system** that:

- 📡 Collects disaster-related data from multiple APIs in parallel  
- 🧹 Cleans and standardizes incoming data  
- 🗄 Stores structured data efficiently using MongoDB  
- 🤖 Uses LLMs for classification and summarization  
- 🔍 Enhances responses using a **RAG (Retrieval-Augmented Generation) pipeline**  
- ☁️ Deploys seamlessly using containerized cloud infrastructure  

---

## 🎯 Key Highlights

- ⚡ **Low-Latency Data Ingestion** using AsyncIO & parallel APIs  
- 🧠 **AI-Powered Summarization** using fine-tuned LLMs  
- 🔍 **Context-Aware Insights** via RAG architecture  
- 🗃 **Efficient Storage & Retrieval** with MongoDB indexing  
- 🐳 **Cloud-Ready Deployment** using Docker & containerization  
- 🚀 **Scalable HPC Pipeline** for high-throughput processing  

---

## ⚙️ System Architecture

```text
🌐 API Sources
     ↓
⚡ Async Data Ingestion (AsyncIO)
     ↓
🧹 Data Cleaning & Validation (Pydantic)
     ↓
🗄 MongoDB (Indexed Storage)
     ↓
🧠 Model Processing (HPC + Multiprocessing)
     ↓
🔍 RAG Pipeline (Retrieval + LLM)
     ↓
📊 Real-Time Disaster Insights
     ↓
☁️ Dockerized Cloud Deployment
