# 📄 PDF Question Answering Chatbot using RAG

A Retrieval-Augmented Generation (RAG) based Question Answering chatbot that allows users to upload a PDF document, store its contents in Astra DB as vector embeddings, and ask natural language questions about the document using LangChain and OpenAI.

---

## 🚀 Features

- Upload and process PDF documents
- Extract text from PDF files
- Split documents into manageable text chunks
- Generate embeddings using Hugging Face Embeddings
- Store embeddings in Astra DB Vector Database
- Retrieve relevant document chunks using similarity search
- Generate accurate answers using OpenAI GPT models
- Interactive command-line chatbot

---

## 🛠️ Tech Stack

- Python
- LangChain
- Astra DB
- CassIO
- OpenAI API
- Hugging Face Embeddings
- PyPDF / PyPDFLoader
- Google Colab

---

## 📂 Project Workflow

1. Upload a PDF document.
2. Extract text from the PDF.
3. Split the extracted text into chunks.
4. Generate embeddings for each chunk.
5. Store embeddings in Astra DB.
6. User enters a question.
7. Retrieve the most relevant chunks using vector similarity search.
8. OpenAI generates an answer based on the retrieved context.

---

## 📁 Project Structure

```
├── PDF_QA_Chatbot.ipynb
├── store.pdf
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/pdf-qa-chatbot.git
cd pdf-qa-chatbot
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file and add:

```env
OPENAI_API_KEY=your_openai_api_key
ASTRA_DB_APPLICATION_TOKEN=your_astra_db_token
ASTRA_DB_ID=your_database_id
```

> **Important:** Never commit your API keys or database tokens to GitHub.

---

## ▶️ Usage

1. Upload your PDF.
2. Run the notebook or Python script.
3. Ask questions about the uploaded PDF.
4. Type `quit` to exit the chatbot.

Example:

```
Question:
What is the return policy?

Answer:
The return policy allows customers to return products within 30 days...
```

---

## 📦 Libraries Used

- langchain
- langchain-community
- langchain-astradb
- cassio
- openai
- datasets
- pypdf
- PyPDF2
- sentence-transformers

---

## 📈 Future Improvements

- Web interface using Streamlit
- Support multiple PDF documents
- Conversation memory
- Source citation for answers
- Hybrid search (keyword + semantic)
- Docker deployment

---

## 👩‍💻 Author

**Mansi Pushpakar**

B.Tech CSE Student  
ABES Engineering College

---

## ⭐ If you found this project useful, please consider giving it a star!
