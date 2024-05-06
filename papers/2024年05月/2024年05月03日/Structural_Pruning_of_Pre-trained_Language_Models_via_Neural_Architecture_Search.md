# 利用神经架构搜索技术对预训练的语言模型进行结构化精简。

发布时间：2024年05月03日

`LLM应用` `模型优化`

> Structural Pruning of Pre-trained Language Models via Neural Architecture Search

# 摘要

> 以 BERT 和 RoBERTa 为代表的预训练语言模型（PLM）在经过标记数据微调后，成为自然语言理解任务的行业标杆。但这些模型的庞大体量对于实际应用中的推理部署构成了挑战，主要体现在对 GPU 内存的巨大需求和较长的推理延迟。本研究通过神经架构搜索（NAS）进行结构性剪枝，旨在寻找在模型大小、延迟和泛化性能之间取得最佳平衡的网络子部分。此外，我们还展示了如何应用最新发展的两阶段权重共享 NAS 方法来加快搜索进程。与传统的固定阈值剪枝法不同，本研究提出了一种多目标优化策略，以识别出帕累托最优的子网络集合，从而实现更加灵活和自动化的模型压缩过程。

> Pre-trained language models (PLM), for example BERT or RoBERTa, mark the state-of-the-art for natural language understanding task when fine-tuned on labeled data. However, their large size poses challenges in deploying them for inference in real-world applications, due to significant GPU memory requirements and high inference latency. This paper explores neural architecture search (NAS) for structural pruning to find sub-parts of the fine-tuned network that optimally trade-off efficiency, for example in terms of model size or latency, and generalization performance. We also show how we can utilize more recently developed two-stage weight-sharing NAS approaches in this setting to accelerate the search process. Unlike traditional pruning methods with fixed thresholds, we propose to adopt a multi-objective approach that identifies the Pareto optimal set of sub-networks, allowing for a more flexible and automated compression process.

[Arxiv](https://arxiv.org/abs/2405.02267)