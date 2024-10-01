# 组合解码器助力通用医学图像表示学习

发布时间：2024年09月29日

`LLM应用` `计算机视觉`

> Universal Medical Image Representation Learning with Compositional Decoders

# 摘要

> 视觉-语言模型虽推动了通用模型的发展，但在医学影像中的应用仍受限于特定功能需求和数据匮乏。现有通用模型常设计有任务特定的分支和头部，限制了共享特征空间和模型灵活性。为此，我们开发了UniMed，一种分解-组合的通用医学影像范式，支持多层次任务。我们提出分解解码器，能根据输入队列预测像素和语义输出；并引入组合解码器，统一输入输出空间，将任务注释标准化为离散令牌。这种设计使模型能灵活组合任务并相互受益。此外，我们的联合表示学习策略利用大量未标记数据和无监督损失，实现高效一阶段预训练，提升性能。实验显示，UniMed在八个数据集上达到最先进性能，并具备强大的零-shot和100-shot迁移能力。论文接受后，我们将发布代码和训练模型。

> Visual-language models have advanced the development of universal models, yet their application in medical imaging remains constrained by specific functional requirements and the limited data. Current general-purpose models are typically designed with task-specific branches and heads, which restricts the shared feature space and the flexibility of model. To address these challenges, we have developed a decomposed-composed universal medical imaging paradigm (UniMed) that supports tasks at all levels. To this end, we first propose a decomposed decoder that can predict two types of outputs -- pixel and semantic, based on a defined input queue. Additionally, we introduce a composed decoder that unifies the input and output spaces and standardizes task annotations across different levels into a discrete token format. The coupled design of these two components enables the model to flexibly combine tasks and mutual benefits. Moreover, our joint representation learning strategy skilfully leverages large amounts of unlabeled data and unsupervised loss, achieving efficient one-stage pretraining for more robust performance. Experimental results show that UniMed achieves state-of-the-art performance on eight datasets across all three tasks and exhibits strong zero-shot and 100-shot transferability. We will release the code and trained models upon the paper's acceptance.

[Arxiv](https://arxiv.org/abs/2409.19890)