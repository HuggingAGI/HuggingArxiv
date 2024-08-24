# ssProp：通过计划稀疏反向传播实现卷积神经网络的节能训练

发布时间：2024年08月22日

`LLM理论` `环境保护`

> ssProp: Energy-Efficient Training for Convolutional Neural Networks with Scheduled Sparse Back Propagation

# 摘要

> 深度学习在生成建模领域，如大型语言模型和概率扩散模型，近期取得了显著成就。但训练这些模型需耗费大量计算资源，产生高额能源消耗和碳足迹，引发环境担忧。反向传播（BP）是深度学习训练中计算成本的主要来源。为此，我们提出了一种通用且节能的卷积模块，可无缝融入任何深度学习架构，旨在推进节能训练并支持在各类设备上进行稀疏学习。我们基于BP通常密集且低效的假设，在反向传播中引入通道稀疏性和梯度选择调度器，以减少过拟合和高计算消耗。实验显示，该方法能减少40%计算量，并可能提升模型性能，已在图像分类和生成任务中验证。这不仅在大规模AI系统研发阶段节省能源、降低碳足迹，还能以不同于Dropout的方式缓解过拟合，与Dropout结合进一步提升性能、减少资源使用。广泛实验证明，该方法适用于多种数据集和任务，与多种深度学习架构兼容。相关代码已公开于https://github.com/lujiazho/ssProp。

> Recently, deep learning has made remarkable strides, especially with generative modeling, such as large language models and probabilistic diffusion models. However, training these models often involves significant computational resources, requiring billions of petaFLOPs. This high resource consumption results in substantial energy usage and a large carbon footprint, raising critical environmental concerns. Back-propagation (BP) is a major source of computational expense during training deep learning models. To advance research on energy-efficient training and allow for sparse learning on any machine and device, we propose a general, energy-efficient convolution module that can be seamlessly integrated into any deep learning architecture. Specifically, we introduce channel-wise sparsity with additional gradient selection schedulers during backward based on the assumption that BP is often dense and inefficient, which can lead to over-fitting and high computational consumption. Our experiments demonstrate that our approach reduces 40\% computations while potentially improving model performance, validated on image classification and generation tasks. This reduction can lead to significant energy savings and a lower carbon footprint during the research and development phases of large-scale AI systems. Additionally, our method mitigates over-fitting in a manner distinct from Dropout, allowing it to be combined with Dropout to further enhance model performance and reduce computational resource usage. Extensive experiments validate that our method generalizes to a variety of datasets and tasks and is compatible with a wide range of deep learning architectures and modules. Code is publicly available at https://github.com/lujiazho/ssProp.

[Arxiv](https://arxiv.org/abs/2408.12561)