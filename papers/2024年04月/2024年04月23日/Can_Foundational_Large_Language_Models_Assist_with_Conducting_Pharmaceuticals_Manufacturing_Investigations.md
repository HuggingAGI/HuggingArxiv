# 基础性的大型语言模型是否能够帮助开展制药制造业的调查研究？

发布时间：2024年04月23日

`LLM应用` `制药制造`

> Can Foundational Large Language Models Assist with Conducting Pharmaceuticals Manufacturing Investigations?

# 摘要

> 近年来，像生成预训练变换器（GPT）和大型语言模型元人工智能（LLaMA）这样的通用大型语言模型（LLM）备受瞩目，并在自然语言处理的多个任务中展现出卓越性能。但如何有效利用这些模型以解决特定领域的应用案例，仍是一个悬而未决的问题。本研究专注于制药制造业的调查，提出通过利用企业内部的历史生产事故和偏差记录，可以有效应对和关闭新案件，或为新的生产活动降低风险。我们选取了不同产品线的真实生产偏差案例，构建了一个小而多样的数据集，用以评估三种主流LLM（GPT-3.5、GPT-4和Claude-2）在相关任务上的表现。研究重点包括：(1) LLM自动提取非结构化数据中特定信息（如案件根本原因）的能力；(2) 通过语义搜索历史记录数据库，识别相似或相关偏差的可能性。我们的研究结果显示，GPT-4和Claude-2在信息提取任务上具有高准确率，同时我们也探讨了LLM在推理与幻觉行为之间复杂相互作用的风险因素。此外，我们还发现，通过向量嵌入进行语义搜索，能够以高准确率识别具有相似缺陷类型的相似记录。文中还讨论了如何进一步提升相似记录识别的准确性。

> General purpose Large Language Models (LLM) such as the Generative Pretrained Transformer (GPT) and Large Language Model Meta AI (LLaMA) have attracted much attention in recent years. There is strong evidence that these models can perform remarkably well in various natural language processing tasks. However, how to leverage them to approach domain-specific use cases and drive value remains an open question. In this work, we focus on a specific use case, pharmaceutical manufacturing investigations, and propose that leveraging historical records of manufacturing incidents and deviations in an organization can be beneficial for addressing and closing new cases, or de-risking new manufacturing campaigns. Using a small but diverse dataset of real manufacturing deviations selected from different product lines, we evaluate and quantify the power of three general purpose LLMs (GPT-3.5, GPT-4, and Claude-2) in performing tasks related to the above goal. In particular, (1) the ability of LLMs in automating the process of extracting specific information such as root cause of a case from unstructured data, as well as (2) the possibility of identifying similar or related deviations by performing semantic search on the database of historical records are examined. While our results point to the high accuracy of GPT-4 and Claude-2 in the information extraction task, we discuss cases of complex interplay between the apparent reasoning and hallucination behavior of LLMs as a risk factor. Furthermore, we show that semantic search on vector embedding of deviation descriptions can be used to identify similar records, such as those with a similar type of defect, with a high level of accuracy. We discuss further improvements to enhance the accuracy of similar record identification.

[Arxiv](https://arxiv.org/abs/2404.15578)