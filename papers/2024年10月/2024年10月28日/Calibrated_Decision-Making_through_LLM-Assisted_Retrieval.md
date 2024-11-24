# 借助 LLM 辅助检索实现校准决策

发布时间：2024年10月28日

`RAG` `决策支持` `语言模型`

> Calibrated Decision-Making through LLM-Assisted Retrieval

# 摘要

> 近来，大型语言模型（LLMs）愈发被用于支持各类决策任务，助力人类做出明智抉择。但当LLMs自信地给出错误信息时，会致使人类做出欠佳决策。为避免LLMs在不熟悉的主题上生成错误信息并提升生成内容的精准度，先前的研究提出了检索增强生成（RAG），即参考外部文档来生成回应。然而，传统的RAG方法仅着眼于检索与输入查询最相关的文档，并非特意确保人类用户的决策得到良好校准。为突破这一局限，我们提出了一种新颖的检索方法，名为校准检索增强生成（CalibRAG），它能保证依据检索到的文档所做的决策得到良好校准。随后，我们通过实证验证，在各种数据集上，与其他基线相比，CalibRAG提升了校准性能和准确性。

> Recently, large language models (LLMs) have been increasingly used to support various decision-making tasks, assisting humans in making informed decisions. However, when LLMs confidently provide incorrect information, it can lead humans to make suboptimal decisions. To prevent LLMs from generating incorrect information on topics they are unsure of and to improve the accuracy of generated content, prior works have proposed Retrieval Augmented Generation (RAG), where external documents are referenced to generate responses. However, traditional RAG methods focus only on retrieving documents most relevant to the input query, without specifically aiming to ensure that the human user's decisions are well-calibrated. To address this limitation, we propose a novel retrieval method called Calibrated Retrieval-Augmented Generation (CalibRAG), which ensures that decisions informed by the retrieved documents are well-calibrated. Then we empirically validate that CalibRAG improves calibration performance as well as accuracy, compared to other baselines across various datasets.

[Arxiv](https://arxiv.org/abs/2411.08891)