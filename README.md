# APEBench: A Benchmark for Autoregressive Neural Emulators of PDEs

[Project Page (under construction)](https://tum-pbs.github.io/apebench-paper/)

## Paper

- ARXIV: coming soon
- [Neurips 2024](https://nips.cc/virtual/2024/poster/97550)

## Software components

- The main [APEBench benchmark suite](https://github.com/tum-pbs/apebench):
    - The [Fourier ETDRK solver](https://github.com/Ceyron/exponax)
    - The [Collection of Emulator Architectures](https://github.com/Ceyron/pdequinox)
    - The [Abstract implementation of training methodologies](https://github.com/Ceyron/trainax)
- The fast [4d volume renderer](https://github.com/KeKsBoTer/vape4d)

## Experimental Scripts, results and postprocessing

- [Main Part](https://huggingface.co/thuerey-group/apebench-paper)
- [Ablation Studies](https://huggingface.co/thuerey-group/apebench-paper-ablations)

## Datasets

APEBench is designed to be used a procedural data generator. However, for ease
of use, there is also a repository of scraped datasets:

- [APEBench version `0.1.0`](https://huggingface.co/datasets/thuerey-group/apebench-scraped)
- [State of APEBench during Neurips submission](https://huggingface.co/datasets/thuerey-group/apebench-scraped-old)