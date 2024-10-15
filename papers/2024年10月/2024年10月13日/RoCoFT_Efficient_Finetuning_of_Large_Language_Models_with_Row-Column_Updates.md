# RoCoFT：通过行-列更新实现大型语言模型的高效微调

发布时间：2024年10月13日

`LLM理论` `人工智能`

> RoCoFT: Efficient Finetuning of Large Language Models with Row-Column Updates

# 摘要

> 我们推出了 RoCoFT，一种专为大规模语言模型设计的参数高效微调方法，仅需更新 transformer 权重矩阵的少数行和列。实验结果显示，无论是 BERT 和 RoBERTa 这样的中型模型，还是 Bloom-7B、Llama2 系列这样的大型模型，RoCoFT 都能在保持或提升准确性的同时，显著节省内存和计算成本。我们还借助神经切线核理论，深入探讨了其高效性的背后原因。实验表明，RoCoFT 构建的核在数值上与全参数核相近，分类性能相当。此外，我们还通过消融研究，详细分析了不同算法选择对效果的影响，包括行和列的选择策略及最佳秩的确定。

> We propose RoCoFT, a parameter-efficient fine-tuning method for large-scale language models (LMs) based on updating only a few rows and columns of the weight matrices in transformers. Through extensive experiments with medium-size LMs like BERT and RoBERTa, and larger LMs like Bloom-7B, Llama2-7B, and Llama2-13B, we show that our method gives comparable or better accuracies than state-of-art PEFT methods while also being more memory and computation-efficient. We also study the reason behind the effectiveness of our method with tools from neural tangent kernel theory. We empirically demonstrate that our kernel, constructed using a restricted set of row and column parameters, are numerically close to the full-parameter kernel and gives comparable classification performance. Ablation studies are conducted to investigate the impact of different algorithmic choices, including the selection strategy for rows and columns as well as the optimal rank for effective implementation of our method.

[Arxiv](https://arxiv.org/abs/2410.10075)