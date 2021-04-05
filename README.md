# PersonAttributeRecognition
This code repository includes the source code for the [Paper](https://arxiv.org/abs/1810.04650):

```
Multi-Task Learning as Multi-Objective Optimization
Ozan Sener, Vladlen Koltun
Neural Information Processing Systems (NeurIPS) 2018 
```

# Requirements and References
The code uses the following Python packages and they are required: ``tensorboardX, pytorch-1.4.0, click, numpy, torchvision, tqdm, scipy, Pillow``


# Usage
The code base uses `configs.json` for the global configurations like dataset directories, etc.. Experiment specific parameters are provided seperately as a json file. See the `sample.json` for an example.

To train a model, use the command: 
```bash
python multi_task/train_multi_task.py --param_file=./sample.json
```

@incollection{NeurIPS2018_Sener_Koltun,
title = {Multi-Task Learning as Multi-Objective Optimization},
author = {Sener, Ozan and Koltun, Vladlen},
booktitle = {Advances in Neural Information Processing Systems 31},
editor = {S. Bengio and H. Wallach and H. Larochelle and K. Grauman and N. Cesa-Bianchi and R. Garnett},
pages = {525--536},
year = {2018},
publisher = {Curran Associates, Inc.},
url = {http://papers.nips.cc/paper/7334-multi-task-learning-as-multi-objective-optimization.pdf}
}
