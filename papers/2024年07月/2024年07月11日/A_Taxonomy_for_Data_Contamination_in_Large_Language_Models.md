# 大型语言模型数据污染的分类体系

发布时间：2024年07月11日

`LLM理论` `人工智能` `数据安全`

> A Taxonomy for Data Contamination in Large Language Models

# 摘要

> 大型语言模型在广泛网络语料库上的预训练表现出色，但数据污染问题日益凸显。评估数据集可能被预训练语料库包含，导致性能虚高。去污染虽是解决方案，但污染物可能变形逃逸检测。我们分类了预训练中的污染类型，并评估其风险。此外，我们深入分析了污染对摘要和问答任务的影响，揭示了污染如何左右评估结果。

> Large language models pretrained on extensive web corpora demonstrate remarkable performance across a wide range of downstream tasks. However, a growing concern is data contamination, where evaluation datasets may be contained in the pretraining corpus, inflating model performance. Decontamination, the process of detecting and removing such data, is a potential solution; yet these contaminants may originate from altered versions of the test set, evading detection during decontamination. How different types of contamination impact the performance of language models on downstream tasks is not fully understood. We present a taxonomy that categorizes the various types of contamination encountered by LLMs during the pretraining phase and identify which types pose the highest risk. We analyze the impact of contamination on two key NLP tasks -- summarization and question answering -- revealing how different types of contamination influence task performance during evaluation.

[Arxiv](https://arxiv.org/abs/2407.08716)