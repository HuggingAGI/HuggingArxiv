# 幻觉现象中的顺序至关重要：将推理顺序作为基准，并利用反射性提示优化大型语言模型的表现。

发布时间：2024年08月09日

`LLM理论` `人工智能` `软件开发`

> Order Matters in Hallucination: Reasoning Order as Benchmark and Reflexive Prompting for Large-Language-Models

# 摘要

> 自诞生以来，大型语言模型（LLM）便备受瞩目，广泛应用于学术与工业领域。然而，这些模型常陷入“幻觉问题”，其输出虽语法逻辑无误，却事实失真或纯属虚构。近期热议的数值比较错误，如多个 LLM 误判“9.11 > 9.9”，尤为棘手。我们发现，LLM 生成答案与推理的顺序对其一致性影响显著。据此，我们提出新基准，对比两种生成方式的响应，有效识别虚构答案及后续理由。同时，我们创新提示策略，实验显示其能提升 LLM 表现。此研究不仅揭示 LLM 关键缺陷，更提供增强其可靠性的实用方案。

> Large language models (LLMs) have generated significant attention since their inception, finding applications across various academic and industrial domains. However, these models often suffer from the "hallucination problem", where outputs, though grammatically and logically coherent, lack factual accuracy or are entirely fabricated. A particularly troubling issue discovered and widely discussed recently is the numerical comparison error where multiple LLMs incorrectly infer that "9.11$>$9.9". We discovered that the order in which LLMs generate answers and reasoning impacts their consistency. Specifically, results vary significantly when an LLM generates an answer first and then provides the reasoning versus generating the reasoning process first and then the conclusion. Inspired by this, we propose a new benchmark method for assessing LLM consistency: comparing responses generated through these two different approaches. This benchmark effectively identifies instances where LLMs fabricate answers and subsequently generate justifications. Furthermore, we introduce a novel and straightforward prompt strategy designed to mitigate this issue. Experimental results demonstrate that this strategy improves performance across various LLMs compared to direct questioning. This work not only sheds light on a critical flaw in LLMs but also offers a practical solution to enhance their reliability.

[Arxiv](https://arxiv.org/abs/2408.05093)