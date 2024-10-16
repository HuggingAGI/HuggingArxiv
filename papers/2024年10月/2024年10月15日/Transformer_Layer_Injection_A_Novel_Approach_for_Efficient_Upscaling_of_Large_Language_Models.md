# Transformer 层注入：提升大型语言模型效率的创新之道

发布时间：2024年10月15日

`LLM理论` `人工智能`

> Transformer Layer Injection: A Novel Approach for Efficient Upscaling of Large Language Models

# 摘要

> 本文介绍了一种名为 Transformer 层注入 (TLI) 的创新方法，旨在高效扩展大型语言模型 (LLM)，同时降低计算成本并保持模型性能。TLI 通过减少初始损失、简化微调过程和保留模型复杂性，解决了模型扩展的难题。与传统深度扩展 (DUS) 技术相比，TLI 在每组 K 层中注入新层，确保隐藏表示流畅通过变换器块。实验结果表明，TLI 在初始化、训练步骤和任务准确性方面均优于现有方法，如专家混合 (MoE) 和 DUS，尤其在 KoBEST 和 KMCQA 任务中表现突出。TLI 不仅数据高效，而且成本效益显著，为从 10B 到 405B 参数的模型扩展提供了简单而强大的解决方案。

> In this paper, we propose Transformer Layer Injection (TLI), a novel method for efficiently upscaling large language models (LLMs) while minimizing computational costs and maintaining model performance. Model scale is a key factor in enhancing the quality of machine learning models, and TLI addresses the challenge of scaling by reducing initial loss, minimizing fine-tuning requirements, and preserving model complexity. Our approach improves upon the conventional Depth Up-Scaling (DUS) technique by injecting new layers into every set of K layers, enabling hidden representations to pass through transformer blocks with minimal disruption. We compare TLI with existing approaches, including Mixture of Experts (MoE) and DUS, and validate its efficiency through experiments on small LLMs (LLama3 1B, 3B, and 8B). Results show that TLI achieves better initialization, requires fewer training steps, and delivers superior accuracy on tasks such as KoBEST and KMCQA, with models performing effectively even without additional training. TLI is demonstrated to be both data-efficient and cost-effective, significantly outperforming existing methods. Its scalability and simplicity make it a promising solution for upscaling transformer-based models, with potential applications in scaling models from 10B to 405B parameters.

[Arxiv](https://arxiv.org/abs/2410.11654)