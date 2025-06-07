# 🤖 LangChain + Hugging Face Q&A (RAG) System

This project demonstrates a simple, fully local **question-answering system over documents** using [LangChain](https://github.com/langchain-ai/langchain), [Hugging Face Transformers](https://huggingface.co/docs/transformers), and [FAISS](https://github.com/facebookresearch/faiss).

It runs entirely **for free**, without the need for OpenAI or any API keys — ideal for open-source, research, or educational use.

---

## 🧠 Features

- Loads a local document (`sample.txt`)
- Splits it into chunks for efficient retrieval
- Embeds using a Hugging Face sentence transformer
- Stores vectors in a local FAISS vector store
- Answers questions using `flan-t5-base` — no internet required after install

---

## 🚀 Quickstart

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/langchain-hf-rag.git
cd langchain-hf-rag
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
python app.py
```

#### Sample output:
```bash
Q: What can LangChain be used for?
A: You can use it to build chatbots, RAG systems, agents, and more.
```
---

## 🗂️ Project Structure
```bash
langchain-hf-rag/
├── app.py              # Main script to run the pipeline
├── sample.txt          # Example input document
├── requirements.txt    # Required Python libraries
└── README.md           # Project overview and usage
```
## 🤖 Models Used

| Purpose         | Model                                   |
|-----------------|-----------------------------------------|
| Embeddings      | `sentence-transformers/all-MiniLM-L6-v2` |
| Text Generation | `google/flan-t5-base`                    |


## 📚 Use Cases

* Q&A over notes, documentation, or articles

* Lightweight internal document search

* Educational tools (chat over textbook content)

* Open-source LLM experimentation







```markdown
 Note: Install Dependencies before running the app!
```
