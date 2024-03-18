# [检索增强生成系统通过自动构建数据集、进行系统评估及配置布尔代理，助力提升模型性能。](https://arxiv.org/abs/2403.00820)

发布时间：2024年02月26日

`RAG`

> Retrieval Augmented Generation Systems: Automatic Dataset Creation, Evaluation and Boolean Agent Setup

> RAG技术凭借其能有效利用领域特异性和时间敏感数据提升LLM输出质量而大受欢迎。近期，这一领域正经历由简易RAG配置向高级形态转变，即从每次接收到用户输入时查询矢量数据库，转向更复杂灵活的RAG解决方案。尽管如此，当前各类具体方法仍大多停留在个案证据层面的竞争状态。本文介绍了一套严格的数据集构建与评估方法论，旨在量化比较各种RAG策略的效果差异。我们借助这套方法论构建的数据集，研发并评估了一个能够智能判断是否查询矢量数据库的布尔型RAG代理系统，此系统有助于在LLM内部知识足以解答问题时节省计算资源。目前，我们已将相关代码及生成的数据集在线公开分享。

> Retrieval Augmented Generation (RAG) systems have seen huge popularity in augmenting Large-Language Model (LLM) outputs with domain specific and time sensitive data. Very recently a shift is happening from simple RAG setups that query a vector database for additional information with every user input to more sophisticated forms of RAG. However, different concrete approaches compete on mostly anecdotal evidence at the moment. In this paper we present a rigorous dataset creation and evaluation workflow to quantitatively compare different RAG strategies. We use a dataset created this way for the development and evaluation of a boolean agent RAG setup: A system in which a LLM can decide whether to query a vector database or not, thus saving tokens on questions that can be answered with internal knowledge. We publish our code and generated dataset online.

[Arxiv](https://arxiv.org/abs/2403.00820)