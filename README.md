# 🤖 LOCAL GPT – Offline GenAI

Welcome to **LOCAL GPT**, a suite of **offline Generative AI hands-on projects** built using LangChain, Ollama, FAISS, and LLaMA 3.2.  
Each project demonstrates a key concept in building secure, local, and production-ready LLM applications — **without internet dependency**.

This main repository acts as a portfolio index of **4 standalone projects**, each implemented and hosted in a separate GitHub repository.

---

## 📁 Project List

### ✅ [Project 1 – Hands-On Setup: Local LLM Playground](https://github.com/lakshmiprasadlp/hands-on-ollama-.git)

> A foundation setup for running and interacting with LLaMA 3.2 locally using **Ollama** and **LangChain**.

**Highlights:**
- Run LLMs like `llama3`, `mistral`, and `deepseek` locally
- Set up LangChain pipeline and LangSmith (optional)
- Zero cloud cost / Fully offline

---

### ✅ [Project 2 – Offline Chatbot with LangChain, Ollama, and LLaMA 3.2](https://github.com/lakshmiprasadlp/Offline-Chatbot-with-Langchain-Ollama-LLAMA-3.2-.git)

> Build a privacy-focused chatbot with no internet required using local LLMs.

**Advantages:**
- 💾 Fully offline and private
- 🔐 No data leakage
- 🔁 Multi-turn chat powered by local inference
- 💻 Works on your own hardware

**Limitations:**
- 🧠 High RAM/CPU/GPU required
- 🕓 Initial model load time can be long on CPU

---

### ✅ [Project 3 – Chatbot with Memory using `ConversationSummaryBufferMemory`](https://github.com/lakshmiprasadlp/Conversational-Chat-Bot-Application-with-Langchain-Ollama.git)

> Improve chat consistency and context retention using memory in LangChain.

**Features:**
- Summary-based conversation memory
- Compresses history to reduce token cost
- Makes multi-turn chat intelligent and contextual
- Works with offline/local models (Ollama)

---

### ✅ [Project 4 – Retrieval-Augmented Generation (RAG) with FAISS + PDF](https://github.com/lakshmiprasadlp/localRag.git)

> Ask deep questions over PDF documents using a full RAG pipeline.

**Pipeline:**
- 📄 Convert PDFs → Markdown → Chunks
- 🔍 Embed using Ollama or OpenAI
- 📦 Store vectors in FAISS
- 💬 Retrieve top K chunks → Answer using LLM (local or cloud)

**Use Case:**  
> Ask questions like “What is Google’s Q3 net income?” over earnings reports and get factual, context-aware answers.

---

## 📦 Tech Stack Used Across Projects

| Category      | Tool/Library                   |
|---------------|--------------------------------|
| LLM           | Ollama (`llama3`, `deepseek`)  |
| Framework     | LangChain                      |
| Memory        | `ConversationSummaryBufferMemory` |
| Vector Store  | FAISS                          |
| Embeddings    | Ollama / OpenAI                |
| File Parser   | Docling                        |
| Prompting     | LangChain `ChatPromptTemplate` |
| Optional UI   | Streamlit / Gradio             |

---

## 🎯 Objective

These projects aim to:
- Enable **offline GenAI** use-cases with full control and zero data risk.
- Demonstrate **LangChain concepts** hands-on: memory, RAG, embeddings, chains.
- Create a **portfolio-level suite** of GenAI use cases.

---

## 🧠 Next Steps / Future Work

- ✅ Add LangGraph for agentic workflows
- ✅ Streamlit UI for chatbot and RAG
- 🔄 Integrate with long-term vector DB like Chroma
- 🌐 Serve locally via FastAPI/Gradio interface

---

## 🙋‍♂️ Author

**Lakshmiprasad**  
Machine Learning & Generative AI Engineer  
🔗 [LinkedIn](https://www.linkedin.com/in/charanlp/) | 🌐 [GitHub](https://github.com/lakshmiprasadlp)

---

## 📄 License

This suite of hands-on GenAI projects is licensed under the **MIT License**.

---

> _“Your LLMs. Your Machine. Your Data.”_ 💻🔒
