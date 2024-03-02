**1.** What are three important goals for MLOps (and LLMOps)?

- [x] Meet KPIs such as model endpoint uptime or model accuracy.
- [x] Reduce the time it takes to get model updates from development to production
- [ ] Automate the entire development-to-production loop to remove humans from this loop.
- [x] Allow updates to models and pipelines

**2.** In an ideal MLOps or LLMOps setup, what is the best description for a Development environment?
- [x] In the Development environment, data scientists or other developers explore data, create new models or pipelines, or update existing models or pipelines.
- [ ] In the Development environment, data scientists or other developers develop new code and models, and the can only access Dev-level data, not Prod-level data.
- [x] In the Development environment, data scientists or other developers create or update models or pipelines, test those models or pipelines on human feedback, and then deploy them directly to Production.

**3.** In an ideal MLOps or LLMOps setup, what is the best description for a Staging environment?
- [ ] In the Staging environment, new or updated models or pipelines undergo rapid unit tests. If the unit tests pass, the updates can be moved immediately to Production to serve end users.
- [x] In the Staging environment, new or updated models or pipelines are tested, using an environment and services which match Production as closely as possible.
- [ ] In the Staging environment, new or updated models or pipelines go through a Continuous Deployment (CD) process that continuously produces newly trained models for deployment to Production.

**4.** In an ideal MLOps or LLMOps setup, what is the best description for a Production environment?
- [ ] In the Production environment, all models or pipelines have already been well-tested and can be used to power user-facing and mission-critical applications.
- [x] In the Production environment, models or pipelines either (a) have been well-tested already or (b) will undergo further testing or gradual rollout, before they replace active models or pipelines powering user-facing and mission-critical applications.
- [ ] In the Production environment, models or pipelines can finally be tested alongside the systems they need to integrate with: data refresh jobs, monitoring, serving etc.

**5.** Recall how the MLflow Tracking server organizes your experimentation and development process.  Which of the following are true statements about how it organizes experiments, runs, metadata, and artifacts?

Select three.

- [ ] The top-level organizational concept is a Run, which contains one or more Experiments.
- [x] Conceptually, an Experiment generally corresponds to a project to create a model or pipeline, whereas a Run corresponds to one execution of that project.
- [x] A Run can store artifacts such as models, pipelines and CSV files.
- [x] A Run can store metadata such as parameters, metrics and links to source code.
- [ ] You must manually log all metadata to a Run.

**6.** Which of the following is a true statement about waht MLflow provides in terms of packaging LLM logic for deployment?
- [ ] MLflow allows you to train and package an LLM without ever knowing what deep learning libraries you are using under the hood.
- [x] Once an LLM API, model or pipeline has been packaged as an MLflow Model, you can deploy that logic almost anywhere: containers, batch jobs, real-time serving, etc.
- [ ] MLflow is for packaging custom fine-tuned models, not for managing pipelines around LLM APIs.

**7.** As you put LLM-powered applications into production, you may need to manage cost/performance tradeoffs.  Which of the following are reasonable tips for optimizing those tradeoffs? Select two.
- [ ] When developing new LLM-powered applications, its always best to start by fine-tuning a model since that will reduce inference costs.
- [x] When scoping out costs, estiamte both development costs such as fine-tuning a model and production costs such as inference computation or API calls.
- [x] Inference costs may be reduced by using smaller models, using shorter queries, and adjusting inference configurations.

**8.** Consider the following scenario.  A Data Scientist writes code for a LangChain chain which calls an LLM API service.  They then serialize the chain as an MLflow Model which is registered to the MLflow Model Registry, transitioned to Staging, tested, transitioned to Production, and put into the end application.  What are plausible reasons for why the chain might not behave in production as expected? Select all that apply.

- [x] The data used for testing in Staging was not representative of the actual user behavior in the end application.
- [x] The end application uses this chain (A) as part of another chain (B), and the testing in Staging used an outdated version of chain B.
- [x] The library versions in Staging and Producrtion did not match.

**9.** Suppose you have an LLM pipeline which uses a vector database to add context to queries.  Which of the following statements is true?
- [x] The embedding used for the vector database query must exactly match the embedding used in the first place to populate the vector database.
- [ ] The embedding used by the LLM pipeline must exactly match the embedding used by the vector database.
- [ ] When you update the embedding used for the vector database, you must also update the embedding used by the LLM pipeline.
- [ ] When you update the embedding used for the LLM pipeline, you must also update the embedding used for the vector database.


**10.** Suppose you have a user-facing LLM-powered application, and your users are complaining about slow response times.  We’ve listed potential updates below which could speed up response times.  Which of these updates might cause the LLM behavior to change?  That is, if a user sends the same query to the old application and the updated one, which updates could cause changes to the LLM response the user sees? 

Select three.
- [x] You shorten queries to the LLM by making your prompt more succint.
- [x] You change inference configurations to do a simple greedy search instead of beam search
- [x] In the vector database used to add context to your LLM prompt, you reset and repopulate the database using a faster embedding.
- [ ] You increase the compute resources available overall by scaling out, but you keep the compute resources used for each query the same.