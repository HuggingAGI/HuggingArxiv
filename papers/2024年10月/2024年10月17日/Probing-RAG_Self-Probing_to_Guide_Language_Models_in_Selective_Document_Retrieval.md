# Probing-RAG：通过自我探测引导语言模型进行精准文档检索

发布时间：2024年10月17日

`RAG` `问答系统`

> Probing-RAG: Self-Probing to Guide Language Models in Selective Document Retrieval

# 摘要

> RAG 通过整合外部知识增强语言模型，但传统方法在现实场景中可能不够灵活。我们提出的 Probing-RAG 利用语言模型中间层的隐藏状态，智能判断是否需要额外检索。借助预训练的探测器，Probing-RAG 能精准捕捉模型内部认知，确保检索决策的可靠性。实验显示，Probing-RAG 在五个开放域 QA 数据集上表现优异，且减少了不必要的检索步骤。

> Retrieval-Augmented Generation (RAG) enhances language models by retrieving and incorporating relevant external knowledge. However, traditional retrieve-and-generate processes may not be optimized for real-world scenarios, where queries might require multiple retrieval steps or none at all. In this paper, we propose a Probing-RAG, which utilizes the hidden state representations from the intermediate layers of language models to adaptively determine the necessity of additional retrievals for a given query. By employing a pre-trained prober, Probing-RAG effectively captures the model's internal cognition, enabling reliable decision-making about retrieving external documents. Experimental results across five open-domain QA datasets demonstrate that Probing-RAG outperforms previous methods while reducing the number of redundant retrieval steps.

[Arxiv](https://arxiv.org/abs/2410.13339)