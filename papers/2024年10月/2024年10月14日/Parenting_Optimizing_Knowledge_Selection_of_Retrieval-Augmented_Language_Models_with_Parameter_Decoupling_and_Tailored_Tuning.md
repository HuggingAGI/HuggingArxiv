# 育儿之道：通过参数解耦与定制调优，优化检索增强语言模型的知识选择

发布时间：2024年10月14日

`RAG` `人工智能`

> Parenting: Optimizing Knowledge Selection of Retrieval-Augmented Language Models with Parameter Decoupling and Tailored Tuning

# 摘要

> RAG 通过引入外部知识，有效解决了 LLM 在幻觉生成和知识过时上的难题。然而，内外知识冲突和检索噪声常使 LLM 难以有效整合外部证据，导致性能下滑。现有方法虽尝试解决，但常在模型遵循性和鲁棒性间难以平衡，导致学习方差显著。受人类认知启发，我们提出 Parenting 框架，在 LLM 参数空间内解耦遵循性和鲁棒性。通过前向激活增益识别关键参数单元，并采用类型引导的定制调优策略，实现两者的平衡增强。广泛实验证明，我们的方法既有效又通用。

> Retrieval-Augmented Generation (RAG) offers an effective solution to the issues faced by Large Language Models (LLMs) in hallucination generation and knowledge obsolescence by incorporating externally retrieved knowledge. However, due to potential conflicts between internal and external knowledge, as well as retrieval noise, LLMs often struggle to effectively integrate external evidence, leading to a decline in performance. Although existing methods attempt to tackle these challenges, they often struggle to strike a balance between model adherence and robustness, resulting in significant learning variance. Inspired by human cognitive processes, we propose Parenting, a novel framework that decouples adherence and robustness within the parameter space of LLMs. Specifically, Parenting utilizes a key parameter mining method based on forward activation gain to identify and isolate the crucial parameter units that are strongly linked to adherence and robustness. Then, Parenting employs a type-guided tailored tuning strategy, applying specific and appropriate fine-tuning methods to parameter units representing different capabilities, aiming to achieve a balanced enhancement of adherence and robustness. Extensive experiments on various datasets and models validate the effectiveness and generalizability of our methods.

[Arxiv](https://arxiv.org/abs/2410.10360)