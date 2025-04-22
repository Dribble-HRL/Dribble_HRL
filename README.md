# Dribble-HRL ⚽

> [!IMPORTANT]  
> Work in progress

This repository contains an official implementation of our paper:
***Dynamic Legged Ball Manipulation on Rugged Terrains with Hierarchical Reinforcement Learning***.
For more information, see our paper and video.

<h3> <a href="https://github.com/locomanip-duet/locomanip-duet.github.io/blob/master/RoboDuet.pdf">📝 Paper</a> | <a href="https://locomanip-duet.github.io/"> 🌐 Website</a> | <a href="https://youtu.be/7Hf6mCO0mZU?si=6pKfS5zPOw_5GbGS"> 🎬 Video</a></h3>

</br>

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
[Dribble_HRL]$ pip install -e .
[Dribble_HRL]$ cd algo 
[algo]$ pip install -e .
```

### Something else
```bash
pip install tensorboard
```
</br>

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

</br>

## Acknowledgement
The base implementation for IsaacGym environment is largely borrowed from [DribbleBot](https://github.com/Improbable-AI/dribblebot). 
The PPO implementation is based on [rsl_rl](https://github.com/leggedrobotics/rsl_rl).
We are deeply grateful for their contribution to the open-source community.

</br>

## Citation
```
@misc{zhu2025dynamicleggedballmanipulation,
      title={Dynamic Legged Ball Manipulation on Rugged Terrains with Hierarchical Reinforcement Learning}, 
      author={Dongjie Zhu and Zhuo Yang and Tianhang Wu and Luzhou Ge and Xuesong Li and Qi Liu and Xiang Li},
      year={2025},
      eprint={2504.14989},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2504.14989}, 
}
```
