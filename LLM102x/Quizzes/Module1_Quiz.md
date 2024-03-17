**1.** n the history of AI development, computer vision was unlocked with the Convolutional Neural Networks, however this required a special feature, the convolution layer.  What was the key feature that allowed a similar breakthrough for large language models (LLMs)?
- [ ] We are still waiting to see if something like the convolution layer for vision can be developed for LLMs
- [ ] LLMs also use the convolution layer, so that one layer is important for both vision and language
- [x] For LLMs, the attention mechanism unlocked the ability to tackle language better than ever before
- [ ] LLMs require both the convolution layer and the attention mechanism to solve the problem of language in AI


**2.** What are the main components of the Transformer block?
- [x] Position-wise feed forward neural network
- [x] Attention mechanism
- [ ] Softmax layer
- [ ] Positional embedding
- [x] Residual connection and normalization


**3.** What happens to the natural language input to a transformer?
- [x] The input is tokenized and made into embeddings which are added to positionl encoding for each token
- [ ] A softmax layer is used to select the next token
- [ ] The words are averaged and set to the transformer block
- [ ] The input is first sent to attention and position-wise feedforward networks to create the word embeddings

**4.**  What are the three types of transformer architectures? Select 3.
- [x] Decoder
- [x] Encoder
- [ ] Decoder-Encoder
- [x] Encoder-Decoder

**5.** What kind of transformer was in the original paper ‘Attention is all you need’?
- [ ] Encoder
- [ ] Decoder
- [x] Encoder-Decoder
- [ ] Encoder-Encoder

**6.** What were the new innovations introduced by the BERT model? Select 3. 
- [x] Segment embeddings with [CLS] and [SEP] tokens
- [x] Masked Language Modeling
- [x] Next Sentence Prediction
- [ ] Self-attention

**7.** What are some of the important variables in transformers? Select 3.
- [ ] Number of CUDA cores
- [x] Context length
- [x] Number of transformer layers
- [x] Embedding/model size

**8.** What are the vectors built in the attention mechanism. Select 3.
- [x] Query
- [x] Key
- [x] Value
- [ ] Perplexity

**9.** What is the difference between a foundation model and a base model?
- [ ] Foundation models are only built for text
- [ ] Base models are part of a foundation model
- [x] They are the same thing
- [ ] Base models are only built for text

**10.** What allowed for GPT-2 and GPT-3 to have so much more data to train on?
- [ ] OpenAI found a new trove of books to digitize
- [x] A crawl of public websites allowed for a much larger data source
- [ ] They did not have extra data
- [ ] Google sent OpenAI the data they were using
