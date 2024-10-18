# 大规模模型训练后 Delta 参数编辑的统一视角

发布时间：2024年10月17日

`LLM理论` `机器学习` `人工智能`

> A Unified View of Delta Parameter Editing in Post-Trained Large-Scale Models

# 摘要

> Post-training 是调整大规模预训练模型以适应各种任务的关键方法，其效果通过 delta 参数（post-trained 与 pre-trained 参数的差异）完全体现。尽管已有研究通过剪枝、量化等操作探索了 delta 参数的特性，但缺乏系统性框架。本文提出基于损失函数 Riemann 和近似的新视角，将现有方法分为竞争性、下降性和改进性三类，解释了它们如何影响模型性能。实验证实了理论发现，并扩展了现有技术如 DARE 和 BitDelta，提升了 delta 参数编辑的适用性和有效性。

> Post-training has emerged as a crucial paradigm for adapting large-scale pre-trained models to various tasks, whose effects are fully reflected by delta parameters (i.e., the disparity between post-trained and pre-trained parameters). While numerous studies have explored delta parameter properties via operations like pruning, quantization, low-rank approximation, and extrapolation, a unified framework for systematically examining these characteristics has been lacking. In this paper, we propose a novel perspective based on Riemann sum approximation of the loss function to elucidate delta parameter editing operations. Our analysis categorizes existing methods into three classes based on their post-editing performance: competitive, decreased, and improved, explaining how they are expressed by the Riemann sum approximation term and how they alter the model performance. Extensive experiments on both visual and language models, including ViT, LLaMA 3, Qwen 2, and Mistral, corroborate our theoretical findings. Furthermore, we introduce extensions to existing techniques like DARE and BitDelta, highlighting their limitations in leveraging the properties of delta parameters and reorganizing them into general expressions to enhance the applicability and effectiveness of delta parameter editing in post-trained models.

[Arxiv](https://arxiv.org/abs/2410.13841)