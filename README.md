# AWS Neuron Samples

This repository contains samples for [AWS Neuron](https://aws.amazon.com/machine-learning/neuron/), the software development kit (SDK) that enables machine learning (ML) inference and training workloads on the AWS ML accelerator chips [Inferentia](https://aws.amazon.com/machine-learning/inferentia/) and [Trainium](https://aws.amazon.com/machine-learning/trainium/).

The samples in this repository provide an indication of the types of deep learning models that can be used with Trainium and Inferentia, but do not represent an exhaustive list of supported models. If you have additional model samples that you would like to contribute to this repository, please submit a pull request following the repository's contribution [guidelines](CONTRIBUTING.md).

Samples are organized by use case (training, inference) and deep learning framework (PyTorch, TensorFlow) below:

## Training

| Framework | Description | Supported EC2 Instance Type |
| --- | --- | --- |
| [PyTorch Neuron](torch-neuronx/training) | Sample training scripts for training various PyTorch models on AWS Trainium | trn1 |

## Inference

| Framework | Description | Supported EC2 Instance Type |
| --- | --- | --- |
| [PyTorch Neuron](torch-neuron/inference) | Sample Jupyter notebooks demonstrating model compilation and inference for various PyTorch models on AWS Inferentia | inf1 |
| [TensorFlow Neuron](torch-neuron/tensorflow) | Sample Jupyter notebooks demonstrating model compilation and inference for various TensorFlow models on AWS Inferentia | inf1 |

## Getting Help

If you encounter issues with any of the samples in this repository, please open an issue via the GitHub Issues feature.

## Contributing

Please refer to the [CONTRIBUTING](CONTRIBUTING.md) document for details on contributing additional samples to this repository.
