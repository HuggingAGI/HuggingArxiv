# LLM-CARD：探索大型语言模型的全景与描述

发布时间：2024年09月25日

`LLM应用` `学术研究`

> LLM-CARD: Towards a Description and Landscape of Large Language Models

# 摘要

> 随着 NLP 领域的迅猛发展，大量 LLM 应运而生，服务于多样化的 NLP 任务。然而，随着论文数量的激增，研究人员和开发者正面临信息过载的挑战。因此，开发一个能够自动从学术论文中提取并组织 LLM 关键信息的系统（LLM 模型卡片）显得尤为重要。我们利用 NER 和 RE 方法，自动提取论文中的 LLM 关键信息，如模型许可证、名称和应用，帮助研究人员高效获取信息。通过这些信息，我们为每篇论文生成一个模型卡片。在数据构建方面，我们定义了 LLM 名称、许可证和应用三个字典，处理了 106 篇论文，提取了 11,051 个句子，并最终通过手动审查，构建了包含 129 个名称与许可证关联句子和 106 个模型名称与应用关联句子的数据集。

> With the rapid growth of the Natural Language Processing (NLP) field, a vast variety of Large Language Models (LLMs) continue to emerge for diverse NLP tasks. As an increasing number of papers are presented, researchers and developers face the challenge of information overload. Thus, it is particularly important to develop a system that can automatically extract and organise key information about LLMs from academic papers (\textbf{LLM model card}). This work is to develop such a pioneer system by using Named Entity Recognition (\textbf{NER}) and Relation Extraction (\textbf{RE}) methods that automatically extract key information about large language models from the papers, helping researchers to efficiently access information about LLMs. These features include model \textit{licence}, model \textit{name}, and model \textit{application}. With these features, we can form a model card for each paper. \textbf{Data-contribution} wise, 106 academic papers were processed by defining three dictionaries - LLMs name, licence, and application. 11,051 sentences were extracted through dictionary lookup, and the dataset was constructed through manual review of the final selection of 129 sentences that have a link between the name and the licence, and 106 sentences that have a link between the model name and the application.

[Arxiv](https://arxiv.org/abs/2409.17011)