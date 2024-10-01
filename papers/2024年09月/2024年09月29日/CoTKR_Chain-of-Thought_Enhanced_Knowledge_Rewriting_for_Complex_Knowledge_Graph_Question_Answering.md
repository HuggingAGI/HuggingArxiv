# CoTKR：通过链式思维增强知识重写，提升复杂知识图谱问答的效率。

发布时间：2024年09月29日

`RAG` `知识图谱` `问答系统`

> CoTKR: Chain-of-Thought Enhanced Knowledge Rewriting for Complex Knowledge Graph Question Answering

# 摘要

> 近期研究探索了结合检索增强生成 (RAG) 的大型语言模型 (LLM) 在知识图谱问答 (KGQA) 中的应用。这些研究通常需要将检索到的子图转换为 LLM 能理解的自然语言格式。然而，面对复杂问题时，现有方法重写的知识可能包含无关信息、遗漏关键细节，或未能与问题语义对齐。为此，我们提出了 CoTKR，一种思维链增强的知识重写方法，通过交错生成推理轨迹和知识，缓解单步重写的局限。同时，为弥合知识重写器与问答模型间的偏好差距，我们设计了 PAQAF 训练策略，利用问答反馈优化重写器。实验结果显示，CoTKR 生成的知识表示对问答模型最为有利，显著提升了 LLM 在 KGQA 中的表现。

> Recent studies have explored the use of Large Language Models (LLMs) with Retrieval Augmented Generation (RAG) for Knowledge Graph Question Answering (KGQA). They typically require rewriting retrieved subgraphs into natural language formats comprehensible to LLMs. However, when tackling complex questions, the knowledge rewritten by existing methods may include irrelevant information, omit crucial details, or fail to align with the question's semantics. To address them, we propose a novel rewriting method CoTKR, Chain-of-Thought Enhanced Knowledge Rewriting, for generating reasoning traces and corresponding knowledge in an interleaved manner, thereby mitigating the limitations of single-step knowledge rewriting. Additionally, to bridge the preference gap between the knowledge rewriter and the question answering (QA) model, we propose a training strategy PAQAF, Preference Alignment from Question Answering Feedback, for leveraging feedback from the QA model to further optimize the knowledge rewriter. We conduct experiments using various LLMs across several KGQA benchmarks. Experimental results demonstrate that, compared with previous knowledge rewriting methods, CoTKR generates the most beneficial knowledge representation for QA models, which significantly improves the performance of LLMs in KGQA.

[Arxiv](https://arxiv.org/abs/2409.19753)