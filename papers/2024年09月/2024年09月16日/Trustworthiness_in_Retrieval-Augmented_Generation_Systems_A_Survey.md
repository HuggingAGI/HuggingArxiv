# 检索增强生成系统中的信任度调查

发布时间：2024年09月16日

`RAG` `人工智能` `数据安全`

> Trustworthiness in Retrieval-Augmented Generation Systems: A Survey

# 摘要

> RAG 已成为 LLM 开发的核心范式，尽管当前研究多聚焦于性能优化，但其可信度仍待探索。RAG 通过引入外部数据库知识，有望解决 LLM 的幻觉问题，但也可能因信息不当而产生不良内容。为此，我们提出一个涵盖事实性、鲁棒性、公平性、透明度、问责性和隐私性六个维度的评估框架，全面审视现有文献，并创建评估基准，对多种模型进行综合评估。通过这项工作，我们不仅为未来研究奠定基础，更为提升 RAG 系统在实际应用中的可信度提供实用指南。

> Retrieval-Augmented Generation (RAG) has quickly grown into a pivotal paradigm in the development of Large Language Models (LLMs). While much of the current research in this field focuses on performance optimization, particularly in terms of accuracy and efficiency, the trustworthiness of RAG systems remains an area still under exploration. From a positive perspective, RAG systems are promising to enhance LLMs by providing them with useful and up-to-date knowledge from vast external databases, thereby mitigating the long-standing problem of hallucination. While from a negative perspective, RAG systems are at the risk of generating undesirable contents if the retrieved information is either inappropriate or poorly utilized. To address these concerns, we propose a unified framework that assesses the trustworthiness of RAG systems across six key dimensions: factuality, robustness, fairness, transparency, accountability, and privacy. Within this framework, we thoroughly review the existing literature on each dimension. Additionally, we create the evaluation benchmark regarding the six dimensions and conduct comprehensive evaluations for a variety of proprietary and open-source models. Finally, we identify the potential challenges for future research based on our investigation results. Through this work, we aim to lay a structured foundation for future investigations and provide practical insights for enhancing the trustworthiness of RAG systems in real-world applications.

[Arxiv](https://arxiv.org/abs/2409.10102)