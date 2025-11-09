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

#########################################################################################################################################

This project uses the [ESPN Soccer Data](https://www.kaggle.com/datasets/excel4soccer/espn-soccer-data) dataset from Kaggle for analysis and visualization.

## Dataset Information
The dataset is licensed under the **MIT License**, originally created and maintained by **Mark Otto** and **Andrew Fong**.

- Dataset Source: [Kaggle - ESPN Soccer Data](https://www.kaggle.com/datasets/excel4soccer/espn-soccer-data)
- License: [MIT License](data/LICENSE)
- Copyright © 2013 Mark Otto, 2017 Andrew Fong

I do not claim ownership of this dataset. It is included here under the terms of the MIT License.

