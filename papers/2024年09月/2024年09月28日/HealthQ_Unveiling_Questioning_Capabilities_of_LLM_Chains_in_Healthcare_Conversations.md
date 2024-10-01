# HealthQ：探索 LLM 链在医疗对话中的提问潜力

发布时间：2024年09月28日

`LLM应用` `人工智能`

> HealthQ: Unveiling Questioning Capabilities of LLM Chains in Healthcare Conversations

# 摘要

> 在数字医疗领域，大型语言模型 (LLM) 主要用于提升问答能力和改善患者互动。然而，要实现有效的患者护理，LLM 需要能够通过提问主动收集信息。为此，我们推出了 HealthQ，一个评估 LLM 提问能力的新框架。我们整合了多种 LLM 链，如 RAG、CoT 和反思链，并引入 LLM 评判器来评估问题质量。为验证 HealthQ，我们采用了 ROUGE 和 NER 等传统 NLP 指标，并从 ChatDoctor 和 MTS-Dialog 数据集中构建了两个自定义数据集。我们的研究首次全面探讨了 LLM 在医疗对话中的提问能力，开发了新的数据集生成方法，并提出了详细的评估策略。

> In digital healthcare, large language models (LLMs) have primarily been utilized to enhance question-answering capabilities and improve patient interactions. However, effective patient care necessitates LLM chains that can actively gather information by posing relevant questions. This paper presents HealthQ, a novel framework designed to evaluate the questioning capabilities of LLM healthcare chains. We implemented several LLM chains, including Retrieval-Augmented Generation (RAG), Chain of Thought (CoT), and reflective chains, and introduced an LLM judge to assess the relevance and informativeness of the generated questions. To validate HealthQ, we employed traditional Natural Language Processing (NLP) metrics such as Recall-Oriented Understudy for Gisting Evaluation (ROUGE) and Named Entity Recognition (NER)-based set comparison, and constructed two custom datasets from public medical note datasets, ChatDoctor and MTS-Dialog. Our contributions are threefold: we provide the first comprehensive study on the questioning capabilities of LLMs in healthcare conversations, develop a novel dataset generation pipeline, and propose a detailed evaluation methodology.

[Arxiv](https://arxiv.org/abs/2409.19487)