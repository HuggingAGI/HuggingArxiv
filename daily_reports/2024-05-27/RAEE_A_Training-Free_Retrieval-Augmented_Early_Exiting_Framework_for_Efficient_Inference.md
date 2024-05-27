# RAEE：一种无需额外训练的检索增强框架，通过早期退出策略优化推理效率
发布时间：2024年05月24日

`RAG`
> RAEE: A Training-Free Retrieval-Augmented Early Exiting Framework for Efficient Inference
>
> 大型语言模型的推理部署因其高计算成本而充满挑战。早期退出策略通过动态减少推理层数来加速这一过程。然而，现有的早期退出方法依赖于内部分类器的训练，这不仅设计复杂，而且训练成本高昂。为此，本文提出了RAEE，一种无需额外训练的检索增强型早期退出框架，旨在提升推理效率。首先，我们将早期退出问题转化为一个分布预测问题，利用类似数据的已有信息来近似这一分布。接着，详细阐述了如何收集这些信息以构建检索数据库。最后，RAEE利用这些检索到的信息，引导模型在预测的层级提前退出，从而加速推理过程。实验证明，RAEE不仅大幅提升了推理速度，还在8个分类任务上达到了顶尖的零-shot性能。
>
> https://arxiv.org/abs/2405.15198

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15198/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15198/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15198/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.15198](https://arxiv.org/abs/2405.15198)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886