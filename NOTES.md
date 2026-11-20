# 🦜🔗 LangChain Learning Notes

> Plain-text version of my notes. Open **`notes.html`** in a browser for the styled version.

---

## 📌 What is LangChain?

LangChain is an open-source framework for building apps powered by LLMs (GPT, Claude, etc.).
It connects the LLM with **your data, tools, and memory**, and lets you chain steps together.

> 🧠 **LLM = the brain, LangChain = the body, hands, and memory around it.**

---

## ✅ Benefits of LangChain

- 🔄 **Model-agnostic:** swap OpenAI, Anthropic, etc. with minimal code change
- 🧩 **Modular:** prompts, models, parsers, tools are reusable pieces
- 🔗 **Chaining:** combine steps easily (prompt -> model -> parser)
- 📚 **RAG support:** connect LLMs to your own documents
- 🛠️ **Agents and tools:** let the LLM call APIs/functions
- 💾 **Memory:** keep conversation context
- 🔌 **Many integrations:** vector DBs, loaders, APIs
- 👥 **Big community:** lots of docs and examples

---

## 🧱 Components of LangChain

### 1. 🤖 Models
The LLMs and embedding models you call.
- **Language model:** takes text in, gives text out (chat, Q&A, summaries)
- **Embedding model:** turns text into numbers (vectors) so meaning can be searched

### 2. 📝 Prompts
Reusable templates for the input sent to the model, with variables filled in at runtime.

### 3. ⛓️ Chains
Steps linked together, where the output of one becomes the input of the next.
Example: prompt -> model -> output parser.

### 4. 📂 Indexes
Everything needed to work with your own data:
- **Document loader:** loads data from PDFs, web pages, files, databases
- **Text splitter:** breaks big documents into small chunks
- **Vector store:** stores the chunk embeddings (FAISS, Chroma, Pinecone)
- **Retriever:** fetches the most relevant chunks for a question

### 5. 💾 Memory
Stores earlier messages so the model remembers the conversation.

### 6. 🕵️ Agents
The LLM decides which **tools** to use (search, calculator, APIs) and in what order to reach a goal.

---

## ⚔️ LangChain vs LlamaIndex vs Haystack

| | LangChain | LlamaIndex | Haystack |
|---|---|---|---|
| Main focus | General LLM apps, chains, agents | Data indexing and retrieval (RAG) | Search and RAG pipelines |
| Best for | Complex workflows, agents, tool use | Q&A over your documents | Production search/QA systems |
| Strength | Flexibility, huge ecosystem | Easy, strong data connectors | Clean pipelines, production-ready |
| Weakness | Can feel complex/abstract | Less suited for agent-heavy apps | Smaller community |

**Quick rule:**
- Need agents and flexible workflows -> LangChain
- Need to chat with your data -> LlamaIndex
- Need production search pipelines -> Haystack

---

## ✍️ My Notes

### Day 1
- 

### Day 2
- 

## ❓ Questions / Things to revisit
- 

## 🔗 Useful links
- Docs: https://python.langchain.com
