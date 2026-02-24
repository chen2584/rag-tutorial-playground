## Installation
pip install langchain langchain-community langchain_text_splitters langchain_openai langchain_chroma python_dotenv
pip install langchain-google-genai
pip install rank_bm25

## Test Retreival quality
Prompt
```
I'm testing my RAG system, i will give you the following information:

User Query:

Context:

I wan to to tell me if the context is good and has the answer to the user's question in 1-2 lines

If you understand this, just say "Okay"
```

and give the answer by output from retrieval_pipeline.py