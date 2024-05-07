# TED：借助内部泛化提升模型训练效率

发布时间：2024年05月06日

`LLM理论` `机器学习` `数据压缩`

> TED: Accelerate Model Training by Internal Generalization

# 摘要

> 近年来，大型语言模型在性能上取得了显著进步，但高昂的训练成本促使我们寻求更高效的数据压缩方法。我们提出了一种名为TED剪枝的新方法，它通过评估模型在剪枝后数据上的性能提升能力，同时保持对保留数据的适应性，即内部泛化（IG），来解决高剪枝比率可能导致的过拟合问题。TED采用基于内部泛化距离（IGD）的优化目标，通过比较剪枝前后IG的变化，确保与真实泛化性能的一致性，从而实现隐式正则化。该优化目标已被证实能够使模型达到泛化误差的最低界限。我们还通过掩码和泰勒近似分析了小掩码波动对IG的影响，并实现了IGD的快速估算。在连续训练动态的分析中，IGD的先前效应得到了验证，同时提出了一种逐步剪枝策略。在图像分类、自然语言理解和大型语言模型微调的实验中，TED证明了其在减少60-70%数据量的同时仍能保持性能无损。我们的代码将在论文被接受后公开。

> Large language models have demonstrated strong performance in recent years, but the high cost of training drives the need for efficient methods to compress dataset sizes. We propose TED pruning, a method that addresses the challenge of overfitting under high pruning ratios by quantifying the model's ability to improve performance on pruned data while fitting retained data, known as Internal Generalization (IG). TED uses an optimization objective based on Internal Generalization Distance (IGD), measuring changes in IG before and after pruning to align with true generalization performance and achieve implicit regularization. The IGD optimization objective was verified to allow the model to achieve the smallest upper bound on generalization error. The impact of small mask fluctuations on IG is studied through masks and Taylor approximation, and fast estimation of IGD is enabled. In analyzing continuous training dynamics, the prior effect of IGD is validated, and a progressive pruning strategy is proposed. Experiments on image classification, natural language understanding, and large language model fine-tuning show TED achieves lossless performance with 60-70\% of the data. Upon acceptance, our code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2405.03228)