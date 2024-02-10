**1.** Suppose you have a data pipeline for marketing events.  The input data has columns with event titles and descriptions as free text, but events are not categorized or labeled.  You want to augment the event data with a new “category” column grouping events into 3 categories: “biz_leadership,” “data_science,” and “engineering.”  When searching for existing models on the Hugging Face Hub, what types of NLP tasks would you filter by to find potential models? Select two
- [ ] Summarization
- [ ] Text Classification
- [x] Text Generation
- [x] Zero-Shot Classification
- [ ] Conversation


**2.** Suppose you need a model for translating between two languages.  When searching for a model, what common NLP tasks might be relevant? Select two.
- [ ] Summarization
- [x] Translation
- [ ] Text Classification
- [x] Text Generation
- [ ] Zero-Shot Classification

**3.** Suppose you need a model for Sentiment Analysis.  When searching for a model, what common NLP tasks might be relevant? Select four.
- [ ] Translation
- [x] Text Generation
- [x] Zero-Shot Classification
- [x] Text Classification
- [x] Few-Shot Learning

**4.** When might you use few-shot learning? Select two.
- [ ] You have a big set of labeled data which you can use for fine-tuning a model in just a few attempts.
- [x] You do not have much labeled data for your task, but you can write out a few examples.
- [x] You have a novel task which you can explain in clear natural language instructions.

**5.** Look at the following statements about inference methods for text generation with LLMs.  Which of the statements are correct? Select two.
- [x] Compared to greedy search, beam search trades more computation for potentially better results.
- [ ] Greedy search usually returns a better result than sampling since greedy search picks the most likely next token.
- [x] When top-K sampling is done with K=1, then sampling is equivalent to greedy search.
- [ ] When top-p sampling is done with p=1, then sampling is equivalent to greedy search.

**6.** What are good reasons to pick a small variant of a model? Select two.
- [ ] It is never worthwhile to use a large model for production because of how much inference costs.
- [x] When you are getting started or prototyping, a small model can be faster and cheaper for development.
- [x] A small, fine-tuned model may performm just as well as a larger, more general model, and it will be faster and cheaper for inference.

**7.** When considering a pre-trained LLM for a new application, what are good reasons to find code examples of using that LLM? Select all that apply.
- [x] Not all models are well-documented, so an example of using the model in a pipeline can provide useful tips about how to call it.
- [x] If you cannot find any examples of using a model, the model may be too obscure and untested to be reliable.
- [x] Not all models are applicable for all NLP tasks. If you find an example of usaage for your NLP task, then you can be more certain that the model is applicable.

**8.** Which is a true statement about prompts?
- [ ] Every LLM requires carefully phrased prompts in order to produce a good answer.
- [x] Prompts can include human language, programming languages, emojis and other arbitrary text.
- [ ] A well-engineered prompt which produces good results for one LLM can be reused successfully with almost any other LLM.

**9.** Of the following prompt engineering techniques, what is the most applicable technique for reducing prompt hacking?
- [ ] Ask the model to admit when it does not know how to answer.
- [x] When you include user input in a prompt, enclose the input with random strings or tags
- [ ] Ask the model to return structured output such as HTML or JSON
- [ ] Include very specific instructions in your prompt, in addition to the user input

**10.** What are reasonable techniques for ensuring your model does not return offensive words? Select two.
- [x] In your instructions to the LLM, include one telling it to remove all offensive words from the output.
- [ ] Ask the model to think step-by-step to come to a solution.
- [ ] Train a new model on a dataset which does not contain any offensive words.
- [x] Use a second model to clean the main LLM's output, removing any offensive words.
