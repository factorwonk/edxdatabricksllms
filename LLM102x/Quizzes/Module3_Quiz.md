**1.** What is a common trade off between large and small scale LLMs?
- [ ] Smaller models are slower than larger models
- [ ] Larger models don't perform as well as smaller models
- [x] Smaller models are faster, but larger models are usually more accurate
- [ ] Larger models are faster, but smaller models are usually more accurate


**2.** How does ALiBi help?
- [ ] It allows you to perform context calculations faster
- [x] It uses a weighting in the attention calculation to improve testing/infereincing on longer contexts
- [ ] It uses a weighting in the attention calculation to improve testing/infereincing on shorter contexts
- [ ] It reduces the memory footprint of attention calculations


**3.** How does FlashAttention help?
- [ ] It only lets the attention mechanism look at the data very briefly
- [x] It never constructs a full attention matrix for the calculations
- [ ] It uses the CPU cache to perform calculations
- [ ] FlashAttention does not help

**4.**  Which type of attention provides the best overall accuracy & speed?
- [ ] Single-headed Attention
- [ ] Multi-query Attention
- [x] Grouped Query Attention
- [ ] Multi-headed Attention

**5.** What was the reason behind the bf16 number?
- [ ] bf16 was an approach to use base-fifteen 16 bit numbers
- [x] bf16 has the same size as fp16, but the same range as fp32
- [ ] The bf16 number was needed for the new Google hardware
- [ ] The bf16 is the same as fp16

**6.** What dies quantization do? 
- [ ] It converts a floating point number into a fraction
- [ ] It creates a Quantum mechanical version of the LLM
- [x] It converts a floating point number into an integer
- [ ] It converts an integer into a floating point number

**7.** What are the differences between LoRA and QLoRA? Select two.
- [x] The transformer in QLoRA is also quantized
- [ ] The transformer is converted into a decoder
- [x] The optimizer is paged to CPU memory
- [ ] QLoRA is the quadratic version of LoRA

**8.** What is a MoE (Mixture of Experts)?
- [ ] Using data from multiple experts to generate data to train a model
- [ ] Combining a mixture of model outputs using different input and averaging the output
- [x] A new architecture that leverages multiple expert models inside one ensemble that is trained simultaneously but a gating mechanism is used to send inputs to different expert models internally
- [ ] A new architecture that mixes different models internally to process input, including deep learning and other machine learning models

**9.** What is an LLM Cascade?
- [ ] The point at which LLMs can create smarter versions of themselves
- [ ] LLM Cascades are the paths taken during backpropagation that use the residual connections
- [ ] LLM Cascade is an alternative to the Transformer architecture
- [x] Using intially lower performing LLMs and slowly accessing more sophisticated ones if needed

**10.** If you had a 40GB VRAM GPU, which model would you load for inference on it? Select two.
- [x] Llama2-7b
- [ ] MPT-30b
- [x] GPT-2
- [ ] Llama2-70b
