# baduk-learning

[Deep Learning and the Game of Go](https://github.com/maxpumperla/deep_learning_and_the_game_of_go)

## Python

- [pyenv](https://github.com/pyenv/pyenv)
- [virtualenv](https://github.com/pyenv/pyenv-virtualenv)

```bash
pyenv virtualenv 3.7.4 baduk
pyenv activate baduk
pyenv deactivate
```

### Library

```bash
pip install -r requirements.txt
```

--- 

## Terminology

- [Minimax](https://en.wikipedia.org/wiki/Minimax)
- [Decision Tree Pruning](https://en.wikipedia.org/wiki/Decision_tree_pruning)
  - [Evaluation function](https://en.wikipedia.org/wiki/Evaluation_function)
  - [Alpha–beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)
- [Monte Carlo Tree Search](https://en.wikipedia.org/wiki/Monte_Carlo_tree_search)
  - [Monte Carlo Method](https://en.wikipedia.org/wiki/Monte_Carlo_method)
  - playout or roll-outs
  - Upper confidence bounds for trees: Bandit Algorithms for Tree Search - [paper](https://arxiv.org/pdf/1408.2028.pdf)
