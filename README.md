# 0. introduction

This project has bene carried out in the 2021 fall semester of the department of industrial engineering at Hanyang University.

This project is based on the main idea of the following papers

"Densely connected convolutional networks" and "Gaussian-based pooling for convolutional neural networks"

Based on the DenseNet we introduce 6 different pooling methods in bottlenek layers(DenseNet_standard)

'max', 'avg', 'gauss_HWCN', 'gauss_CN', 'gauss_half_HWCN', 'gauss_half_CN'

And we also tried to extends the lengh of the denseblock(DenseNet_4blocks/DenseNet_6blocks), 

and tested the original 13layers presented in the original papar(13layers_network)


# 1. requirements

python=3.5

numpy

torch=1.0

torchvision

torchsummary

cifar-10 dataset


# 2. models

DenseNet_standard : DensNet-100-12

DenseNet_4blocks : DensNet-101-12

DenseNet_6blocks : DensNet-103-12

13-Layers Network


# 3. code execution

ptype -> 'max', 'avg', 'gauss_HWCN', 'gauss_CN', 'gauss_half_HWCN', 'gauss_half_CN'

ptype = 

# 4. attributors

박우찬, 유병철, 유재성, 이명진, 이상훈
