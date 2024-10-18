# LoLDU：利用下-对角-上分解技术，实现低秩适应，从而进行参数高效的微调。

发布时间：2024年10月17日

`LLM理论` `机器学习` `计算资源优化`

> LoLDU: Low-Rank Adaptation via Lower-Diag-Upper Decomposition for Parameter-Efficient Fine-Tuning

# 摘要

> 随着模型规模的迅猛增长，微调所需的计算资源也水涨船高。现有的低秩适应（LoRA）方法虽试图解决全量微调中的参数爆炸问题，但其随机初始化和低秩矩阵优化策略可能导致收敛不佳和精度损失。为此，我们推出了 LoLDU，一种参数高效的微调（PEFT）新方法，其训练参数比常规 PEFT 方法减少了惊人的 2600 倍，性能却毫不逊色。LoLDU 巧妙运用下三角-对角-上三角分解（LDU），加速收敛并确保正交性，同时重点优化对角矩阵以实现精准的缩放变换。据我们所知，LoLDU 在 PEFT 领域堪称参数最精简。我们在多个数据集和模型类型上进行了详尽实验，全面剖析了其性能。开源代码现已上线，欢迎访问 \href{https://github.com/SKDDJ/LoLDU}{https://github.com/SKDDJ/LoLDU} 一探究竟。

> The rapid growth of model scale has necessitated substantial computational resources for fine-tuning. Existing approach such as Low-Rank Adaptation (LoRA) has sought to address the problem of handling the large updated parameters in full fine-tuning. However, LoRA utilize random initialization and optimization of low-rank matrices to approximate updated weights, which can result in suboptimal convergence and an accuracy gap compared to full fine-tuning. To address these issues, we propose LoLDU, a Parameter-Efficient Fine-Tuning (PEFT) approach that significantly reduces trainable parameters by 2600 times compared to regular PEFT methods while maintaining comparable performance. LoLDU leverages Lower-Diag-Upper Decomposition (LDU) to initialize low-rank matrices for faster convergence and orthogonality. We focus on optimizing the diagonal matrix for scaling transformations. To the best of our knowledge, LoLDU has the fewest parameters among all PEFT approaches. We conducted extensive experiments across 4 instruction-following datasets, 6 natural language understanding (NLU) datasets, 8 image classification datasets, and image generation datasets with multiple model types (LLaMA2, RoBERTa, ViT, and Stable Diffusion), providing a comprehensive and detailed analysis. Our open-source code can be accessed at \href{https://github.com/SKDDJ/LoLDU}{https://github.com/SKDDJ/LoLDU}.

[Arxiv](https://arxiv.org/abs/2410.13618)