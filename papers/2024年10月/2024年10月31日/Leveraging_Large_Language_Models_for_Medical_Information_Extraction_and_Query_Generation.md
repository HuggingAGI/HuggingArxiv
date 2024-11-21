# 借助大型语言模型实现医学信息提取与查询生成

发布时间：2024年10月31日

`LLM应用` `临床试验`

> Leveraging Large Language Models for Medical Information Extraction and Query Generation

# 摘要

> 这篇论文介绍了一个把大型语言模型（LLMs）融入临床试验检索流程的系统，能增强患者与适配试验的匹配效果，还能保障信息隐私并接受专家监管。我们对六个用于生成查询的LLMs进行了评估，重点放在所需计算资源极少的开源且相对小型的模型上。我们的评估涵盖了两个闭源模型和四个开源模型，其中有一个是专门针对医学领域训练的，另外五个是通用模型。我们把LLM生成的查询的检索成效与医学专家创建的查询以及文献中的前沿方法做了对比。我们的研究发现，被评估的模型所实现的检索成效与专家创建的查询持平甚至更优。LLMs始终超越文献中的标准基线和其他方法。表现最佳的LLMs响应迅速，时间在1.7至8秒之间，生成的查询词数量适中（平均15至63个），适合实际应用。我们的总体研究结果表明，在医疗场景中，借助小型开源LLMs进行临床试验检索，能够平衡性能、计算效率和实际应用的可行性。

> This paper introduces a system that integrates large language models (LLMs) into the clinical trial retrieval process, enhancing the effectiveness of matching patients with eligible trials while maintaining information privacy and allowing expert oversight. We evaluate six LLMs for query generation, focusing on open-source and relatively small models that require minimal computational resources. Our evaluation includes two closed-source and four open-source models, with one specifically trained in the medical field and five general-purpose models. We compare the retrieval effectiveness achieved by LLM-generated queries against those created by medical experts and state-of-the-art methods from the literature. Our findings indicate that the evaluated models reach retrieval effectiveness on par with or greater than expert-created queries. The LLMs consistently outperform standard baselines and other approaches in the literature. The best performing LLMs exhibit fast response times, ranging from 1.7 to 8 seconds, and generate a manageable number of query terms (15-63 on average), making them suitable for practical implementation. Our overall findings suggest that leveraging small, open-source LLMs for clinical trials retrieval can balance performance, computational efficiency, and real-world applicability in medical settings.

[Arxiv](https://arxiv.org/abs/2410.23851)