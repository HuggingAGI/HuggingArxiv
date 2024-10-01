# 非英语环境下，针对小规模且不平衡的放射学文本数据集进行分类

发布时间：2024年09月30日

`LLM应用`

> Classification of Radiological Text in Small and Imbalanced Datasets in a Non-English Language

# 摘要

> 在处理小数据集、非英语语言、少量标记样本和不平衡类别的实际应用中，医学领域的 NLP 表现可能不尽如人意。我们评估了包括 BERT 类模型、SetFit 和 LLM 在内的一系列 NLP 模型，使用丹麦语的癫痫患者磁共振图像放射学报告数据集。结果显示，在放射学报告领域预训练的 BERT 类模型表现最佳，而 SetFit 和 LLM 则表现较差，尤其是 LLM。值得注意的是，这些模型均无法在没有监督的情况下进行准确的文本分类，但它们在数据过滤方面展现出潜力，有望减少手动标记的工作量。

> Natural language processing (NLP) in the medical domain can underperform in real-world applications involving small datasets in a non-English language with few labeled samples and imbalanced classes. There is yet no consensus on how to approach this problem. We evaluated a set of NLP models including BERT-like transformers, few-shot learning with sentence transformers (SetFit), and prompted large language models (LLM), using three datasets of radiology reports on magnetic resonance images of epilepsy patients in Danish, a low-resource language. Our results indicate that BERT-like models pretrained in the target domain of radiology reports currently offer the optimal performances for this scenario. Notably, the SetFit and LLM models underperformed compared to BERT-like models, with LLM performing the worst. Importantly, none of the models investigated was sufficiently accurate to allow for text classification without any supervision. However, they show potential for data filtering, which could reduce the amount of manual labeling required.

[Arxiv](https://arxiv.org/abs/2409.20147)