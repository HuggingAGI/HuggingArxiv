# 激发多模态语言模型似然组合的无限潜能

发布时间：2024年09月30日

`LLM应用` `计算机视觉` `人工智能`

> Unleashing the Potentials of Likelihood Composition for Multi-modal Language Models

# 摘要

> 在大型语言模型（LLM）和多模态语言模型（MLM）不断涌现的时代，模型融合显得尤为重要。我们提出了一种名为“似然组合”的后验框架，旨在无缝融合异构模型。其核心思想是在多选视觉问答任务中，综合多个模型的似然分布。这里的“似然”即候选答案的对数概率。我们引入了四种基本操作：去偏、突出、多数投票和集成。通过这些元素的组合，我们开发了“混合组合”方法。实验证明，“混合组合”在多个VQA数据集和MLM上的表现优于传统方法。这一框架不仅提供了融合异构模型的新视角，还为未来的探索开辟了新的可能性。

> Model fusing has always been an important topic, especially in an era where large language models (LLM) and multi-modal language models (MLM) with different architectures, parameter sizes and training pipelines, are being created all the time. In this work, we propose a post-hoc framework, aiming at fusing heterogeneous models off-the-shell, which we call \textit{likelihood composition}, and the basic idea is to compose multiple models' likelihood distribution when doing a multi-choice visual-question-answering task. Here the core concept, \textit{likelihood}, is actually the log-probability of the candidate answer. In \textit{likelihood composition}, we introduce some basic operations: \textit{debias}, \textit{highlight}, \textit{majority-vote} and \textit{ensemble}. By combining (composing) these basic elements, we get the mixed composition methods: \textit{mix-composition}. Through conducting comprehensive experiments on 9 VQA datasets and 10 MLMs, we prove the effectiveness of \textit{mix-composition} compared with simple \textit{ensemble} or \textit{majority-vote} methods. In this framework, people can propose new basic composition methods and combine them to get the new mixed composition methods. We hope our proposed \textit{likelihood composition} can provide a new perspective of fusing heterogeneous models and inspire the exploration under this framework.

[Arxiv](https://arxiv.org/abs/2410.00363)