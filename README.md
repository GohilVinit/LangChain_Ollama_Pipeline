# 🔥 LangChain + Ollama Policy Processing Pipeline  

## 📌 Overview  
This project is an AI-powered **policy document processing pipeline** using **LangChain** and **Ollama**. It extracts **keywords** and **policy-related questions** from documents (PDF, Word, TXT) and saves the results in an **Excel file**. It also supports **retrieval-based search** using **ChromaDB**.  

---

## ✨ Features
✅ Extracts **keywords** from policy documents  
✅ Generates **policy-related questions** using **Ollama**  
✅ Supports **PDF, Word (.docx), and TXT** files  
✅ Saves results to **Excel (`policy_results.xlsx`)**  
✅ **ChromaDB integration** for document retrieval  
✅ Fully automated **pipeline with virtual environment**  

---

## 📂 Project Structure
```bash
📁 LangChain_Ollama_Pipeline
│── 📁 documents/            # Folder for input policy documents
│── 📄 convert.py            # Converts PDFs, Word, and Text to plain text
│── 📄 keyword.py            # Extracts keywords using Ollama
│── 📄 question.py           # Generates policy questions using Ollama
│── 📄 pipeline.py           # Main script to run the pipeline
│── 📄 vectorstore.py        # Stores documents in ChromaDB (optional)
│── 📄 requirements.txt      # List of dependencies
│── 📄 README.md             # Project documentation
│── 📄 policy_results.xlsx   # Output Excel file
