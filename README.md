# ideal-waffle
# Using OpenAI API for full RAG Implementation
This project is a part of the external Lab assignment of the Coursera Project 'Introduction to Retrieval Augmented Generation (RAG)' where I implemented the RAG pattern on wine quality classification dataset.
Here is a summary of what this repository will use:

1.Qdrant
 for the vector database. We will use an in-memory database for the examples

2.Llamafile
 for the LLM (alternatively you can use an OpenAI API compatible key and endpoint)

3.OpenAI's Python API
 to connect to the LLM after retrieving the vectors response from Qdrant

4.Sentence Transformers to create the embeddings with minimal effort
