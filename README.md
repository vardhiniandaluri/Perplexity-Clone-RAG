# 🔍 Perplexity Clone – AI-Powered Conversational Search Engine

An AI-powered conversational search engine inspired by Perplexity AI, developed using **Google Gemini**, **Retrieval-Augmented Generation (RAG)**, **FAISS Vector Database**, and **Sentence Transformers**. The project retrieves relevant information from a knowledge base before generating responses, enabling more accurate, context-aware, and citation-supported answers.

---

## 📖 Project Overview

Traditional search engines display multiple web links, requiring users to browse several pages to find relevant information. This project transforms the search experience into a conversational AI assistant by combining semantic document retrieval with Google's Gemini Large Language Model.

The application retrieves the most relevant information using vector similarity search and generates reliable responses based on the retrieved context, significantly reducing AI hallucinations.

---

## ✨ Features

- 🤖 AI-powered conversational search
- 🔍 Semantic similarity search
- 📚 Retrieval-Augmented Generation (RAG)
- ⚡ Google Gemini API integration
- 🗂️ FAISS vector database
- 🧠 Sentence Transformer embeddings
- 💬 Conversation history support
- 📄 Citation-based responses
- 🧩 Modular and scalable architecture

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| Google Gemini API | Large Language Model |
| Sentence Transformers | Text Embeddings |
| FAISS | Vector Similarity Search |
| NumPy | Numerical Computation |
| PyPDF | PDF Processing |
| Google Colab | Development Environment |

---

## 🏗️ Project Architecture

```
                User
                  │
                  ▼
         User Query Input
                  │
                  ▼
      Generate Query Embedding
                  │
                  ▼
        FAISS Vector Database
                  │
                  ▼
    Retrieve Relevant Chunks
                  │
                  ▼
      Google Gemini API
                  │
                  ▼
    AI Generated Response
                  │
                  ▼
      Citation + Chat History
```

---

## ⚙️ Workflow

1. User enters a natural language query.
2. The query is converted into vector embeddings.
3. FAISS performs semantic similarity search.
4. The most relevant document chunks are retrieved.
5. Retrieved context is sent to Google Gemini.
6. Gemini generates an accurate response.
7. Sources are displayed along with the answer.
8. Chat history is stored for future conversations.

---

## 📂 Project Structure

```
Perplexity-Clone-RAG
│
├── Perplexity_Clone.ipynb
├── README.md
├── requirements.txt
├── sample_data.txt
└── screenshots
    ├── output1.png
    ├── output2.png
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Perplexity-Clone-RAG.git
```

Install dependencies

```bash
pip install google-generativeai
pip install sentence-transformers
pip install faiss-cpu
pip install pypdf
```

Run the notebook using **Google Colab** or **Jupyter Notebook**.

---

## 📊 Expected Output

The application accepts user questions and provides context-aware AI-generated answers with supporting citations retrieved from the knowledge base.

Example:

**Question**

```
What is Retrieval-Augmented Generation?
```

**Answer**

```
Retrieval-Augmented Generation (RAG) is a technique that combines information retrieval with Large Language Models to generate more accurate and context-aware responses.
```

**Sources**

```
Chunk 1
Chunk 3
```

---

## 📌 Future Enhancements

- 🌐 Real-time web search
- 📄 PDF document question answering
- 🎙️ Voice-based interaction
- 🌍 Multilingual support
- 🎨 Streamlit web interface
- ☁️ Cloud deployment

---

## 👩‍💻 Author

**Vardhini**

B.Tech – Artificial Intelligence & Machine Learning

Passionate about Web Development, Generative AI, and Building Intelligent Applications.

---

## ⭐ Acknowledgements

- Google Gemini API
- FAISS
- Sentence Transformers
- Google Colab
- Blackbucks Internship Program
