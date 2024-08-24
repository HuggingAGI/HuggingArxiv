# 大型语言模型如同自学成才的推理高手，通过量身定制的问题解决演示，其应用能力得以进一步提升。

发布时间：2024年08月22日

`LLM应用` `人工智能`

> Large Language Models Are Self-Taught Reasoners: Enhancing LLM Applications via Tailored Problem-Solving Demonstrations

# 摘要

> 为了提升大型语言模型的应用，通常采用人工编写的演示进行指导。但人工成本高且效果未必最佳，尤其是在专业领域如临床诊断。为此，我们探索了自动生成定制演示的方法，确保与目标实例技能一致。我们提出的SELF-TAUGHT框架，能在零-shot模式下，为特定问题定制演示并过滤以确保质量。在多项选择题和阿尔茨海默病诊断等15个任务中，SELF-TAUGHT表现优于现有基线。我们还对其泛化能力、生成质量等进行了深入分析。

> Guiding large language models with a selected set of human-authored demonstrations is a common practice for improving LLM applications. However, human effort can be costly, especially in specialized domains (e.g., clinical diagnosis), and does not guarantee optimal performance due to the potential discrepancy of target skills between selected demonstrations and real test instances. Motivated by these, this paper explores the automatic creation of customized demonstrations, whose target skills align with the given target instance. We present SELF-TAUGHT, a problem-solving framework, which facilitates demonstrations that are "tailored" to the target problem and "filtered" for better quality (i.e., correctness) in a zero-shot manner. In 15 tasks of multiple-choice questions of diverse domains and the diagnosis of Alzheimer's disease (AD) with real-world patients, SELF-TAUGHT achieves superior performance to strong baselines (e.g., Few-shot CoT, Plan-and-Solve, Auto-CoT). We conduct comprehensive analyses on SELF-TAUGHT, including its generalizability to existing prompting methods and different LLMs, the quality of its intermediate generation, and more.

[Arxiv](https://arxiv.org/abs/2408.12315)