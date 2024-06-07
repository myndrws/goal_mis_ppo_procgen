# Training code for Goal Misgeneralization in Deep Reinforcement Learning, 🌳 adapted for Treechop 🌳

I have [forked this code from this codebase](https://github.com/jbkjr/train-procgen-pytorch/tree/master) (I would like to make clear that I have made very little modification and most of the code here is not my own), used by the [Goal Misgeneralization in Deep Reinforcement Learning](https://arxiv.org/abs/2105.14111) paper. It includes scripts for training RL agents on [modified procgen environments](https://github.com/JacobPfau/procgenAISC), producing figures for the paper, and also for training RL agents on my further forked and [modified procgen environment code available here](https://github.com/myndrws/procgenAISC/tree/master). In turn, this code is based on a fork of [this repository](https://github.com/joonleesky/train-procgen-pytorch) by Hojoon Lee.

## Running the treechop environment 

```
python train.py --exp_name treechopper --env_name treechop --distribution_mode easy --param_name debug --num_timesteps 50000 --num_checkpoints 2 --seed 1080 --gpu_device 0 --device cpu
```

## Requirements

You can view the requirements of the original repositories at the links above, but I have also created a .yml for the set up required for this repo - please see this for further instructions. 

## My references

[Goal Misgeneralization: Why Correct Specifications Aren’t Enough For Correct Goals](https://arxiv.org/abs/2210.01790 and https://sites.google.com/view/goal-misgeneralization)
[Goal Misgeneralization in Deep Reinforcement Learning](https://arxiv.org/abs/2210.01790) and the accompanying codebases, linked above.

## References [from the original repo]

[1] [PPO: Human-level control through deep reinforcement learning ](https://arxiv.org/abs/1707.06347) <br>
[2] [GAE: High-Dimensional Continuous Control Using Generalized Advantage Estimation ](https://arxiv.org/abs/1506.02438) <br>
[3] [IMPALA: Scalable Distributed Deep-RL with Importance Weighted Actor-Learner Architectures](https://arxiv.org/abs/1802.01561) <br>
[4] [Implementation Matters in Deep Policy Gradients: A Case Study on PPO and TRPO](https://arxiv.org/abs/2005.12729) <br>
[5] [Leveraging Procedural Generation to Benchmark Reinforcement Learning](https://arxiv.org/abs/1912.01588)

