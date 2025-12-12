# AI-Assistant-A-RAG-Based-Chatbot-using-LLM
Design and Implementation of a Library AI Assistant: A RAG-Based Chatbot Leveraging Large Language Models (LLMs).

**Retrieval-Augmented Generation (RAG) AI Agent with Chat UI Integration**

* Built a full-stack RAG AI Agent that answers user queries from documents (PDF, Excel, Markdown, TXT).
* Backend designed using Langflow and n8n to orchestrate the RAG flow: file ingestion → text splitting → OpenAI embeddings → vector store → retriever → LLM.
* Used Supabase (Postgres + pgvector) for vector storage and retrieval.
* Powered by OpenAI/Gemini LLMs and deployed locally with Docker.
