# ConflictBank：评估 LLM 中知识冲突影响的基准

发布时间：2024年08月21日

`LLM理论` `人工智能` `知识管理`

> ConflictBank: A Benchmark for Evaluating the Influence of Knowledge Conflicts in LLM

# 摘要

> 尽管大型语言模型 (LLM) 在多领域取得了显著进展，但知识冲突这一幻觉的主要来源却鲜有研究。我们针对这一研究空白，推出了 ConflictBank，首个全面评估知识冲突的基准，涵盖检索知识冲突、模型内部知识冲突及两者间的相互作用。通过深入分析四个模型家族和十二个 LLM 实例，我们揭示了错误信息、时间差异和语义分歧引发的冲突。基于创新构建框架，我们生成了大量声明-证据对和 QA 对，揭示了模型规模、冲突原因和类型的多重发现。我们期待 ConflictBank 能助力社区深入理解模型在冲突中的表现，推动开发更可靠的 LLM。

> Large language models (LLMs) have achieved impressive advancements across numerous disciplines, yet the critical issue of knowledge conflicts, a major source of hallucinations, has rarely been studied. Only a few research explored the conflicts between the inherent knowledge of LLMs and the retrieved contextual knowledge. However, a thorough assessment of knowledge conflict in LLMs is still missing. Motivated by this research gap, we present ConflictBank, the first comprehensive benchmark developed to systematically evaluate knowledge conflicts from three aspects: (i) conflicts encountered in retrieved knowledge, (ii) conflicts within the models' encoded knowledge, and (iii) the interplay between these conflict forms. Our investigation delves into four model families and twelve LLM instances, meticulously analyzing conflicts stemming from misinformation, temporal discrepancies, and semantic divergences. Based on our proposed novel construction framework, we create 7,453,853 claim-evidence pairs and 553,117 QA pairs. We present numerous findings on model scale, conflict causes, and conflict types. We hope our ConflictBank benchmark will help the community better understand model behavior in conflicts and develop more reliable LLMs.

[Arxiv](https://arxiv.org/abs/2408.12076)