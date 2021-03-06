# Implementation of PacMan-Lite

Code for FYP SCSE20-0482:
‘The Six Pac-men’: Exploring the strength of advice provision and the impact of an adversarial advisor in reinforcement learning

## Requirements

- Python 3.6.1 (Minimum)
- [OpenAI baselines](https://github.com/openai/baselines), commit hash: 98257ef8c9bd23a24a330731ae54ed086d9ce4a7
- [OpenAI Gym](https://github.com/openai/gym), version: 0.9.4
- [Multi-agent Particle Environments](https://github.com/shariqiqbal2810/multiagent-particle-envs)
- [PyTorch](http://pytorch.org/), version: 0.3.0.post4
- [Tensorboard](https://github.com/tensorflow/tensorboard), version: 0.4.0rc3
- [Tensorboard-Pytorch](https://github.com/lanpa/tensorboard-pytorch), version: 1.0 (for logging)

## Intructions to run the code

- To run training, use the command:
  py main.py PacmanLite_Experiment1 "..\\Output" --n_rollout_threads=1 --episode_length=25 --n_episodes=50
  py main.py PacmanLite_Experiment2 "..\\Output" --n_rollout_threads=1 --episode_length=25 --n_episodes=50

- To run training, use the command:
  py main_test.py PacmanLite_Experiment1 "..\\Output" --n_rollout_threads=1 --episode_length=25 --n_episodes=50
  py main_test.py PacmanLite_Experiment2 "..\\Output" --n_rollout_threads=1 --episode_length=25 --n_episodes=50

- Settings for Experiment 1 are contained within `PacmanLite_Experiment1.py`
  Settings for Experiment 2 are contained within `PacmanLite_Experiment2.py`

- All training code is contained within `main.py`
  All test code contained within `main_test.py`
