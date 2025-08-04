Overview:
This project is a faithful reproduction of the Vision Transformer (ViT) architecture described in the original paper "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale" (Dosovitskiy et al., 2020). The goal is to learn the internals of the ViT model by implementing it step-by-step using PyTorch, using only the details provided in the paper's Tables and Equations.

Features:

Implements ViT-Base configuration as described in the paper (Table 1 and Table 3)

Patch embedding and position encoding

Multi-head self-attention (MSA) block

Feedforward MLP block with residual connections

Layer normalization applied before every block (pre-norm)

Simple visualizations of the patching process

Designed for educational and research use

File Structure:

vit_model.py — Contains the full implementation of the Vision Transformer

vit_blocks.py — Defines the MSA and MLP blocks

train.py — Script to train the ViT model on a sample image dataset (e.g., CIFAR-10)

utils.py — Contains helper functions such as patching and visualization

notebooks/ — Contains step-by-step Jupyter/Colab notebooks explaining each stage of the model

Requirements:

Python 3.8+

PyTorch

torchvision

matplotlib

numpy

Getting Started:
To get started, clone this repository, install the requirements, and open the notebooks to walk through the ViT implementation piece by piece.

Why This Project:
Most ViT tutorials skip over the details of the original paper or use pre-built modules. This project is meant for those who want to deeply understand how ViT works under the hood and replicate each architectural piece from scratch.

Credits:
Paper: Dosovitskiy et al. (2020) - "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"
Link: https://arxiv.org/abs/2010.11929

License:
MIT License
