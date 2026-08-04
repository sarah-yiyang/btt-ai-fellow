# Break Through Tech AI Fellowship Projects
A collection of AI assignments completed through the Break Through Tech AI Fellowship, a competitive program focused on applied machine learning, AI engineering, and building real-world AI solutions.



## Capstone
**Airbnb Price Classification**

Developed an end-to-end ML pipeline to classify NYC Airbnb listings as high-priced or low-priced using real-world listing data. Built and evaluated multiple models, including Logistic Regression, Decision Tree, and Neural Networks, while applying feature engineering, preprocessing, hyperparameter tuning, and class imbalance techniques.

The project explored the tradeoffs between model performance and interpretability, demonstrating how machine learning can support data-driven pricing decisions in real-world business applications.

## ai-chatbot

A progression of Streamlit apps built on the OpenAI API, each adding one AI application capability on top of a shared chat interface — from a basic conversational loop to multimodal document extraction.

- **ai-chatbot.py** — Streamlit, OpenAI API, chat completions, session state, message history
- **ai-chatbot-streaming.py** — token streaming, real-time output, `st.write_stream`
- **ai-chatbot-summary.py** — context management, automatic summarization, token tracking, cost optimization, gpt-4o-mini
- **image-interpreter.py** — multimodal (GPT-4o vision), OCR, PDF/image parsing, structured JSON output, invoice/receipt extraction

## rag

Retrieval-Augmented Generation systems that ground model responses in external data, built with LangChain. Covers the full RAG pipeline over unstructured text and extends it to structured relational databases.

- **BuildingRAGSystem.ipynb** — document loading, text splitting, embeddings, ChromaDB vector store, retriever, LangChain chains (LCEL)
- **BuildingImprovingDocumentRAGSystem.ipynb** — baseline RAG chain, query rewriting, retrieval quality, evaluation and comparison
- **BuildNL2SQL.ipynb** — natural language to SQL, SQLAlchemy, structured data, schema-aware querying, pandas



