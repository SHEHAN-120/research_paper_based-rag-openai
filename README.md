# RAG-Based Q\&A on RNN and LSTM Fundamentals (arXiv Paper)

This project demonstrates a **Retrieval-Augmented Generation (RAG)** system using the research paper:

> [Fundamentals of Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) Network – arXiv:1808.03314](https://arxiv.org/abs/1808.03314)

The goal is to enable intelligent Q\&A over the paper content using semantic search and language generation. The system retrieves relevant chunks from the paper and generates context-aware answers using OpenAI's GPT model.

---

## 📊 Project Objective

* Extract and index content from the arXiv research PDF
* Embed the document using FAISS for vector similarity search
* Use OpenAI API to generate answers from retrieved passages

---

## 🚀 Technologies Used

* Python
* LangChain
* FAISS (Facebook AI Similarity Search)
* OpenAI  API
* `PyMuPDF` for text extraction

---

## 💡 Skills Gained

| Skill                           | Description                                       |
| ------------------------------- | ------------------------------------------------- |
| **LangChain Workflow**          | Built modular RAG pipeline with retriever and LLM |
| **Document Chunking**           | Split text into semantically meaningful blocks    |
| **Vector Embedding with FAISS** | Created a searchable index of the paper's content |
| **Prompt Engineering**          | Designed prompts for context-based answers        |
| **OpenAI API Usage**            | Integrated custom GPT model with personal API key |
           




---

## 📖 How It Works

1. **PDF Loading**: Paper is loaded and parsed into clean text
2. **Text Splitting**: Paragraphs are chunked with LangChain’s `RecursiveCharacterTextSplitter`
3. **Embedding**: Chunks are vectorized using OpenAI embeddings and stored in a FAISS index
4. **Query**: User submits a question
5. **Retrieval + Generation**: LangChain retrieves top-matching chunks and passes them to OpenAI for answer generation

---

## 🔐 OpenAI Key

> ⚠️ This project uses my **personal OpenAI API key** 

---

## 🔗 Paper Link

[https://arxiv.org/abs/1808.03314](https://arxiv.org/abs/1808.03314)

---



Happy RAG building 🧠
