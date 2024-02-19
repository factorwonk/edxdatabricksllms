**1.** What two reasons would we want to consider to look beyond the single-LLM call?
- [ ] Single-LLM calls are inaccurate fro most tasks. We need to run many LLM calls so we can get at least one right answer.
- [x] While NLP tasks are handled well by LLMs, most problems contain more tasks than just NLP tasks end-to-end, requiring us to take a step back and look at LLMs as just a piece of the workflow.
- [x] A problem may require multiple NLP tasks connected together, which may require multiple LLMs to complete
- [ ] We always need to have at least two different LLMs producing output so we know which one is true and which is fake.

**2.** Why do we want to create prompt templates?
- [ ] It can be easy to forget what the model needs as input.
- [x] Templating is a useful tool to scale up and abstract out the parts needed to interact with an LLM.
- [ ] LLMs only respond to very specific formats so we need to template every input.
- [ ] Prompt engineering is an important profession and without templates, these engineers will not be able to do their work.

**3.** What is an LLM Chain?
- [ ] A special type of metal that is built and designed using LLMs.
- [ ] The process of linking weaker models together so that the final output is better than a single weak model.
- [ ] Asking an LLM to compute multiple tasks within a single prompt template.
- [x] Combining a prompt to an LLM, and the output of that LLM interation to the input of another LLM.

**4.** What are the two necessary pieces of an LLM Chain?
- [ ] A prompt and a task description.
- [x] A prompt and a candidate LLM.
- [ ] A candidate LLM and a task description.
- [ ] Two LLMs.

**5.** How do you chain LLMs together in LangChain?
- [ ] Utilizing a graph networking library, LangChain combines these LLMs with a complex graphing language
- [x] Chains can be combined as Sequential, or SimpleSequential, chains where outputs and inputs can be defined in a simple and structured way.
- [ ] Langchain, a python library, utilizes python generators to create a low-level structure to combine API calls in a chain.
- [ ] Within the prompt for the first LLM is the API call from LangChain's documentation to access the second LLM.


**6.** Can you combine LLMs with non-LLM tools?
- [x] Yes
- [ ] No

**7.** What are some tools tha can be combined with LLMs? Select all that apply.
- [x] Python Read-Evaluate-Print-Loop
- [x] Mathematical API Libraries
- [x] Internet Search APIs
- [x] Other LLMs


**8.** What are the steps of the ReAct framwork for LLM Agents?
- [ ] Thought-Observation-Action
- [x] Thought-Action-Observation
- [ ] Stop-Drop-Roll
- [ ] Act-React-Readapt


**9.** What are self-directing agents like Auto-GPT?
- [ ] LLMs that are deployed in self-driving cars. 
- [x] LLM Agents that take a guiding prompt and then make their own decisions on how to proceed.
- [ ] LLM Agents that continuously request human feedback for each task.
- [ ] LLMs that can detect when they need to train themselves on new data.

**10.** What can you do if the agent doesn't produce the result you need? Select two.
- [ ] Build a manual process instead since LLM agents are pointless.
- [x] Just re-run the agent, sometimes they need a few tries to get it right.
- [ ] Fine-tune the underlying LLM so that it is as least 2x more accurate than before.
- [x] Refine your prompt to give the LLM agent more guidance and specificity.
