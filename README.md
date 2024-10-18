# Reinforcement Learning Environments for your next Research Project

RL Environments (RLEnvs) are a complex topic, since we can make an environment to model pretty much anything we want (if we are happy to take the trade-offs). More complete lists of possible environments have been made for example [awesome-ai-environments](https://github.com/dbobrenko/awesome-ai-environments) and [awesome-rl-envs](https://github.com/clvrai/awesome-rl-envs). The aim of the below is therefore not to provide an exhaustive list but to provide a quick reference for selecting an environment that may suit your research problem, useful for proof of concepts and experimentation.

#### Selecting an RLEnv

Precisely matching the problem domain is probably possible if we are willing to search for the correct env and customise the code. Mostly however we are interesting in testing that our algorithm functions as we would like especially while developing our work. Some of the criteria we can therefore select on are as follows:

|Criteria|Explanation|
|---|---|
|Problem Space|What is the problem similar to at a very basic level? Games are very different to exploration and puzzle solving. If the purpose is explainability there must be something to explain. Also for consideration is how the environment might help to best illustrate your work by demonstrating a use-case.|
|Discrete/Continuous|Many algorithms are designed to work on a certain type of state space|
|Support|Some RLEnvs have developer or community support meaning problems can be solved very fast|
|Updates|There is huge variability in how recently RLEnvs have been updated leading to potential package conflicts|
|System Resources|RLEnvs are designed to be a toy problem but some have much larger state spaces, action spaces, episode lengths or rendering requirements. Iteration speed, computational requirements (and cost) and goal (sometimes we are aiming to show a method helps to solve complex Envs) need to be considered.|







