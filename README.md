# ideal-waffle
# Using OpenAI API for full RAG Implementation
Here is a summary of what this repository will use:

1.Qdrant
 for the vector database. We will use an in-memory database for the examples

2.Llamafile
 for the LLM (alternatively you can use an OpenAI API compatible key and endpoint)

3.OpenAI's Python API
 to connect to the LLM after retrieving the vectors response from Qdrant

4.Sentence Transformers to create the embeddings with minimal effort
