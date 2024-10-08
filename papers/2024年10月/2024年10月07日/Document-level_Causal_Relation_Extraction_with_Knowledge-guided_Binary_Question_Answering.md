# 文档级因果关系提取：知识引导下的二进制问题解答

发布时间：2024年10月07日

`LLM应用` `信息提取`

> Document-level Causal Relation Extraction with Knowledge-guided Binary Question Answering

# 摘要

> 在信息提取领域，事件-事件因果关系提取（ECRE）旨在识别文本中事件间的因果关系。然而，现有研究面临两大难题：文档级建模缺失和因果幻觉。本文提出了一种知识引导的二元问答（KnowQA）方法，结合事件结构，分两阶段进行：事件结构构建和二元问答。我们在 MECI 和 MAVEN-ERE 数据集上，通过零-shot 和微调设置，利用大型语言模型（LLM）进行了广泛实验。结果显示，事件结构显著提升了文档级 ECRE 的性能，KnowQA 在 MECI 数据集上达到了最先进水平。此外，我们的方法不仅高效，还表现出高泛化性和低不一致性，尤其是在模型微调后具备完整事件结构时。

> As an essential task in information extraction (IE), Event-Event Causal Relation Extraction (ECRE) aims to identify and classify the causal relationships between event mentions in natural language texts. However, existing research on ECRE has highlighted two critical challenges, including the lack of document-level modeling and causal hallucinations. In this paper, we propose a Knowledge-guided binary Question Answering (KnowQA) method with event structures for ECRE, consisting of two stages: Event Structure Construction and Binary Question Answering. We conduct extensive experiments under both zero-shot and fine-tuning settings with large language models (LLMs) on the MECI and MAVEN-ERE datasets. Experimental results demonstrate the usefulness of event structures on document-level ECRE and the effectiveness of KnowQA by achieving state-of-the-art on the MECI dataset. We observe not only the effectiveness but also the high generalizability and low inconsistency of our method, particularly when with complete event structures after fine-tuning the models.

[Arxiv](https://arxiv.org/abs/2410.04752)