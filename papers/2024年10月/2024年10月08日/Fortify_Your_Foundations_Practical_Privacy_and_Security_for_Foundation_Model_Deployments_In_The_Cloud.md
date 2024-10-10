# 夯实基础：云端部署中的隐私与安全实践

发布时间：2024年10月08日

`LLM应用` `人工智能`

> Fortify Your Foundations: Practical Privacy and Security for Foundation Model Deployments In The Cloud

# 摘要

> 基础模型 (FMs) 在自然语言处理等领域表现出色，并广泛应用于各个学科。尽管这些模型通常在大型公共数据集上训练，但它们常被微调或集成到依赖私有数据的 RAG 系统中，这增加了知识产权被盗的风险。此外，多模态 FMs 还可能泄露敏感信息。我们探讨了 FM 的威胁模型，并评估了多种防护方法，如基于机器学习的技术和可信执行环境 (TEEs)。研究表明，TEEs 在安全、可用性和性能之间实现了有效平衡。我们提出了一种解决方案，在 \intel\ SGX 和 \intel\ TDX 环境下，Llama2 7B 和 13B 推理管道的开销不到 10\%。我们还分享了配置文件和实施经验。据我们所知，这是首次展示 TEEs 在保护 FMs 方面的实际应用。

> Foundation Models (FMs) display exceptional performance in tasks such as natural language processing and are being applied across a growing range of disciplines. Although typically trained on large public datasets, FMs are often fine-tuned or integrated into Retrieval-Augmented Generation (RAG) systems, which rely on private data. This access, along with their size and costly training, heightens the risk of intellectual property theft. Moreover, multimodal FMs may expose sensitive information. In this work, we examine the FM threat model and discuss the practicality and comprehensiveness of various approaches for securing against them, such as ML-based methods and trusted execution environments (TEEs). We demonstrate that TEEs offer an effective balance between strong security properties, usability, and performance. Specifically, we present a solution achieving less than 10\% overhead versus bare metal for the full Llama2 7B and 13B inference pipelines running inside \intel\ SGX and \intel\ TDX. We also share our configuration files and insights from our implementation. To our knowledge, our work is the first to show the practicality of TEEs for securing FMs.

[Arxiv](https://arxiv.org/abs/2410.05930)