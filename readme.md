## Project Overview

This project implements the CV_LR algorithm based on the `causallearn` package. Below is an overview of the directories and scripts included in this project:

- **data/**: Contains the Sachs and Child real datasets.
- **data_generate.py**: Used to generate synthetic data.
- **GES.py**: Contains the implementation of various algorithms including CV and CV_LR.
- **main.py**: Used to conduct experiments. The following parameters can be specified:
  - `method`: Selects the method to use.
  - `dataset`: Chooses different datasets.
  - `graph_density`: Selects the graph density for synthetic data in experiments.
  - `generate`: Chooses whether to generate new synthetic data or use existing ones.
  - `epoch`: Specifies the number of experiment iterations.


## Usage

To use this project, simply run the following command:

```sh
python main.py
```

## Bibtex
If you find this code useful, please cite our paper:

```
@inproceedings{ren2025fast,
  title={Fast causal discovery by approximate kernel-based generalized score functions with linear computational complexity},
  author={Ren, Yixin and Zhang, Haocheng and Xia, Yewei and Zhang, Hao and Guan, Jihong and Zhou, Shuigeng},
  booktitle={Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 1},
  pages={1197--1208},
  year={2025}
}
```

