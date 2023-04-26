# 1D Demos of Sparsity-constrained Optimal Transport

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yxxeqrlKsGrhoqLmY7IjJNgOJnd3Pvu1?usp=sharing)

This repository contains a Google Colab notebook demonstrating sparsity-constrained optimal transport, as proposed in our publication:

> Liu, T., Puigcerver, J., & Blondel, M. (2023). [Sparsity-constrained optimal transport](https://openreview.net/forum?id=yHY9NbQJ5BP). Proceedings of the Eleventh International Conference on Learning Representations (ICLR).

In this repository, we focus on 1D problems: transporting between 1D distributions. The official implementation in the [vmoe](https://github.com/google-research/vmoe/tree/main/vmoe/projects/sparsity_constrained_ot) repository includes additional demos showcasing applications in 2D, color transfer, and vision mixture-of-experts models. 

While the official [vmoe](https://github.com/google-research/vmoe/tree/main/vmoe/projects/sparsity_constrained_ot) repository is based on JAX, this repository also demonstrates the usage of sparsity-constrained OT in PyTorch (thanks to the backend system in [POT](https://github.com/PythonOT/POT)).

  <img src="https://user-images.githubusercontent.com/10226549/234486514-f5e45d28-b69b-40ed-aefb-e4930c1fb6bb.png" width="90%" />
<p align="center">
Optimal transport between two 1D Gaussians.
</p>



## Getting Started

To try out the demo notebook, click the "Open in Colab" button above or access it [here](https://colab.research.google.com/drive/1yxxeqrlKsGrhoqLmY7IjJNgOJnd3Pvu1?usp=sharing). 

## Citation

If you find our work useful in your research, please consider citing:

```
@inproceedings{
  liu2023sparsity,
  title={Sparsity-constrained optimal transport},
  author={Tianlin Liu, Joan Puigcerver, Mathieu Blondel},
  booktitle={Proceedings of the Eleventh International Conference on Learning Representations (ICLR)},
  year={2023},
  url={https://openreview.net/forum?id=yHY9NbQJ5BP}
}
```
