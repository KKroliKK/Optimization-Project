# Optimization Project

Implementation of [Statistically Preconditioned Accelerated Gradient Method for Distributed Optimization](http://proceedings.mlr.press/v119/hendrikx20a/hendrikx20a.pdf)

The analysis and experiments are performed the notebooks:
1. `notebooks/theory.ipynb` - problem statement, description of SPAG method and convergence.
2. `notebooks/experiments.ipynb` - SPAG implementation, experiments, comparison with AGD.

## Authors

- Andrey Vagin (<a.vagin@innopolis.university>)
- Sergey Golubev (<s.golubev@innopolis.university>)

## Requirements

You can find the environment requirements in `requirements.txt`.

## Repository structure

```text
├── README.md       # The top-level README
|
├── data
│   ├── interim     # Intermediate data that has been transformed
│   └── raw         # The original, immutable data. Collected via src/mak_dataset.py script
|       └── rcv1_train.binary   # RCV1 dataset file 
|
├── notebooks   # Jupyter notebooks
│   └── theory.ipynb  # problem statement, description of SPAG method and convergence
│   └── experiments.ipynb  # SPAG implementation, experiments, comparison with AGD
|
├── interim submission   # Intermediate reports on the papers considered
│
├── references      # Reference papers
│
└── requirements.txt  # The requirements file for reproducing the analysis environment
                        generated with 'pip freeze › requirements.txt'
```

## References

### Papers

- [Statistically Preconditioned Accelerated Gradient Method for Distributed Optimization](http://proceedings.mlr.press/v119/hendrikx20a/hendrikx20a.pdf)

### Datasets

- [RCV1 Dataset](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html)
