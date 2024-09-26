# RoleBreak：角色幻觉——角色扮演系统中的越狱攻击

发布时间：2024年09月25日

`LLM应用` `人工智能`

> RoleBreak: Character Hallucination as a Jailbreak Attack in Role-Playing Systems

# 摘要

> 基于 LLM 的角色扮演系统在情感交流中日益重要，但易受角色幻觉影响，即模型偏离预设角色，生成与角色不符的回应。本文首次从攻击角度系统分析角色幻觉，提出 RoleBreak 框架，识别查询稀疏性和角色-查询冲突为关键驱动因素。我们构建了 RoleBreakEval 数据集，评估现有幻觉缓解技术，发现即使强化模型也易受攻击。为此，我们提出叙述者模式，通过叙述生成补充上下文，缓解冲突，提升泛化能力。实验显示，叙述者模式在减少幻觉、增强角色和查询忠诚度及提高叙事连贯性方面，显著优于传统拒绝策略。

> Role-playing systems powered by large language models (LLMs) have become increasingly influential in emotional communication applications. However, these systems are susceptible to character hallucinations, where the model deviates from predefined character roles and generates responses that are inconsistent with the intended persona. This paper presents the first systematic analysis of character hallucination from an attack perspective, introducing the RoleBreak framework. Our framework identifies two core mechanisms-query sparsity and role-query conflict-as key factors driving character hallucination. Leveraging these insights, we construct a novel dataset, RoleBreakEval, to evaluate existing hallucination mitigation techniques. Our experiments reveal that even enhanced models trained to minimize hallucination remain vulnerable to attacks. To address these vulnerabilities, we propose a novel defence strategy, the Narrator Mode, which generates supplemental context through narration to mitigate role-query conflicts and improve query generalization. Experimental results demonstrate that Narrator Mode significantly outperforms traditional refusal-based strategies by reducing hallucinations, enhancing fidelity to character roles and queries, and improving overall narrative coherence.

[Arxiv](https://arxiv.org/abs/2409.16727)