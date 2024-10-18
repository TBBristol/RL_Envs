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








