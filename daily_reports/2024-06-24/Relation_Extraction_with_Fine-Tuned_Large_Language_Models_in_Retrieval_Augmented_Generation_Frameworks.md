# 微调大型语言模型在检索增强生成框架下的关系抽取研究
发布时间：2024年06月20日

`RAG`
> Relation Extraction with Fine-Tuned Large Language Models in Retrieval Augmented Generation Frameworks
>
> 信息抽取（IE）是将非结构化数据转化为知识图谱等结构化格式的关键技术。其中，关系抽取（RE）任务尤为重要，它旨在揭示文本中实体间的联系。RE方法多样，涵盖了监督、无监督、弱监督及基于规则的策略。近年来，预训练语言模型（PLMs）的应用在这一领域大放异彩。在大型语言模型（LLMs）盛行的今天，通过微调这些模型，我们能够克服零-shot LLM提示型RE方法在领域适应和识别句子中隐含关系方面的局限。这些隐含关系往往难以从依赖树中直接提取，需要逻辑推理来精准捕捉。本研究聚焦于微调LLMs的效能，并探讨其在检索增强型（RAG）RE方法中的应用，旨在解决句子级别隐含关系识别的难题，尤其是在LLMs作为RAG框架中的生成器时。实证分析基于TACRED、TACRED-Revisited、Re-TACRED和SemEVAL数据集，结果显示微调LLMs（如Llama2-7B、Mistral-7B和T5（Large））显著提升了性能。特别是在SemEVAL数据集上，我们的方法在处理常见隐含关系时表现出色，刷新了该数据集的记录。此外，在TACRED、TACREV和Re-TACRED上的表现也超越了以往，展现了在多变评估环境下的卓越能力。
>
> https://arxiv.org/abs/2406.14745

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14745/x9.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.14745](https://arxiv.org/abs/2406.14745)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2