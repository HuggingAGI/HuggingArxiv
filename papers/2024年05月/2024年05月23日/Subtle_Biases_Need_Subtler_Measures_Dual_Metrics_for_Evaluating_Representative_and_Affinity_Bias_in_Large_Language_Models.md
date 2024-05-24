# 微妙偏见，需以细腻之策应对：大型语言模型中代表性与亲和性偏差的双重评估指标

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的微妙偏见，包括代表性偏见和亲和性偏见，并提出了相应的偏见分数（RBS和ABS）。通过开发创意导向生成套件（CoGS）来检测这些偏见，并分析了主流LLMs中的偏见模式。这些研究内容属于对LLMs内部机制和偏见理论的深入探讨，因此归类为LLM理论。` `社会科学`

> Subtle Biases Need Subtler Measures: Dual Metrics for Evaluating Representative and Affinity Bias in Large Language Models

# 摘要

> 大型语言模型（LLMs）研究中常被忽视的微妙偏见，虽不显眼，却能显著影响模型输出，使其偏向特定社会叙事。本研究聚焦于LLMs中的两种偏见：代表性偏见，即模型倾向于生成反映特定群体经验的输出；亲和性偏见，指模型对特定叙事或观点的偏好。我们创新性地提出了代表性偏见分数（RBS）和亲和性偏见分数（ABS），并开发了创意导向生成套件（CoGS），通过定制评分标准的开放式任务，如短篇小说和诗歌创作，来检测这些偏见。分析发现，主流LLMs存在明显的代表性偏见，偏好白人、异性恋和男性身份。亲和性偏见的研究则揭示了各模型内部的独特评价模式，类似“偏见指纹”。这种模式在人类评价者中也可见，揭示了人机偏见感知间的复杂互动。

> Research on Large Language Models (LLMs) has often neglected subtle biases that, although less apparent, can significantly influence the models' outputs toward particular social narratives. This study addresses two such biases within LLMs: \textit{representative bias}, which denotes a tendency of LLMs to generate outputs that mirror the experiences of certain identity groups, and \textit{affinity bias}, reflecting the models' evaluative preferences for specific narratives or viewpoints. We introduce two novel metrics to measure these biases: the Representative Bias Score (RBS) and the Affinity Bias Score (ABS), and present the Creativity-Oriented Generation Suite (CoGS), a collection of open-ended tasks such as short story writing and poetry composition, designed with customized rubrics to detect these subtle biases. Our analysis uncovers marked representative biases in prominent LLMs, with a preference for identities associated with being white, straight, and men. Furthermore, our investigation of affinity bias reveals distinctive evaluative patterns within each model, akin to `bias fingerprints'. This trend is also seen in human evaluators, highlighting a complex interplay between human and machine bias perceptions.

[Arxiv](https://arxiv.org/abs/2405.14555)