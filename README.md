# RLlib-Scalable-Reinforcement-Learning
Experiments with RLlib with gym environments
Documentation about getting started [here](https://ray.readthedocs.io/en/latest/rllib-training.html)

#### Experiment 1
env : Asteroids-v0
alg : A3C
config : num_workers: 4 

'''
python3 ray/python/ray/rllib/train.py --run A3C --env Asteroids-v0 --config '{"num_workers":4}'
'''

#### Experiment 2 
env : Asteroids-v0
alg : PPO
config : num_workers: 4 

'''
python3 ray/python/ray/rllib/train.py --run PPO --env Asteroids-v0 --config '{"num_workers":4}'
'''

### For tensorboard visualization , run :

--tensorboard --logdir=/ray_results/default

### Policy Graphs

Learn about policy graphs 
https://ray.readthedocs.io/en/latest/rllib-concepts.html

