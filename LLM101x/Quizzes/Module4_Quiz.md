**1.** What are some of the variations that the release of a new LLM will contain?
- [ ] Models with different sequence lenght inputs
- [ ] Models with different parameter counts
- [ ] Models with different fine-tuned 'flavors'
- [x] All of the above

**2.** As a developer, do you use the largest LLM you can find?
- [ ] Yes, the largest version is always the right choice for development and deployment.
- [x] No, the largest version will never be the right choice as any application will not need such a large model to run properly.
- [ ] Yes, you can always fine tune it later if you need to make a smaller version of it.
- [ ] No, you should take some time to find the best balance between performance and cost, typically the right model for developers will be the smallest model that can produce sufficient performance.

**3.** What are some of the different options available to apply an LLM for a specific application? Select all that apply.
- [x] Few-shot learning of Foundation Models.
- [x] DIY fine-tuning.
- [x] LLM-as-a-Service.
- [x] Zero-shot learning with instruction-tuned models.

**4.** What is the library, DeepSpeed, most efficient for in terms of cluster configuration?
- [ ] Single-node CPU clusters
- [ ] Single-node GPU clusters
- [ ] Multiple-node CPU clusters
- [x] Multiple-node and multiple-GPU clusters

**5.** Is there any reason to use LLMs-as-a-Service?
- [ ] Yes, they will be able to do a better job than you every time.
- [ ] No, you should never have to pay for LLMs!
- [x] Yes, sometimes, depending on your budget and constraints, utilising LLMs-as-a-Service is an excellent way to use minimal effort and leverage high quality LLMs.
- [ ] No, you will always get better results by building an LLM yourself.


**6.** What were two of the contributions of the Dolly v2 model?
- [ ] It created a new foundation LLM that could be cloned easily.
- [x] Databricks' employees contributed a commercial-free use dataset for instruction-following.
- [x] Dolly utilizes smaller and older foundatoin LLMs than ChatGPT but still shows excellent performance.
- [ ] Dolly showed that commercial-use was important to restrict usage to proprietary models.


**7.** True or False: When training an LLM, you only need to focus on the validation losses during training.
- [ ] True. The losses will tell you how well it is adapting to the dataset so you don't need anything else.
- [x] False. There are many ways that the validation loss can be decreasing withouth the task itself actually being learned, this is why we need more sophisticated metrics.


**8.** Why is perplexity important to consider above and beyond accuracy?
- [ ] Perplexity and accuracy are the same thing.
- [x] Perplexity is a measure of how confident the model was with predicting the next token, if a model has low perplexity and high accuracy, that is the best state.
- [ ] Accuracy is more important than Perplexity since we really only need to know if the answer is correct or not.
- [ ] Perplexity is a measure of how confident the model was with predicting the next token, if a model has high perplexity and low accuracy, that is the best state.


**9.** What are two task-specific evaluation metrics?
- [x] ROUGE - for summarisation tasks 
- [ ] ROSE - for question/answering
- [ ] VERDE - for translation and summarization tasks
- [x] BLEU - for translation tasks

**10.** What are the three feature of evaluation by Alignment?
- [x] Helpful
- [x] Honest
- [x] Harmless
- [ ] Happy
