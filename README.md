# Long-tailed Classification from a Bayesian-decision-theory Perspective
[This paper](https://openreview.net/forum?id=sz7d2cKXVb) develops a unified framework from Bayesian Decision Theory to address the problem of long-tailed classification. It unifies previous techniques like re-balancing loss and ensembling, and provides theoretical justification for their efficacy. The experiments demonstrate that our method improves over existing baselines for long-tailed classification.

## Recommended Environment
```
python==3.8
pytorch==1.8.2
```

## Command
```
python main.py -c "configs/cifar100_lt.json"
```

## Citation
```
@inproceedings{lilong,
  title={Long-tailed Classification from a Bayesian-decision-theory Perspective},
  author={Li, Bolian and Zhang, Ruqi},
  booktitle={Fifth Symposium on Advances in Approximate Bayesian Inference}
}
```
