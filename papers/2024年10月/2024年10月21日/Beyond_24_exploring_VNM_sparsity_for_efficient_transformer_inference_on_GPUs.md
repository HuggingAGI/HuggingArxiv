# 超越 2:4：探索 V:N:M 稀疏性，提升 GPU 上 Transformer 推理效率

发布时间：2024年10月21日

`LLM理论` `人工智能` `计算机视觉`

> Beyond 2:4: exploring V:N:M sparsity for efficient transformer inference on GPUs

# 摘要

> 目前，2:4 稀疏性是唯一能通过 GPU 稀疏张量核心加速的模式。然而，这种模式实际加速有限（$\leq 1.3$），且需固定稀疏比率，其他比率如 4:8、8:16 或超过 50% 稀疏性则无加速效果。近期研究显示，V:N:M 稀疏性有望克服这些局限。但关于其对视觉 Transformer 和 LLM 等广泛模型的准确性影响，仍未深入研究。此外，如何选择合适的 V 和 M 值等具体问题也未解决。本研究全面探讨了 V:N:M 稀疏性在视觉模型和 LLM 中的应用，提出三种方法提升其适用性和准确性：启发式 V 和 M 选择、V:N:M 特定通道排列及三阶段 LoRA 训练技术。实验表明，DeiT-small 在 64:2:5 稀疏性下无损准确，DeiT-base 在 64:2:8 稀疏性下仍保持准确。微调的 LLama2-7B 在 64:2:5 稀疏性下，下游任务表现优于无需训练的 2:4 稀疏方案。更重要的是，V:N:M 稀疏 Transformer 提供了更广泛的加速-准确性权衡。总体而言，我们的研究使 V:N:M 稀疏性成为成本敏感推理场景中 Transformer 的有效加速方案。

> To date, 2:4 sparsity has stood as the only sparse pattern that can be accelerated using sparse tensor cores on GPUs. In practice, 2:4 sparsity often possesses low actual speedups ($\leq 1.3$) and requires fixed sparse ratios, meaning that other ratios, such as 4:8, 8:16, or those exceeding 50% sparsity, do not incur any speedups on GPUs. Recent studies suggest that V:N:M sparsity is promising in addressing these limitations of 2:4 sparsity. However, regarding accuracy, the effects of V:N:M sparsity on broader Transformer models, such as vision Transformers and large language models (LLMs), are largely unexamined. Moreover, Some specific issues related to V:N:M sparsity, such as how to select appropriate V and M values, remain unresolved. In this study, we thoroughly investigate the application of V:N:M sparsity in vision models and LLMs across multiple tasks, from pertaining to downstream tasks. We propose three key approaches to enhance the applicability and accuracy of V:N:M-sparse Transformers, including heuristic V and M selection, V:N:M-specific channel permutation, and three-staged LoRA training techniques. Experimental results show that, with our methods, the DeiT-small achieves lossless accuracy at 64:2:5 sparsity, while the DeiT-base maintains accuracy even at 64:2:8 sparsity. In addition, the fine-tuned LLama2-7B at 64:2:5 sparsity performs comparably or better than training-free 2:4 sparse alternatives on downstream tasks. More importantly, V:N:M-sparse Transformers offer a wider range of speedup-accuracy trade-offs compared to 2:4 sparsity. Overall, our exploration largely facilitates the V:N:M sparsity to act as a truly effective acceleration solution for Transformers in cost-sensitive inference scenarios.

[Arxiv](https://arxiv.org/abs/2410.16135)