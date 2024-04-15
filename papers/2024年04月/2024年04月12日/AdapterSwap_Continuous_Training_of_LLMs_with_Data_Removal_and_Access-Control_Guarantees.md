# AdapterSwap 技术能够在确保数据安全删除和访问受限的前提下，对大型语言模型（LLM）实施持续的训练与优化。

发布时间：2024年04月12日

`LLM理论` `机器学习` `数据管理`

> AdapterSwap: Continuous Training of LLMs with Data Removal and Access-Control Guarantees

# 摘要

> 大型语言模型（LLMs）正日益擅长利用静态预训练资料库中的信息，来完成那些需要丰富知识的复杂任务。本文聚焦于LLMs在应对不断演变的数据需求上的角色。比如，定期更新的数据批次、依据用户权限管理的数据子集，以及对文档动态删除的需求，同时确保已删除内容的知识不会被再次调用。我们的目标是在新数据到来时，确保模型依然保留旧信息。为此，我们提出了AdapterSwap——一种训练与推理的新方案，它能将知识整理成一系列低秩适配器，并在推理时动态地进行组合。实验证明，AdapterSwap不仅支持高效的持续学习，还让机构对数据的访问与删除拥有了更精细的控制权。

> Large language models (LLMs) are increasingly capable of completing knowledge intensive tasks by recalling information from a static pretraining corpus. Here we are concerned with LLMs in the context of evolving data requirements. For instance: batches of new data that are introduced periodically; subsets of data with user-based access controls; or requirements on dynamic removal of documents with guarantees that associated knowledge cannot be recalled. We wish to satisfy these requirements while at the same time ensuring a model does not forget old information when new data becomes available. To address these issues, we introduce AdapterSwap, a training and inference scheme that organizes knowledge from a data collection into a set of low-rank adapters, which are dynamically composed during inference. Our experiments demonstrate AdapterSwap's ability to support efficient continual learning, while also enabling organizations to have fine-grained control over data access and deletion.

[Arxiv](https://arxiv.org/abs/2404.08417)