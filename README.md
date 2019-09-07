# OpenAI Gym-demo environment

OpenAI Gym environment created following [Gym Docs](https://github.com/openai/gym/blob/master/docs/creating-environments.md). For testing purposes, we use a custom environment named IdentityEnv defined in [this file](https://github.com/hill-a/stable-baselines/blob/master/stable_baselines/common/identity_env.py).

# Installation

To install the Gym environment:

```bash
cd gym-demo
pip install -e .
```

# Test Gym environment on Stable Baselines

[Stable Baselines](https://stable-baselines.readthedocs.io/en/master/index.html) is a set of improved implementations of Reinforcement Learning (RL) algorithms based on [OpenAI Baselines](https://github.com/openai/baselines). Follow the [installation guide](https://stable-baselines.readthedocs.io/en/master/guide/install.html) before running the test code.


```bash
python test.py
```
