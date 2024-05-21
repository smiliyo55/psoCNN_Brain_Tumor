# Brain Tumor Classification with Particle Swarm Optimization (PSO)

This repository contains code adapted from the original work by Francisco Erivaldo Fernandes Junior on Particle Swarm Optimization (PSO) of deep neural networks architectures for image classification. This adaptation was conducted by Smili Youssef under the supervision of Professor Douda Sofia. We have modified and extended the original implementation to apply it to the task of brain tumor classification using a dataset specific to this domain.

## Overview

Our project aims to leverage PSO in conjunction with deep learning techniques to classify brain tumor images accurately. The PSO algorithm optimizes the architecture of deep neural networks for image classification tasks, allowing for efficient exploration of the model space.

## Dataset

We utilize a brain tumor dataset specifically curated for this project. You can find the dataset [here](link_to_dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset). The dataset includes a diverse set of brain tumor images for training and evaluation.

## Changes and Modifications

While the original repository used Keras for implementing neural network architectures, we have adapted the code to use PyTorch by adding a class that generates the model. This significant modification enables us to take advantage of PyTorch's functionalities and seamlessly integrate our models with other PyTorch-based workflows.

## Credits

This project is based on the work of Francisco Erivaldo Fernandes Junior. The original repository can be found [here](link_to_original_repository](https://github.com/feferna/psoCNN.git).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
