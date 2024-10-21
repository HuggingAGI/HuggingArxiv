# 在多语言 LLM 中，构建基于等价和继承的鲁棒知识表示，以实现一致推理

发布时间：2024年10月18日

`LLM理论` `人工智能`

> Towards Robust Knowledge Representations in Multilingual LLMs for Equivalence and Inheritance based Consistent Reasoning

# 摘要

> 推理与语言能力是人类智慧的基石，助力问题解决与决策。大型语言模型（LLM）的进步赋予了其卓越的语言能力和推理能力，广泛应用于各领域。然而，LLM 在复杂推理任务上仍显不足，暴露其局限性。我们探讨 LLM 是否具备“等价”与“继承”两种基础关系的推理能力。通过六种语言的新任务与基准测试，发现当前最先进的 LLM 在 17.3-57.5% 的情况下对同一问题给出不同答案，且高达 37.2% 的情况下违反继承规则。为提升语言间一致性，我们提出“组合表示”，将标记视为跨语言等价标记的组合，冲突减少高达 4.7%，彰显共享 LLM 表示的优势。

> Reasoning and linguistic skills form the cornerstone of human intelligence, facilitating problem-solving and decision-making. Recent advances in Large Language Models (LLMs) have led to impressive linguistic capabilities and emergent reasoning behaviors, fueling widespread adoption across application domains. However, LLMs still struggle with complex reasoning tasks, highlighting their systemic limitations. In this work, we focus on evaluating whether LLMs have the requisite representations to reason using two foundational relationships: "equivalence" and "inheritance". We introduce novel tasks and benchmarks spanning six languages and observe that current SOTA LLMs often produce conflicting answers to the same questions across languages in 17.3-57.5% of cases and violate inheritance constraints in up to 37.2% cases. To enhance consistency across languages, we propose novel "Compositional Representations" where tokens are represented as composition of equivalent tokens across languages, with resulting conflict reduction (up to -4.7%) indicating benefits of shared LLM representations.

[Arxiv](https://arxiv.org/abs/2410.14235)