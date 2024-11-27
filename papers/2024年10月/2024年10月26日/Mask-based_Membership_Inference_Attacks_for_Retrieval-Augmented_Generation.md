# 基于掩码的针对检索增强生成的成员推理攻击

发布时间：2024年10月26日

`RAG` `语言模型` `数据安全`

> Mask-based Membership Inference Attacks for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）已成为缓解大型语言模型（LLM）中幻觉现象的有效手段，其通过融入最新且特定领域的知识来实现。近来，出现了一种新趋势，即在 RAG 知识数据库中存储最新或有版权的数据，而非用于 LLM 训练。此做法引发了对成员推理攻击（MIA）的担忧，其旨在检测特定目标文档是否存于 RAG 系统的知识数据库中，以保障数据生产者的权益。尽管研究聚焦于提升 RAG 系统的可信度，但现有的针对 RAG 系统的 MIA 仍存在很大不足。以往的工作要么单纯依赖 RAG 系统的判断，要么易受其他文档或 LLM 内部知识的影响，既不可靠又缺乏可解释性。为解决这些局限，我们提出了一个基于掩码的成员推理攻击（MBA）框架。我们的框架首先运用一种掩码算法，在目标文档中有效掩码一定数量的单词。随后，用掩码文本提示 RAG 系统，并要求其预测掩码值。若目标文档在知识数据库中，掩码文本会检索出完整的目标文档作为上下文，从而实现准确的掩码预测。最后，我们采用一种简单却有效的基于阈值的方法，通过分析掩码预测的准确性来推断目标文档的成员资格。我们基于掩码的方法更具文档针对性，使 RAG 系统的生成不易受其他文档或 LLM 内部知识的干扰。大量实验表明，与现有的基线模型相比，我们的方法行之有效。

> Retrieval-Augmented Generation (RAG) has been an effective approach to mitigate hallucinations in large language models (LLMs) by incorporating up-to-date and domain-specific knowledge. Recently, there has been a trend of storing up-to-date or copyrighted data in RAG knowledge databases instead of using it for LLM training. This practice has raised concerns about Membership Inference Attacks (MIAs), which aim to detect if a specific target document is stored in the RAG system's knowledge database so as to protect the rights of data producers. While research has focused on enhancing the trustworthiness of RAG systems, existing MIAs for RAG systems remain largely insufficient. Previous work either relies solely on the RAG system's judgment or is easily influenced by other documents or the LLM's internal knowledge, which is unreliable and lacks explainability. To address these limitations, we propose a Mask-Based Membership Inference Attacks (MBA) framework. Our framework first employs a masking algorithm that effectively masks a certain number of words in the target document. The masked text is then used to prompt the RAG system, and the RAG system is required to predict the mask values. If the target document appears in the knowledge database, the masked text will retrieve the complete target document as context, allowing for accurate mask prediction. Finally, we adopt a simple yet effective threshold-based method to infer the membership of target document by analyzing the accuracy of mask prediction. Our mask-based approach is more document-specific, making the RAG system's generation less susceptible to distractions from other documents or the LLM's internal knowledge. Extensive experiments demonstrate the effectiveness of our approach compared to existing baseline models.

[Arxiv](https://arxiv.org/abs/2410.20142)