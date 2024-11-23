# 利用大型语言模型生成合成数据，服务于个性化的社区问答

发布时间：2024年10月29日

`LLM应用` `信息检索` `个性化问答`

> Synthetic Data Generation with Large Language Models for Personalized Community Question Answering

# 摘要

> 在信息检索（IR）领域，个性化一直是研究社区长期探讨的主题。然而，目前仍缺少用于大规模评估个性化 IR 的数据集，主要原因在于收集和整理高质量的用户相关信息需要耗费大量成本与时间。而且，创建个性化 IR（PIR）任务的数据集会受隐私问题以及对准确用户相关数据的需求影响，这些数据通常无法公开获取。近来，研究人员开始探索利用大型语言模型（LLMs）生成合成数据集，这为低资源任务生成数据提供了一种可能的解决方案。本文研究了大型语言模型（LLMs）为个性化社区问答任务生成合成文档以训练 IR 系统的潜力。为探究在 LLM 生成的数据上微调的 IR 模型的有效性，我们引入了一个新的数据集，名为 Sy-SE-PQA。我们基于现有的 SE-PQA 数据集构建了 Sy-SE-PQA，该数据集包含在热门的 StackExchange 社区发布的问题和答案。从 SE-PQA 中的问题出发，我们运用不同的提示技术和 LLMs 生成合成答案。我们的发现表明，LLMs 在生成契合用户需求的数据方面潜力巨大。合成数据能够替代人工编写的训练数据，即便生成的数据可能存在错误信息。

> Personalization in Information Retrieval (IR) is a topic studied by the research community since a long time. However, there is still a lack of datasets to conduct large-scale evaluations of personalized IR; this is mainly due to the fact that collecting and curating high-quality user-related information requires significant costs and time investment. Furthermore, the creation of datasets for Personalized IR (PIR) tasks is affected by both privacy concerns and the need for accurate user-related data, which are often not publicly available. Recently, researchers have started to explore the use of Large Language Models (LLMs) to generate synthetic datasets, which is a possible solution to generate data for low-resource tasks. In this paper, we investigate the potential of Large Language Models (LLMs) for generating synthetic documents to train an IR system for a Personalized Community Question Answering task. To study the effectiveness of IR models fine-tuned on LLM-generated data, we introduce a new dataset, named Sy-SE-PQA. We build Sy-SE-PQA based on an existing dataset, SE-PQA, which consists of questions and answers posted on the popular StackExchange communities. Starting from questions in SE-PQA, we generate synthetic answers using different prompt techniques and LLMs. Our findings suggest that LLMs have high potential in generating data tailored to users' needs. The synthetic data can replace human-written training data, even if the generated data may contain incorrect information.

[Arxiv](https://arxiv.org/abs/2410.22182)