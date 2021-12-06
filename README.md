# 0. introduction

This project has bene carried out in the 2021 fall semester of the department of industrial engineering at Hanyang University.

This project is based on the main idea of the following papers

"Densely connected convolutional networks" and "Gaussian-based pooling for convolutional neural networks"

Based on the CNN network we introduce 6 different pooling methods in bottlenek layers

'max', 'avg', 'gauss_HWCN', 'gauss_CN', 'gauss_half_HWCN', 'gauss_half_CN'


# 1. requirements

python=3.5

numpy

torch=1.0

torchvision

torchsummary

cifar-10 dataset


# 2. models

DensNet-100-12 : # of layers: 100, growth rate: 12, theta: 0.5, drop rate: 0.2

DensNet-101-12 : # of layers: 101, growth rate: 12, theta: 0.5, drop rate: 0.2

DensNet-103-12 : # of layers: 103, growth rate: 12, theta: 0.5, drop rate: 0.2

13-Layers Network : # of layers: 13


# 3. code execution

ptype -> 'max', 'avg', 'gauss_HWCN', 'gauss_CN', 'gauss_half_HWCN', 'gauss_half_CN'

ptype = 

# 4. attributors

박우찬, 유병철, 유재성, 이명진, 이상훈
