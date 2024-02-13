**1.** Why do we use dense, rather than sparse, embedding vectors for semantic search? Select two.
- [x] Dense embedding vectors can encode the context of the words
- [x] Dense embedding vectors capture semantic relationships better
- [ ] Dense embedding vectors are quicker to computeß
- [ ] Dense embedding vectors take up less storage space


**2.**  Which of the following is NOT true about passing text as context to language models?
- [x] It is the only way for languae models to learn knowledge from your text
- [ ] Passing context helps improve factual recall
- [ ] If the context passed is irrelevant to the user query, it is not helpful to improve language model performance
- [ ] Long context increases search-retrieval time

**3.** Which one of the following is NOT an approximate nearest neighbor search algorithm?
- [ ] Facebook AI Similarity Search (FAISS)
- [ ] Hierarchical Navigable Small Worlds (HNSW)
- [x] K-nearest neighbors (KNN)
- [ ] Locality-Sensitive Hashing (LSH)

**4.** Which of the following are used as a vector distance similarity measure? Select two.
- [ ] L1 reguralization
- [ ] L2 reguralization
- [x] L2 Euclidean
- [x] Cosine similarity

**5.** Which is the correct sequential workflow of retrieval-augmented generation?
- [x] User submits query -> Language model converts query to embeddings -> Search for relevant documents -> Pass context to language model -> Language model outputs responses
- [ ] Search for relevant documents -> User submits query -> Language model converts query to embeddings -> Pass context to language model -> Language model outputs responses
- [ ] Search for relevant documents -> Pass context to language model -> User submits query -> Language model converts query to embeddings -> Language model outputs responses
- [ ] User submits query -> Search for relevant documents -> Language model converts query to embeddings -> Pass context to language model -> Language model outputs responses

**6.** Which of the following is true about Facebook AI Similarity Search (FAISS) algorithm?
- [ ] It implements cosine distance and forms clusters of sparse vectors
- [ ] It implements L2 distance and forms clusters of sparse vectors
- [ ] It implements cosine distance and forms clusters of dense vectors
- [ ] It implements L2 distance and forms clusters of dense vectors

**7.** When might you choose to store vectors in a vector database, as opposed to using only a vector library? Select three.
- [x] You want to persist the embedding vectors in long-term storage
- [x] You want to have Create-Read-Update-Delete (CRUD) support to edit or update the vectors, without recomputing the entire vector index
- [ ] You have a relatively less stringent latency requirement
- [x] You have a large volumne of frequently changing data

**8.** True or False: You need to have a vector store for all your text use cases.
- [ ] True
- [x] False

**9.** You have implemented a search and retrieval workflow for your chatbot. However, the chatbot never seems to generate relevant responses. Which of the following is NOT a possible reason?
- [ ] There is none or sufficient relevant documents as context to answer those specific user queries
- [ ] The users need to experiment more with prompts
- [ ] The embedding model you choose to encode the queries and the documents is trained on another type of data
- [x] The developers should have used a vector database, rather than a vector library

**10.** True or False: You always need to split documents into chunks before storing them as vector indices in a vector library or database
- [ ] True
- [x] False
