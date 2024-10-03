# 从 LLM 的旋转对称性中找回免费比特

发布时间：2024年10月02日

`LLM理论` `人工智能` `数据压缩`

> Getting Free Bits Back from Rotational Symmetries in LLMs

# 摘要

> 现有的神经网络权重压缩方法，如分解、剪枝等，往往忽视了网络中的固有对称性，导致编码冗余信息时浪费比特。本文提出了一种基于比特回退编码的新格式，能更高效地存储旋转对称Transformer权重，相比传统数组布局，在相同浮点精度下节省3-5%的比特使用量，且不影响模型性能。我们在SliceGPT剪枝的LLM上验证了这一方法，效果显著。

> Current methods for compressing neural network weights, such as decomposition, pruning, quantization, and channel simulation, often overlook the inherent symmetries within these networks and thus waste bits on encoding redundant information. In this paper, we propose a format based on bits-back coding for storing rotationally symmetric Transformer weights more efficiently than the usual array layout at the same floating-point precision. We evaluate our method on Large Language Models (LLMs) pruned by SliceGPT (Ashkboos et al., 2024) and achieve a 3-5% reduction in total bit usage for free across different model sizes and architectures without impacting model performance within a certain numerical precision.

[Arxiv](https://arxiv.org/abs/2410.01309)