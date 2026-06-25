# PyTorch Geometric-friendly implementation
This framework provides a PyTorch Geometric-friendly implementation of our ECHO Benchmark.
The minimal example provided follows the experimental design of the [original ECHO Benchmark reference code](https://github.com/Graph-ECHO-Benchmark/ECHO/). The benchmark has been proposed for inclusion in PyTorch Geometric through [PR](https://github.com/pyg-team/pytorch_geometric/pull/10648).


## Usage:
For a complete list of available arguments and options, run:

```python echo_benchmark_example.py --help```

The following commands are provided for illustration purposes only and do not necessarily correspond to the hyperparameters used in the original ECHO experiments.


- ```python echo_benchmark_example.py --task sssp```

- ```python echo_benchmark_example.py --task diam --epochs 20```

- ```python echo_benchmark_example.py --task energy --batch_size 16```
