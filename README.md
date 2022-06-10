## Introduction to Weaviate:

* Weaviate is a vector database and search engine.
* It is a low-latency vector search engine that supports various media types(text, images, etc.). 
* Weaviate uses machine learning to vectorize and store data and find responses to natural language questions.
* It includes semantic search, Question-Answer Extraction, Classification, and Customizable Models (PyTorch/TensorFlow/Keras). 
* Weaviate search can perform through different methods such as GraphQL, REST, and various language clients. 
* Python, Javascript, Go, and Go are popular programming languages that support Weaviate clients.

## Features of Weaviate
* Fast queries – In less than 100 milliseconds, Weaviate runs a 10 closest neighbour (NN) search over millions of items.
* Different media support – Use State-of-the-Art AI model inference (e.g. Transformers) for Images, Text, etc.
* Combining scalar and vector search – Weaviate saves both your objects and your vectors, ensuring that retrieval is always quick. A third-party object storage system is not required.
* Horizontal scalability– Weaviate can scale horizontally in production depending on the use case.
* Graph-like connections – Make graph-like connections between data items to mimic real-life connections between the data points. GraphQL is used to traverse those connections.

## Where can it be used?
At the moment weaviate is used in such cases as:
* semantic search,
* similarity search,
* image search,
* power recommendation engines,
* e-commerce search,
* cybersecurity threat analysis,
* automated data harmonization,
* anomaly detection,
* data classification in ERP systems,
, and many many more cases.

## What is Weaviate Python Client?
The Weaviate Python Client is a python package that allows you to connect and interact with a Weaviate instance. The python client is NOT a Weaviate instance but you can use it to create one on the Weaviate Cloud Service. It provides API for importing data, creating schemas, do classification, query data, ... We are going to go through most of them and explain how and when one could use them.

## What is vector search?

# Weaviate is a vector search engine
Instead of just storing raw data like traditional databases do,Weaviate leverages the power of machine learning(ML) models to vectorize the data.What this means,is that the ML-Models try to understand your data while storing it. This allows Weaviate to search, discover and classify similar results in your dataset. Simply put, Weaviate is a database that understandas your data.
