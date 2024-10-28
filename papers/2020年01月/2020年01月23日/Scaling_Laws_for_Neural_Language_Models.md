# 神经语言模型的缩放定律

发布时间：2020年01月23日

`LLM理论` `语言模型` `计算效率`

> Scaling Laws for Neural Language Models

# 摘要

> 摘要：我们研究了语言模型在交叉熵损失上的经验缩放定律。损失与模型大小、数据集大小以及用于训练的计算量呈幂律关系，一些趋势跨越了七个数量级以上。其他架构细节，如网络宽度或深度，在很大范围内影响极小。简单的方程控制着过拟合对模型/数据集大小的依赖关系，以及训练速度对模型大小的依赖关系。这些关系使我们能够确定固定计算预算的最优分配。较大的模型在样本方面效率显著更高，因此最优的计算效率训练包括在相对适度的数据量上训练非常大的模型，并在收敛前显著停止。

> 
Abstract:We study empirical scaling laws for language model performance on the cross-entropy loss. The loss scales as a power-law with model size, dataset size, and the amount of compute used for training, with some trends spanning more than seven orders of magnitude. Other architectural details such as network width or depth have minimal effects within a wide range. Simple equations govern the dependence of overfitting on model/dataset size and the dependence of training speed on model size. These relationships allow us to determine the optimal allocation of a fixed compute budget. Larger models are significantly more sample-efficient, such that optimally compute-efficient training involves training very large models on a relatively modest amount of data and stopping significantly before convergence.
    

[Arxiv](https://arxiv.org/pdf/2001.08361)