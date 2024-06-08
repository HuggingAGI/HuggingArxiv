# 借助去焦注意力网络，探索一维因果视觉表示的学习之道

发布时间：2024年06月06日

`RAG

理由：这篇论文主要探讨了在多模态模型中，如何通过改进1D因果建模来处理图像数据，解决现有模型中存在的“过度聚焦”问题。论文提出了一种新的网络结构——去焦注意力网络，并通过实验验证了其在全局感知、密集预测及多模态理解等任务中的有效性。这与RAG（Retrieval-Augmented Generation）分类相关，因为RAG模型通常涉及如何有效地结合和处理不同模态的数据，以提高模型的理解和生成能力。虽然论文没有直接提到生成任务，但其对多模态数据处理的研究与RAG模型的核心思想相契合。` `计算机视觉` `多模态学习`

> Learning 1D Causal Visual Representation with De-focus Attention Networks

# 摘要

> 模态差异促使视觉与语言模型采用异构架构，图像依赖2D非因果建模，文本则采用1D因果建模，这为构建统一多模态模型带来挑战。本文探索了利用1D因果建模处理图像的可能性，并指出当前1D因果视觉模型存在“过度聚焦”问题，即注意力过分集中于少数视觉令牌，影响了模型提取多样视觉特征及优化梯度的能力。为此，我们提出去焦注意力网络，通过可学习的带通滤波器生成多样化的注意力模式。在训练中，我们采用高计划性drop路径率，并引入针对全局理解任务的全局池化特征的辅助损失，以鼓励模型关注更广泛的令牌，并优化网络。大量实验证明，我们的方法在全局感知、密集预测及多模态理解等任务中，1D因果视觉表示能与2D非因果表示媲美。相关代码已发布于https://github.com/OpenGVLab/De-focus-Attention-Networks。

> Modality differences have led to the development of heterogeneous architectures for vision and language models. While images typically require 2D non-causal modeling, texts utilize 1D causal modeling. This distinction poses significant challenges in constructing unified multi-modal models. This paper explores the feasibility of representing images using 1D causal modeling. We identify an "over-focus" issue in existing 1D causal vision models, where attention overly concentrates on a small proportion of visual tokens. The issue of "over-focus" hinders the model's ability to extract diverse visual features and to receive effective gradients for optimization. To address this, we propose De-focus Attention Networks, which employ learnable bandpass filters to create varied attention patterns. During training, large and scheduled drop path rates, and an auxiliary loss on globally pooled features for global understanding tasks are introduced. These two strategies encourage the model to attend to a broader range of tokens and enhance network optimization. Extensive experiments validate the efficacy of our approach, demonstrating that 1D causal visual representation can perform comparably to 2D non-causal representation in tasks such as global perception, dense prediction, and multi-modal understanding. Code is released at https://github.com/OpenGVLab/De-focus-Attention-Networks.

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x1.png)

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x2.png)

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x3.png)

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x4.png)

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x5.png)

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x6.png)

![借助去焦注意力网络，探索一维因果视觉表示的学习之道](../../../paper_images/2406.04342/x7.png)

[Arxiv](https://arxiv.org/abs/2406.04342)