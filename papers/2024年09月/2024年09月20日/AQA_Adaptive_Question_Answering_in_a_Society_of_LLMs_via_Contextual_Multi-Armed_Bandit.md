# AQA：在 LLM 社会中，通过上下文多臂老虎机实现自适应问答

发布时间：2024年09月20日

`LLM应用` `问答系统` `人工智能`

> AQA: Adaptive Question Answering in a Society of LLMs via Contextual Multi-Armed Bandit

# 摘要

> 在问答系统中，不同问题需要不同的解答策略。有些问题只需简单查找，而有些则需复杂的多步推理。这一现象促使我们开发一种动态方法，自适应地为每个问题选择最合适的策略，从而构建更高效、更全面的问答系统。基于近期在多大型语言模型编排上的进展，我们将自适应问答视为动态编排挑战，并将其定义为上下文多臂赌博机问题。我们训练了一个线性上置信界模型，以优化不同问题类型与最优多 LLM 通信图之间的映射。实验证明，该方案在自适应编排多模块问答系统时表现出色，既利用了复杂策略的优势，又在简单策略足够时避免了其成本。

> In question answering (QA), different questions can be effectively addressed with different answering strategies. Some require a simple lookup, while others need complex, multi-step reasoning to be answered adequately. This observation motivates the development of a dynamic method that adaptively selects the most suitable QA strategy for each question, enabling more efficient and effective systems capable of addressing a broader range of question types. To this aim, we build on recent advances in the orchestration of multiple large language models (LLMs) and formulate adaptive QA as a dynamic orchestration challenge. We define this as a contextual multi-armed bandit problem, where the context is defined by the characteristics of the incoming question and the action space consists of potential communication graph configurations among the LLM agents. We then train a linear upper confidence bound model to learn an optimal mapping between different question types and their corresponding optimal multi-LLM communication graph representation. Our experiments show that the proposed solution is viable for adaptive orchestration of a QA system with multiple modules, as it combines the superior performance of more complex strategies while avoiding their costs when simpler strategies suffice.%

[Arxiv](https://arxiv.org/abs/2409.13447)