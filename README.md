# MMDNE
Source code for CIKM 2019 paper "**Temporal Network Embedding with Micro- and Macro-dynamics**"

# Requirements

- Python 2.7
- numpy
- scipy
- PyTorch (0.3.0)
- My machine with two GPUs (NVIDIA GTX-1080 *2) and two CPUs (Intel Xeon E5-2690 * 2)

# Description

```
RHINE/
├── code
│   ├── DataHelper.py: load and process data for $\text{M^2DNE}$
│   ├── Evaluation.py: evaluate the performance of $\text{M^2DNE}$ (e.g., classification)
│   └── MMDNE.py: model architecture and training
├── data
│   └── dblp
│       ├── dblp.txt: each line is a temporal edge with the format (node1 \ tnode2 \t timestamp)
│       ├── node2label.txt: node label data with the format (node_name, label)
│   └── Tmall
│       ├── tmall.txt: each line is a temporal edge with the format (node1 \ tnode2 \t timestamp)
│       ├── node2label.txt: node label data with the format (node_name, label)
└── res
│    └── dblp
│        └──
├── README.md
```

# Usage:
python MMDNE.py


# Reference

```
@inproceedings{Yuanfu2019RHINE,
  title={Temporal Network Embedding with Micro- and Macro-dynamics},
  author={Yuanfu Lu, Xiao Wang, Chuan Shi, Philip S. Yu, Yanfang Ye.}
  booktitle={Proceedings of CIKM},
  year={2019}
}

```


