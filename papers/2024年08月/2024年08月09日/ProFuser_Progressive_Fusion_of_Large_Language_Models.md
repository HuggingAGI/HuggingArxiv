# ProFuser：大型语言模型的逐步融合技术

发布时间：2024年08月09日

`LLM理论` `人工智能` `软件开发`

> ProFuser: Progressive Fusion of Large Language Models

# 摘要

> 融合多种大型语言模型 (LLM) 的能力和优势，虽然为构建更强大和多功能的模型开辟了道路，但在训练期间如何选择有优势的模型仍是一个基本挑战。现有融合方法主要依赖于教师强制模式下的交叉熵来评估模型优势，这种方法可能提供的见解有限。本文提出了一种新方法，通过结合训练和推理两种模式来优化融合过程。我们的方法不仅在训练时通过交叉熵评估模型优势，还考虑了推理输出，从而提供了更全面的评估。为有效整合这两种模式，我们设计了 ProFuser，它能逐步从推理模式过渡到训练模式。通过融合 vicuna-7b-v1.5、Llama-2-7b-chat 和 mpt-7b-8k-chat 三个模型，我们验证了 ProFuser 的有效性，并展示了其在知识、推理和安全性方面优于传统基线方法的性能提升。

> While fusing the capacities and advantages of various large language models (LLMs) offers a pathway to construct more powerful and versatile models, a fundamental challenge is to properly select advantageous model during the training. Existing fusion methods primarily focus on the training mode that uses cross entropy on ground truth in a teacher-forcing setup to measure a model's advantage, which may provide limited insight towards model advantage. In this paper, we introduce a novel approach that enhances the fusion process by incorporating both the training and inference modes. Our method evaluates model advantage not only through cross entropy during training but also by considering inference outputs, providing a more comprehensive assessment. To combine the two modes effectively, we introduce ProFuser to progressively transition from inference mode to training mode. To validate ProFuser's effectiveness, we fused three models, including vicuna-7b-v1.5, Llama-2-7b-chat, and mpt-7b-8k-chat, and demonstrated the improved performance in knowledge, reasoning, and safety compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2408.04998)