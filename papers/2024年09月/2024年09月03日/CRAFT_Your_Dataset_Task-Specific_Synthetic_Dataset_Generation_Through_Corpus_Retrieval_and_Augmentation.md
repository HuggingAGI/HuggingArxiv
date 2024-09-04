# CRAFT 你的数据集：利用语料库检索与增强技术，定制任务专属的合成数据集

发布时间：2024年09月03日

`LLM应用` `生物学`

> CRAFT Your Dataset: Task-Specific Synthetic Dataset Generation Through Corpus Retrieval and Augmentation

# 摘要

> 构建高质量专用任务数据集既耗时又资源密集，常需专业知识。我们提出的 CRAFT 方法，能根据少量用户示例生成合成数据集。利用大规模网络爬取语料库和相似性检索，我们找到相关人工文档，再由指令调整的 LLM 将其转化为定制任务样本，用于微调。CRAFT 能高效为生物学、医学、常识问答及摘要等任务生成大规模训练数据集。实验表明，CRAFT 模型在问答任务上表现优异，摘要模型更胜人工精选数据训练的模型 46 分。

> Building high-quality datasets for specialized tasks is a time-consuming and resource-intensive process that often requires specialized domain knowledge. We propose Corpus Retrieval and Augmentation for Fine-Tuning (CRAFT), a method for generating synthetic datasets, given a small number of user-written few-shots that demonstrate the task to be performed. Given the few-shot examples, we use large-scale public web-crawled corpora and similarity-based document retrieval to find other relevant human-written documents. Lastly, instruction-tuned large language models (LLMs) augment the retrieved documents into custom-formatted task samples, which then can be used for fine-tuning. We demonstrate that CRAFT can efficiently generate large-scale task-specific training datasets for four diverse tasks: biology question-answering (QA), medicine QA and commonsense QA as well as summarization. Our experiments show that CRAFT-based models outperform or achieve comparable performance to general LLMs for QA tasks, while CRAFT-based summarization models outperform models trained on human-curated data by 46 preference points.

[Arxiv](https://arxiv.org/abs/2409.02098)