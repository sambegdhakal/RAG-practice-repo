\# Soccer Stats RAG Assistant



This project demonstrates a \*\*Retrieval-Augmented Generation (RAG)\*\* pipeline for analyzing soccer statistics.  

It combines semantic search with a \*\*Groq-hosted LLaMA 3.1 LLM\*\* to generate insightful answers grounded in real data.



---



\## 🛠 Features



\- \*\*R — Retrieval:\*\* Uses \*\*Qdrant\*\* for semantic vector search on soccer stats data.  

\- \*\*A — Augmentation:\*\* Injects retrieved results into the LLM prompt to ensure factual responses.  

\- \*\*G — Generation:\*\* Uses \*\*Groq LLaMA 3.1 8B\*\* model to generate summaries and insights.  

\- \*\*Generative AI:\*\* Produces new, coherent natural-language answers based on the retrieved context.



---



\## ⚡ Requirements



Make sure you have Python 3.9+ installed.



```bash

\# Groq API client

pip install groq



\# Sentence Transformers for embeddings

pip install sentence-transformers



\# Ensure typing\_extensions is up-to-date

pip install --upgrade typing\_extensions



\# If issues occur with typing\_extensions

python -m pip install --force-reinstall --upgrade typing\_extensions



