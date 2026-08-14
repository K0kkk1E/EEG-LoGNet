# EEG-LoGNet

Official implementation of **EEG-LoGNet**, a compact local--global fusion network for EEG-based motor imagery decoding.

> **Code Availability**  
> The source code, training scripts, configuration files, and experimental details will be publicly released after the paper is accepted.

## Overview

EEG-LoGNet is a compact neural network designed for EEG-based brain--computer interface decoding. The model couples local feature extraction and global temporal modeling through a trial-adaptive fusion mechanism, aiming to achieve accurate and stable decoding with a small number of trainable parameters.

The proposed framework includes:

- An ASPP-CNN stream for multi-scale local feature extraction
- An ARF-Former stream for adaptive receptive-field global modeling
- A CCGF module for confidence-routed local--global feature fusion

## Paper Status

The manuscript is currently under review.

More details, including the full implementation, training pipeline, preprocessing protocol, and evaluation scripts, will be released upon acceptance of the paper.

## Dataset

Experiments are conducted on the **BCI Competition IV-2a** dataset.

Please refer to the official dataset provider for data access and usage requirements.


## Citation

If you find this work useful, please consider citing our paper:

```bibtex
@article{your_paper_2026,
  title   = {Your Paper Title},
  author  = {Author Name and Author Name and Author Name},
  journal = {Journal or Conference Name},
  year    = {2026}
}
```
The citation information will be updated after publication.

## License

The license will be specified when the code is released.
