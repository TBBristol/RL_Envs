# Reinforcement Learning Environments for your next Research Project

RL Environments (RLEnvs) are a complex topic, since we can make an environment to model pretty much anything we want (if we are happy to take the trade-offs). More complete lists of possible environments have been made for example [awesome-ai-environments](https://github.com/dbobrenko/awesome-ai-environments) and [awesome-rl-envs](https://github.com/clvrai/awesome-rl-envs). The aim of the below is therefore not to provide an exhaustive list but to provide a quick reference for selecting an environment that may suit your research problem, useful for proof of concepts and experimentation.

#### Selecting an RLEnv

Precisely matching the problem domain is probably possible if we are willing to search for the correct env and customise the code. Mostly however we are interesting in testing that our algorithm functions as we would like especially while developing our work. Some of the criteria we can therefore select on are as follows:

|Criteria|Explanation|
|---|---|
|Problem Space|What is the problem similar to at a very basic level? Games are very different to exploration and puzzle solving. Some environemnts are _directly_ transferrable to the real world (e.g some Drone simulators). Also for consideration is how the environment might help to best illustrate your work by demonstrating a use-case.|
|Discrete/Continuous|Many algorithms are designed to work on a certain type of state space|
|Support|Some RLEnvs have developer or community support meaning problems can be solved very fast|
|Updates|There is huge variability in how recently RLEnvs have been updated leading to potential package conflicts|
|System Resources|RLEnvs are designed to be a toy problem but some have much larger state spaces, action spaces, episode lengths or rendering requirements. Iteration speed, computational requirements (and cost) and goal (sometimes we are aiming to show a method helps to solve complex Envs) need to be considered.|
|API/Interface|Many RLEnvs follow a famliliar format (Gymnasium) for method calls and setting up the problem. This makes it easier to get to grips with both for the developer and anyone reading the code|
|Benchmarks/Previous work|Some RLEnvs are considered benchmark problems meaning it is easy to compare results. Even if There is no comparison to be made future work may want to build on the effort and this is easier if using a non-obscure Env|
|Compatibility with RL libraries|Some Envs state that they are directly compatible with some RL libraries meaning training an agent is as simple as selecting the algorithm and calling the function. Some examples are [Stable Baselines 3](https://stable-baselines3.readthedocs.io/en/master/) or [Clean RL](https://docs.cleanrl.dev/). While most Envs can be made to work with these libraries if they are designed to be compatible this speeds up the process a lot.|
|Documentation/Examples|Some RLEnvs have extensive documentation meaning it is easy to troubleshoot without reading through the Env code. In addition many have example implementations which aid in getting a minimally functioning example up and running very quickly.|
|Custom problems|Some environments have simple APIs to let you customise the problem|
|Wrappers/Utility Functions|Some Envs provide a suite of useful tools for example in changing the observation output or customising the reward to enable you change options without modifying the base code|


The selection of RLEnvs below is somewhat arbitary but should give a broad selection for those wanting to find an Env for a research problem. Likewise the tabular information is simplified and there is more nuance when diving into the Envs themselves especially if customising (pretty much anything can be made to do anyting if you try hard!) but aims to provide a starting point. 

### Farama Foundation <img src="https://github.com/user-attachments/assets/86e3c4cb-7573-4c54-a201-997de52dd0e7" width=50 height=50>

Of note is the [Farama Foundation](https://farama.org/) which took over the maintenence of the Gymnasium project from OpenAI. The Foundation maintains a good number of open-source RL [projects](https://farama.org/projects) and ensures that they are built to certain [standards](https://farama.org/project_standards). Multiple Envs listed below belong to the project and it is certainly a good starting point due to the great documentation and standardised APIs.

|Environment|Image|Description|Discrete/Continuous|Multi-Agent|Customisable|Gymnasium Style API|Utils|Problem Complexity/Resources|Benchmarks|RL Library Compatibility|last Update|Documentation|Support|
|---|---|---|---|---|---|----|---|---|---|---|---|---|---|
|Farama Foundation||||||||||||
|---|---|---|---|---|---|----|---|---|---|---|---|---|---|
|---|---|---|---|---|---|----|---|---|---|---|---|---|---|
|---|---|---|---|---|---|----|---|---|---|---|---|---|---|





