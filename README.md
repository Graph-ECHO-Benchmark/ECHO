<div align="center">

# Can You Hear Me Now? A Benchmark for Long-Range Graph Propagation

[![Paper](https://img.shields.io/badge/Paper-OpenReview-red.svg)](https://openreview.net/forum?id=DgkWFPZMPp)
[![Dataset](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Datasets-blue.svg)](https://huggingface.co/datasets/lucamiglior/echo-benchmark)

*Published at the International Conference on Learning Representations (ICLR) 2026*

</div>



## Overview

**ECHO** is a novel benchmark designed to rigorously test the long-range information propagation capabilities of Graph Neural Networks (GNNs). While current benchmarks often focus on local interactions, ECHO introduces both synthetic and real-world tasks where successful prediction requires traversing up to **40 hops** in a graph.

## Leaderboards

(last update Dec 23rd 2025)

### ECHO-Synth

<details>
<summary> <b>Diameter</b> (Graph Regression) </summary>

Model | MAE (Mean ± Std) | Reference| Contact | Date | 
| :--- | :---: | --- | --- | --- |
| A-DGN    | 1.151 ± 0.038      | [Gravina et al, ICLR 2023](https://openreview.net/forum?id=J3Y7cgZOOS) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| DRew     | 1.243 ± 0.047      | [Gutteridge et al, ICML 2023](https://proceedings.mlr.press/v202/gutteridge23a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GCN      | 3.832 ± 0.262      | [Kipf et al, ICLR 2017](https://openreview.net/forum?id=SJU4ayYgl) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GCNII    | 2.005 ± 0.093      | [Chen et al, ICML 2020](https://proceedings.mlr.press/v119/chen20v.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GIN      | 1.630 ± 0.161      | [Xu et al, ICLR 2019](https://openreview.net/forum?id=ryGs6iA5Km) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GPS      | 2.160 ± 0.098      | [Rampášek et al, NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/5d4834a159f1547b267a05a4e2b7cf5e-Abstract-Conference.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GraphCON | 2.969 ± 0.189      | [Rusch et al, ICML 2022](https://proceedings.mlr.press/v162/rusch22a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GRIT     | **1.014** ± 0.046  | [Ma et al, ICML 2023](https://proceedings.mlr.press/v202/ma23c.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| PH-DGN   | 1.627 ± 0.398      | [Heilig et al, ICLR 2025](https://openreview.net/forum?id=03EkqSCKuO) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| SWAN     | 1.121 ± 0.070      | [Gravina et al, AAAI 2025](https://ojs.aaai.org/index.php/AAAI/article/view/33858) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
</details>

<details>
<summary> <b>Eccentricity</b> (Node Regression) </summary>

Model | MAE (Mean ± Std) | Reference| Contact | Date | 
| :--- | :---: | --- | --- | --- |
| A-DGN     | 4.981 ± 0.037     | [Gravina et al, ICLR 2023](https://openreview.net/forum?id=J3Y7cgZOOS) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| DRew      | **4.651** ± 0.020 | [Gutteridge et al, ICML 2023](https://proceedings.mlr.press/v202/gutteridge23a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GCN       | 5.233 ± 0.034     | [Kipf et al, ICLR 2017](https://openreview.net/forum?id=SJU4ayYgl) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GCNII     | 5.241 ± 0.030     | [Chen et al, ICML 2020](https://proceedings.mlr.press/v119/chen20v.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GIN       | 4.869 ± 0.092     | [Xu et al, ICLR 2019](https://openreview.net/forum?id=ryGs6iA5Km) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GPS       | 4.758 ± 0.021     | [Rampášek et al, NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/5d4834a159f1547b267a05a4e2b7cf5e-Abstract-Conference.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GraphCON  | 5.474 ± 0.001     | [Rusch et al, ICML 2022](https://proceedings.mlr.press/v162/rusch22a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GRIT      | 5.091 ± 0.158     | [Ma et al, ICML 2023](https://proceedings.mlr.press/v202/ma23c.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| PH-DGN    | 5.068 ± 0.126     | [Heilig et al, ICLR 2025](https://openreview.net/forum?id=03EkqSCKuO) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| SWAN      | 4.840 ± 0.045     | [Gravina et al, AAAI 2025](https://ojs.aaai.org/index.php/AAAI/article/view/33858) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
</details>

<details>
<summary> <b>Single Source Shorthest Path</b> (Node Regression) </summary>

Model | MAE (Mean ± Std) | Reference| Contact | Date | 
| :--- | :---: | --- | --- | --- |
| A-DGN     | 1.176 ± 0.140     | [Gravina et al, ICLR 2023](https://openreview.net/forum?id=J3Y7cgZOOS) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| DRew      | 1.279 ± 0.011     | [Gutteridge et al, ICML 2023](https://proceedings.mlr.press/v202/gutteridge23a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GCN       | 2.102 ± 0.094     | [Kipf et al, ICLR 2017](https://openreview.net/forum?id=SJU4ayYgl) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GCNII     | 2.128 ± 0.429     | [Chen et al, ICML 2020](https://proceedings.mlr.press/v119/chen20v.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GIN       | 2.234 ± 0.271     | [Xu et al, ICLR 2019](https://openreview.net/forum?id=ryGs6iA5Km) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GPS       | 0.472 ± 0.050     | [Rampášek et al, NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/5d4834a159f1547b267a05a4e2b7cf5e-Abstract-Conference.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GraphCON  | 5.734 ± 0.011     | [Rusch et al, ICML 2022](https://proceedings.mlr.press/v162/rusch22a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GRIT      | **0.121** ± 0.013 | [Ma et al, ICML 2023](https://proceedings.mlr.press/v202/ma23c.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| PH-DGN    | 1.323 ± 0.485     | [Heilig et al, ICLR 2025](https://openreview.net/forum?id=03EkqSCKuO) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| SWAN      | 0.896 ± 0.232     | [Gravina et al, AAAI 2025](https://ojs.aaai.org/index.php/AAAI/article/view/33858) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
</details>


### ECHO-Chem

<details>
  <summary> <b>Energy</b> (Graph Regression) </summary>

| Model | MAE (Mean ± Std) | Reference| Contact | Date | 
| :--- | :---: | --- | --- | --- |
| A-DGN     | 12.486 ± 1.621    | [Gravina et al, ICLR 2023](https://openreview.net/forum?id=J3Y7cgZOOS) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| DRew      | 11.325 ± 2.394    | [Gutteridge et al, ICML 2023](https://proceedings.mlr.press/v202/gutteridge23a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GCN       | 28.112 ± 1.239    | [Kipf et al, ICLR 2017](https://openreview.net/forum?id=SJU4ayYgl) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GCNII     | 13.235 ± 2.630    | [Chen et al, ICML 2020](https://proceedings.mlr.press/v119/chen20v.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GIN       | 47.851 ± 10.154   | [Xu et al, ICLR 2019](https://openreview.net/forum?id=ryGs6iA5Km) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GINE      | 23.558 ± 7.568    | [Hu et al, ICLR 2020](https://openreview.net/forum?id=HJlWWJSFDH) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GPS       | **5.257** ± 0.842 | [Rampášek et al, NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/5d4834a159f1547b267a05a4e2b7cf5e-Abstract-Conference.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GraphCON  | 14.295 ± 0.807    | [Rusch et al, ICML 2022](https://proceedings.mlr.press/v162/rusch22a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GRIT      | 25.508 ± 2.507    | [Ma et al, ICML 2023](https://proceedings.mlr.press/v202/ma23c.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| PH-DGN    | 16.080 ± 1.123    | [Heilig et al, ICLR 2025](https://openreview.net/forum?id=03EkqSCKuO) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| SWAN      | 12.629 ± 1.157    | [Gravina et al, AAAI 2025](https://ojs.aaai.org/index.php/AAAI/article/view/33858) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
</details>


<details>
  <summary> <b>Charge</b> (Node Regression) </summary>

| Model | MAE (Mean ± Std) $\times 10^{-3}$ | Reference| Contact | Date | 
| :--- | :---: | --- | --- | --- |
| A-DGN     | 6.543 ± 0.146     | [Gravina et al, ICLR 2023](https://openreview.net/forum?id=J3Y7cgZOOS) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| DRew      | 9.086 ± 0.473     | [Gutteridge et al, ICML 2023](https://proceedings.mlr.press/v202/gutteridge23a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GCN       | 8.421 ± 0.512     | [Kipf et al, ICLR 2017](https://openreview.net/forum?id=SJU4ayYgl) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GCNII     | 8.829 ± 0.021     | [Chen et al, ICML 2020](https://proceedings.mlr.press/v119/chen20v.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GIN       | 10.784 ± 0.059    | [Xu et al, ICLR 2019](https://openreview.net/forum?id=ryGs6iA5Km) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GINE      | 7.176 ± 0.371     | [Hu et al, ICLR 2020](https://openreview.net/forum?id=HJlWWJSFDH) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 | 
| GPS       | 6.182 ± 0.219     | [Rampášek et al, NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/5d4834a159f1547b267a05a4e2b7cf5e-Abstract-Conference.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GRIT      | 7.134 ± 6.090     | [Rusch et al, ICML 2022](https://proceedings.mlr.press/v162/rusch22a.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| GraphCON  | 19.629 ± 0.195    | [Ma et al, ICML 2023](https://proceedings.mlr.press/v202/ma23c.html) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| PH-DGN    | 7.915 ± 0.269     | [Heilig et al, ICLR 2025](https://openreview.net/forum?id=03EkqSCKuO) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
| SWAN      | **6.109** ± 0.103 | [Gravina et al, AAAI 2025](https://ojs.aaai.org/index.php/AAAI/article/view/33858) |   [Luca Miglior - ECHO Team](mailto:luca.miglior@phd.unipi.it) | Dec 23, 2025 |
</details>

---

## 🚀 Getting Started

### PyG-friendly implementation
Please refer to [the code in the ```PyG_implementation``` folder]([https://github.com/Graph-ECHO-Benchmark/ECHO/PyG_implementation](https://github.com/Graph-ECHO-Benchmark/ECHO/tree/main/PyG_implementation)) for a minimal example on the PyG ecosystem. 


### Installation

We recommend using [uv](https://github.com/astral-sh/uv) for fast and reliable dependency management.

```bash
# Create a virtual environment
uv init
# Install dependencies
uv sync
```

### Downloading Data

You can download the datasets using the provided script. This will automatically fetch the required files from Hugging Face.

```bash
# Download all tasks
python scripts/download-all.py

# Or download specific tasks
python scripts/download-all.py --task diam
python scripts/download-all.py --task charge
```

---

## 📦 Datasets

### 🧪 ECHO-Synth
A synthetic dataset suite of **10,080 graphs** across six topologies: `line`, `ladder`, `grid-like`, `tree`, `caterpillar`, `lobster`.

Tasks:
- **Single-source shortest path (sssp)**
- **Node eccentricity (ecc)**
- **Graph diameter (diam)**

Each task isolates different aspects of global graph property prediction.

### 🧪 ECHO-Chem
A **real-world molecular dataset** of **200k molecular graphs**.

Tasks:
- **Atomic partial charges (charge)**: Node-level regression requiring long-range atomic interaction modeling.
- **Energy (energy)**: Graph-level regression task.

---

## 💻 Usage

### 📓 Notebooks (Recommended)
For ease of use, we provide Jupyter notebooks to guide you through training and inference:

- **`notebooks/train-model.ipynb`**: Step-by-step guide to training a model on ECHO tasks.
- **`notebooks/make-predictions.ipynb`**: Load a trained checkpoint and generate predictions.

### 🧠 Training from CLI
You can also train models directly using the command line script:

```bash
python scripts/train.py \
    --task diam \
    --gnn_type GNN \
    --conv_layer GCNConv \
    --hidden_dim 128 \
    --num_layers 8 \
    --lr 0.001 \
    --batch_size 512
```

### 🔎 Hyperparameter Search
To run a hyperparameter search (using Ray Tune and Optuna):

```bash
# Run search for diameter task
python scripts/search.py --tasks diam --n_samples 32

# Or use the helper script
bash scripts/run_search.sh
```

---


## 📚 Citation

If you use ECHO in your research, please cite our paper:

```bibtex
@article{echobenchmark,
    title={{Can You Hear Me Now? A Benchmark for Long-Range Graph Propagation}}, 
    author={Luca Miglior and Matteo Tolloso and Alessio Gravina and Davide Bacciu},
    booktitle={The Fourteenth International Conference on Learning Representations},
    year={2026},
    url={https://openreview.net/forum?id=DgkWFPZMPp}
}
```

