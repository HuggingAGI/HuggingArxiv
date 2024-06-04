# EMERGE：融合 RAG 技术，优化多模态电子健康记录的预测模型构建
发布时间：2024年05月27日

`RAG`
> EMERGE: Integrating RAG for Improved Multimodal EHR Predictive Modeling
>
> 多模态电子健康记录（EHR）数据的整合显著提升了临床预测能力。然而，现有模型在使用临床笔记和多变量时间序列EHR数据时，往往缺乏精确临床任务所需的医学背景。为此，我们提出了EMERGE框架，这是一个基于检索增强生成（RAG）的先进系统，旨在提升多模态EHR的预测能力。EMERGE通过大型语言模型（LLMs）从时间序列数据和临床笔记中提取实体，并与专业PrimeKG对齐，确保了医学知识的一致性。此外，我们不仅关注三元组关系，还包含了实体的详细定义和描述，以丰富语义信息。提取的知识用于生成患者健康状况的任务相关摘要，这些摘要通过自适应多模态融合网络与其他模态数据融合。在MIMIC-III和MIMIC-IV数据集上的实验表明，EMERGE在院内死亡率和30天再入院预测任务中表现出色，超越了传统模型。详细的消融研究和分析证实了EMERGE框架中每个模块的有效性及其对数据稀疏性的强鲁棒性。EMERGE不仅提升了多模态EHR数据的应用，还弥合了复杂医学背景与临床预测之间的差距，为精准医疗提供了有力支持。
>
> https://arxiv.org/abs/2406.00036

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00036/x17.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00036](https://arxiv.org/abs/2406.00036)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886