**1.** How can you leverage pre-trained foundation models? Select two.
- [ ] We typically do not use them at all because they are not useful without any fine-tuning on top
- [x] We can use their outputs as input features to downstream models
- [x] We can update a few top layers, update all layers, or add layers to adapt to the downstream tasks


**2.** Which of the following statements is NOT true about fine-tuning?
- [ ] It can improve downstream task performance
- [x] It does not involve updating model weights
- [ ] Fine-tuning outperforms few-shot learning
- [ ] Full fine-tuning can result in undesirable catastrophic forgetting


**3.** Few shot learning, where it involves prompt engineering, can be called different names. Which of the following describes few-shot learning or prompt engineering? Select all that apply.
- [x] Prompt Design
- [x] Hard prompt tuning
- [x] Discrete prompt tuning
- [x] In-context learning

**4.**  Which of the following is a potential **disadvantage** of full fine-tuning?
- [x] Catastrophic forgetting of other pre-trained tasks
- [ ] Reduced memory usage
- [ ] Reduced compute usage
- [ ] It requires less training data

**5.** Which of the categories does NOT describe how parameter-efficient fine-tuning works?
- [ ] Additive
- [ ] Re-parameterization
- [x] Ablation
- [ ] Selective

**6.** Which of the following is NOT true about soft prompts? 
- [ ] It adds tunable parameters
- [ ] It learns a sequence of task-specific embeddings
- [x] It requires one model for each unique task
- [ ] We only update prompt weights, rather than also updating the foundation model weights
- [ ] It can learn prompt embedding representations automatically

**7.** Which of the following statements is true about the reparametrization technique, LoRA?
- [ ] It adds tunable parameters
- [x] It decomposes a higher-rank weight matrix into low-rank matrices
- [ ] It increases serving latency because of the additional parameters
- [ ] It requires a different copy of model to serve different tasks at deployment

**8.** True or False: Parameter-efficient fine-tuning is superior to full fine-tuning because it always results in stable and better performance.
- [ ] True
- [x] False

**9.** True or False: The more fine-tuning data we can provide to fine-tune a LLM, the better the model performance.
- [ ] True
- [x] False

**10.** Which steps are ideally taken to curate a high quality dataset? Select three.
- [x] Manually verify data quality
- [ ] Scrape through all publicly available websites possible to gain the widest coverage
- [ ] Manually create or rewrite training data examples
- [ ] Remove any data that could be biased or confidential
