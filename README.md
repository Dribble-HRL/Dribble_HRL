# Dribble-HRL ⚽

> [!IMPORTANT]  
> TODO

This repository contains an official implementation of the paper:

**Dynamic Legged Ball Manipulation on Rugged Terrains with Hierarchical Reinforcement Learning**

Dongjie Zhu, Zhuo Yang, Tianhang Wu, Luzhou Ge, Xuesong Li, Qi Liu*, Xiang Li*

[[Website](https://xander-2077.github.io/Dribble_HRL/)], [Paper (Comming soon)], [[Video](https://youtu.be/7Hf6mCO0mZU)]

## Installation

### Create a new conda environment
   
```bash
conda create -n Dribble-HRL python=3.8
conda activate Dribble-HRL
```

### Install Isaac Gym

Download the Isaac Gym from the [official website](https://developer.nvidia.com/isaac-gym) and follow the installation instructions.

### Install Dribble-HRL and its dependencies

```bash
cd Dribble-HRL
pip install -e .
cd algo 
pip install -e .
```

### Something else
```bash
pip install tensorboard
```

## Run
### Train

```bash
cd scripts
python high_level_policy.py  # add --help to see more options
```

### Test

```bash
cd scripts
python play.py  # add --help to see more options
```



