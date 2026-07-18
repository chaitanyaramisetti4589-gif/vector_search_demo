# 🔍 Vector Search Demo with ChromaDB

A simple **Vector Search Demo** built with **Python** and **ChromaDB** to demonstrate how vector databases perform semantic search using natural language queries.

Instead of searching for exact keywords, this application retrieves the most relevant document based on the meaning of the user's query.

---

## 🚀 Features

- 📚 Store documents in a ChromaDB collection
- 🧠 Automatically generate embeddings
- 🔍 Perform semantic search
- 💬 Query using natural language
- ⚡ Retrieve the most relevant document
- 🖥️ Simple command-line interface

---

## 🏗️ Workflow

```text
               Documents
                    │
                    ▼
          ChromaDB Collection
                    │
                    ▼
      Automatic Embedding Generation
                    │
                    ▼
           Store Vector Embeddings
                    │
                    ▼
            User Question
                    │
                    ▼
            Semantic Search
                    │
                    ▼
      Most Relevant Document
```

---

## 🛠️ Tech Stack

- Python
- ChromaDB

---

## 📂 Project Structure

```
vector-search-demo/
│
├── main.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/vector-search-demo.git
```

Move into the project directory

```bash
cd vector-search-demo
```

Install dependencies

```bash
pip install chromadb
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 📷 Example Output

```text
==================================================
🔍 Vector Search Demo using ChromaDB
==================================================

Enter your question:
What is Gemini?

📄 Most Relevant Document:
Google Gemini is an AI model developed by Google.
```

---

## 💡 Sample Questions

Try asking:

- What is Python?
- Explain Artificial Intelligence.
- Tell me about Machine Learning.
- What is Gemini?
- What are vector databases?

---

## 🔎 How It Works

1. Create a ChromaDB collection.
2. Store documents in the collection.
3. ChromaDB automatically converts the documents into vector embeddings.
4. The user enters a question.
5. ChromaDB converts the question into an embedding.
6. Semantic search finds the closest matching document.
7. The most relevant document is returned.

---

## 📚 Concepts Demonstrated

- Vector Databases
- Semantic Search
- Embeddings
- Natural Language Querying
- Information Retrieval

---

## 🔮 Future Improvements

- Support multiple document retrieval (Top-K Search)
- Add PDF document support
- Integrate Google Gemini
- Build a Retrieval-Augmented Generation (RAG) system
- Add a web interface
- Store thousands of documents
- Display similarity scores

---

## ⭐ Learning Outcome

This project demonstrates the basics of vector databases and semantic search. It serves as a foundation for building more advanced AI applications such as Retrieval-Augmented Generation (RAG), AI chatbots, document search systems, and knowledge assistants.

---

## 👨‍💻 Author

**Chaitanya Ramisetti**

If you found this project useful, consider giving it a ⭐ on GitHub!
