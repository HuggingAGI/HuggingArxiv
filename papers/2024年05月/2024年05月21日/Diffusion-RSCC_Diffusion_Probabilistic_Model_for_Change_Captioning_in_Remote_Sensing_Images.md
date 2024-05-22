# 扩散-RSCC：遥感图像变化描述的扩散概率模型

发布时间：2024年05月21日

`Agent

这篇论文主要介绍了一种基于概率扩散模型的新方法，用于解决遥感图像变化描述（RSICC）任务中的问题。该方法通过构建跨模态特征的噪声预测器，并利用马尔可夫链学习从真实描述到标准高斯分布的转换，以及通过跨模态融合和堆叠自注意力模块优化反向过程的噪声预测。这种方法在测试时能够准确估计分布均值，逐步生成变化描述。因此，这篇论文更偏向于介绍一个具体的Agent模型，用于处理特定的遥感图像变化描述任务。` `环境监测`

> Diffusion-RSCC: Diffusion Probabilistic Model for Change Captioning in Remote Sensing Images

# 摘要

> 遥感图像变化描述（RSICC）旨在用人类般的语言描述不同时期遥感图像间的语义变化，为环境监测和土地管理提供深刻洞见。与传统任务不同，RSICC不仅需跨模态检索信息并生成流畅描述，还需减少像素级差异对地形变化定位的干扰。长时间跨度导致的像素问题影响了描述的准确性。受扩散模型强大生成能力的启发，我们提出了一种概率扩散模型，旨在解决这些问题。训练中，我们构建了一个基于跨模态特征的噪声预测器，通过马尔可夫链学习从真实描述到标准高斯分布的转换。同时，设计了跨模态融合和堆叠自注意力模块以优化反向过程的噪声预测。测试时，训练有素的噪声预测器能准确估计分布均值，逐步生成变化描述。在LEVIR-CC数据集上的实验充分验证了我们的Diffusion-RSCC方法及其组件的有效性，定量分析显示在传统与新增度量上均超越现有技术。相关代码和材料将在https://github.com/Fay-Y/Diffusion-RSCC公开。

> Remote sensing image change captioning (RSICC) aims at generating human-like language to describe the semantic changes between bi-temporal remote sensing image pairs. It provides valuable insights into environmental dynamics and land management. Unlike conventional change captioning task, RSICC involves not only retrieving relevant information across different modalities and generating fluent captions, but also mitigating the impact of pixel-level differences on terrain change localization. The pixel problem due to long time span decreases the accuracy of generated caption. Inspired by the remarkable generative power of diffusion model, we propose a probabilistic diffusion model for RSICC to solve the aforementioned problems. In training process, we construct a noise predictor conditioned on cross modal features to learn the distribution from the real caption distribution to the standard Gaussian distribution under the Markov chain. Meanwhile, a cross-mode fusion and a stacking self-attention module are designed for noise predictor in the reverse process. In testing phase, the well-trained noise predictor helps to estimate the mean value of the distribution and generate change captions step by step. Extensive experiments on the LEVIR-CC dataset demonstrate the effectiveness of our Diffusion-RSCC and its individual components. The quantitative results showcase superior performance over existing methods across both traditional and newly augmented metrics. The code and materials will be available online at https://github.com/Fay-Y/Diffusion-RSCC.

[Arxiv](https://arxiv.org/abs/2405.12875)