# CRE-LLM：一个针对特定领域的中文关系抽取框架，融合了经过精细调整的大型语言模型。

发布时间：2024年04月28日

`LLM应用` `中文关系抽取`

> CRE-LLM: A Domain-Specific Chinese Relation Extraction Framework with Fine-tuned Large Language Model

# 摘要

> 领域定制的中文关系抽取（DSCRE）致力于从专业中文文本中提取实体间的关系。尽管预训练语言模型（PLMs）尤其是大型语言模型（LLMs）技术近年来突飞猛进，DSCRE在网络结构设计、意识提升和微调成本上仍面临重大挑战。鉴于LLMs在自然语言处理领域的卓越成就，我们设计了一种创新框架CRE-LLM。该框架依托于对开源LLMs如Llama-2、ChatGLM2和Baichuan2进行微调，通过精心构建的提示和指令驱动的微调，显著提升了模型的逻辑理解和生成能力。CRE-LLM能够直接从文本数据中抽取实体间的关系，优化了传统的关系抽取方法。为了验证框架的效能，我们在两个专业的CRE数据集FinRE和SanWen上进行了深入的实验。实验结果显示，CRE-LLM在性能上大幅领先，尤其在FinRE数据集上达到了行业领先水平。本文提出了一种创新的DSCRE任务处理方法，通过结合LLMs与三元组来处理更为复杂的语义关系。我们的相关代码已对公众开放。

> Domain-Specific Chinese Relation Extraction (DSCRE) aims to extract relations between entities from domain-specific Chinese text. Despite the rapid development of PLMs in recent years, especially LLMs, DSCRE still faces three core challenges: complex network structure design, poor awareness, and high consumption of fine-tuning. Given the impressive performance of large language models (LLMs) in natural language processing, we propose a new framework called CRE-LLM. This framework is based on fine-tuning open-source LLMs, such as Llama-2, ChatGLM2, and Baichuan2. CRE-LLM enhances the logic-awareness and generative capabilities of the model by constructing an appropriate prompt and utilizing open-source LLMs for instruction-supervised fine-tuning. And then it directly extracts the relations of the given entities in the input textual data, which improving the CRE approach. To demonstrate the effectiveness of the proposed framework, we conducted extensive experiments on two domain-specific CRE datasets, FinRE and SanWen. The experimental results show that CRE-LLM is significantly superior and robust, achieving state-of-the-art (SOTA) performance on the FinRE dataset. This paper introduces a novel approach to domain-specific relation extraction (DSCRE) tasks that are semantically more complex by combining LLMs with triples. Our code is publicly available.

[Arxiv](https://arxiv.org/abs/2404.18085)