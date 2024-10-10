# MatMamba：一款如俄罗斯套娃般精巧的状态空间模型

发布时间：2024年10月09日

`LLM理论` `人工智能` `计算机视觉`

> MatMamba: A Matryoshka State Space Model

# 摘要

> Mamba2 等状态空间模型（SSM）是 Transformer 的潜力替代品，尤其在长上下文处理上，训练和推理速度更快。最新研究如 Matryoshka 表示学习，通过 MatFormer 等应用，展示了如何在单一弹性模型中嵌套多层次子模型。我们提出的 MatMamba 结合了 Matryoshka 风格与 Mamba2，通过嵌套维度实现联合训练与自适应推理，适用于各种模型大小的灵活部署。训练一个大型 MatMamba 模型，即可免费获得多个小嵌套模型，性能不减反增。在 35M 至 1.4B 参数范围内，MatMamba 在 ImageNet 和 FineWeb 上的表现与 Transformer 相当，且推理更高效。这使得 MatMamba 成为弹性部署大规模模型的实用选择。代码与模型已开源，详见 \url{https://github.com/ScaledFoundations/MatMamba}。

> State Space Models (SSMs) like Mamba2 are a promising alternative to Transformers, with faster theoretical training and inference times -- especially for long context lengths. Recent work on Matryoshka Representation Learning -- and its application to Transformer backbones in works like MatFormer -- showed how to introduce nested granularities of smaller submodels in one universal elastic model. In this work, we present MatMamba: a state space model which combines Matryoshka-style learning with Mamba2, by modifying the block to contain nested dimensions to enable joint training and adaptive inference. MatMamba allows for efficient and adaptive deployment across various model sizes. We train a single large MatMamba model and are able to get a number of smaller nested models for free -- while maintaining or improving upon the performance of a baseline smaller model trained from scratch. We train language and image models at a variety of parameter sizes from 35M to 1.4B. Our results on ImageNet and FineWeb show that MatMamba models scale comparably to Transformers, while having more efficient inference characteristics. This makes MatMamba a practically viable option for deploying large-scale models in an elastic way based on the available inference compute. Code and models are open sourced at \url{https://github.com/ScaledFoundations/MatMamba}

[Arxiv](https://arxiv.org/abs/2410.06718)