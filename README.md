# Baselines

This repository contains baseline systems for  SIGMORPHON 2020 Task 0.


## Non-Neural Baseline
The first baseline is a non-neural system that has been used as a baseline in earlier shared tasks on morphological reinflection, now available [HERE](https://github.com/sigmorphon/conll2018/tree/master/task1/baseline)

## Neural Baseline
The second baseline is hard monotonic attention [(Wu and Cotterell, 2019)](https://arxiv.org/abs/1905.06319) and the transformer [(Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762), both one model per language and one model per language family.

Setup the submodule by

```bash
git submodule update --init --recursive
```
