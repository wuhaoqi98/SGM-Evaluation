# Sparse Graphical Memory (SGM) Evaluation

This project is an evaluation of SGM for the purpose of a course project. Please refer to https://mishalaskin.github.io/sgm/ for original implementation. 
The evaluation code is located in notebook folder.

[Sparse Graphical Memory (SGM)](https://mishalaskin.github.io/sgm/) is a data structure for reinforcement-learning agents to solve long-horizon, sparse-reward navigation tasks.
This codebase is a TensorFlow implementation of SGM accompanying the paper [Sparse Graphical Memory for Robust Planning](https://arxiv.org/abs/2003.06417).


## To install:
1. Create a new conda environment: `conda create -n sgm python=3.6`
2. Activate the conda environment: `conda activate sgm`
3. Install the requirements: `pip install -r requirements.txt`
4. Install the package: `pip install -e .`


## Credits

This code was built upon the [code released by Eysenbach et al.](http://bit.ly/rl_search) under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).


## Reference

```
@inproceedings{emmons2020sparse,
  Author = {Emmons, Scott and Jain, Ajay and
  Laskin, Michael and Kurutach, Thanard
  and Abbeel, Pieter and Pathak, Deepak},
  Title = {Sparse Graphical Memory
  for Robust Planning},
  Booktitle = {Neural Information Processing
  Systems},
  Year = {2020}
}
```
