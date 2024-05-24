# FiDeLiS：大型语言模型在知识图谱问答中的忠实推理探索
发布时间：2024年05月22日

`知识图谱`
> FiDeLiS: Faithful Reasoning in Large Language Model for Knowledge Graph Question Answering
>
> 大型语言模型（LLMs）虽在多领域取得显著成就，但在深度和负责任推理场景中常遭遇幻觉问题。通过整合外部知识图谱（KG），这些问题得以部分缓解，但整合方式仍待深入研究。本文提出了一种名为FiDelis的检索-探索交互方法，专为基于KG的推理中间步骤设计。特别地，我们开发了Path-RAG模块，旨在从KG中提取对LLM推理至关重要的中间知识。此方法融合了LLMs的逻辑推理、常识推理与KG的拓扑结构，显著提升了知识检索的准确性。我们还引入了LLMs的演绎推理能力，作为指导推理过程的更优标准，确保推理步骤的逐步性和可推广性。演绎验证的精确性有助于及时终止推理，避免误导和无效计算。实验结果显示，我们的方法在无需额外训练、计算成本更低的情况下，在三个基准测试中均优于现有基线。
>
> https://arxiv.org/abs/2405.13873


<hr />

- 论文原文: [https://arxiv.org/abs/2405.13873](https://arxiv.org/abs/2405.13873)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886