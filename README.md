# GovPDF – GenAI Reader for Government Circulars 📄🤖

**GovPDF** is a GenAI-powered system designed to read, summarize, and answer questions on Indian government financial circulars and policy documents.

---

## 🧠 Features

- ✅ Ingests and semantically indexes PDF documents
- ✅ RAG pipeline using **LangChain + FAISS**
- ✅ Summarization and Q&A using **LLaMA2 fine-tuned with LoRA**
- ✅ Deployed using **Flask, Docker, AWS EC2**, and **Kubernetes**
- ✅ Enables real-time user queries and summarization

---

## 🔧 Tech Stack

| Category         | Tools Used                        |
|------------------|------------------------------------|
| LLM              | LLaMA2 + LoRA                      |
| Vector Search    | FAISS                              |
| Orchestration    | LangChain                          |
| Backend          | Flask                              |
| Deployment       | Docker, AWS EC2, Kubernetes        |
| File Handling    | PyMuPDF / pdfminer                 |

---

## 🗂️ Planned Folder Structure
GovPDF-GenAI-Reader/
├── app.py
├── pdf_ingestor.py
├── rag_pipeline.py
├── llama2_loader.py
├── Dockerfile
├── requirements.txt
└── README.md
---

## 📸 Coming Soon

- 📌 Sample PDF inputs + chatbot response screenshots  
- 🧠 Notebook for testing inference and summaries  
- 🔗 Optional demo link (if deployed)

---

## 👩‍💻 Author

**Rashmitha Vaddadi**  
[GitHub](https://github.com/rashmitha-vaddadi) | [LinkedIn](https://linkedin.com/in/rashmitha-vaddadi)

---

## 📝 Status

> Core components built and tested. This README documents the architecture and tech stack. Code & deployment notes will be added shortly.
