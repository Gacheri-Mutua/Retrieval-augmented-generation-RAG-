# Retrieval-augmented-generation-RAG- 
A Retrieval-Augmented Generation (RAG) project that enables users to query the **Constitution of Kenya (2010)** interactively.  
This tool uses embeddings + a vector database to retrieve relevant sections of the Constitution and generate contextual answers through a language model.  

Features
- Upload and preprocess the Constitution of Kenya (2010).
- Chunk text and build vector embeddings for semantic search.
- Query the document via a simple **Gradio UI**.
- Returns answers grounded in the original Constitution text.
- Prompting: tailor generation prompts to your use case and to avoid hallucination (include retrieved context, citations).
- 
Tech Stack
- [LangChain](https://www.langchain.com/) – retrieval + pipeline
- [FAISS / Chroma](https://python.langchain.com/docs/integrations/vectorstores) – vector database
- [Gradio](https://gradio.app/) – user interface
- [OpenAI / Groq API](https://platform.openai.com/) – LLM for generation

