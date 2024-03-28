# 致力于普通法系环境下的低资源法院判决摘要生成，本研究关注在有限数据条件下，如何高效地为法院判决文档创建精炼、准确的摘要。

发布时间：2024年03月07日

`LLM应用`

> Low-Resource Court Judgment Summarization for Common Law Systems

# 摘要

> 面对普通法法院需参考类似判例作出裁决的实际需求，我们构建了首个针对多司法辖区普通法判决文档的摘要数据集——CLSum。不同于以往仅关注某一民法或特定地区判决的研究，CLSum填补了在资源稀缺情况下跨多个司法辖区有效总结判例的空白。本研究率先运用大型语言模型（LLMs）进行数据增强、摘要生成及评估，其中设计了一种融合法律知识的LLM增强数据方法，并创新性地提出了基于LLM的法律知识强化评估标准，以确保生成判决摘要的质量。实验证明，在少量样本甚至零样本条件下，基于LLM的摘要方法表现出色。我们还通过深入对比实验，找出了可显著提升摘要效果的关键模型结构与参数设置。

> Common law courts need to refer to similar precedents' judgments to inform their current decisions. Generating high-quality summaries of court judgment documents can facilitate legal practitioners to efficiently review previous cases and assist the general public in accessing how the courts operate and how the law is applied. Previous court judgment summarization research focuses on civil law or a particular jurisdiction's judgments. However, judges can refer to the judgments from all common law jurisdictions. Current summarization datasets are insufficient to satisfy the demands of summarizing precedents across multiple jurisdictions, especially when labeled data are scarce for many jurisdictions. To address the lack of datasets, we present CLSum, the first dataset for summarizing multi-jurisdictional common law court judgment documents. Besides, this is the first court judgment summarization work adopting large language models (LLMs) in data augmentation, summary generation, and evaluation. Specifically, we design an LLM-based data augmentation method incorporating legal knowledge. We also propose a legal knowledge enhanced evaluation metric based on LLM to assess the quality of generated judgment summaries. Our experimental results verify that the LLM-based summarization methods can perform well in the few-shot and zero-shot settings. Our LLM-based data augmentation method can mitigate the impact of low data resources. Furthermore, we carry out comprehensive comparative experiments to find essential model components and settings that are capable of enhancing summarization performance.

[Arxiv](https://arxiv.org/abs/2403.04454)