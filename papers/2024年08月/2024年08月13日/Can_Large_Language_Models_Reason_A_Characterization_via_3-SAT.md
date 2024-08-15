# 大型语言模型是否具备推理能力？本研究通过 3-SAT 方法对其进行特征分析。

发布时间：2024年08月13日

`LLM理论` `计算机科学` `人工智能`

> Can Large Language Models Reason? A Characterization via 3-SAT

# 摘要

> 尽管大型语言模型 (LLM) 被认为具备高级推理能力，但近期研究揭示了它们常采用捷径而非真正推理，引发了一些质疑。当前评估方法多依赖于可能过度代表的开源基准，这可能影响评估的准确性。我们采用计算理论视角，以 3-SAT 这一典型的 NP-完全问题为核心，探讨了 LLM 的推理能力。通过分析 3-SAT 中的相变，我们实证了 LLM 的推理能力及其随问题难度的变化。实验结果显示，LLM 未能展现出解决 3-SAT 问题所需的真正推理能力。

> Large Language Models (LLMs) are said to possess advanced reasoning abilities. However, some skepticism exists as recent works show how LLMs often bypass true reasoning using shortcuts. Current methods for assessing the reasoning abilities of LLMs typically rely on open-source benchmarks that may be overrepresented in LLM training data, potentially skewing performance. We instead provide a computational theory perspective of reasoning, using 3-SAT -- the prototypical NP-complete problem that lies at the core of logical reasoning and constraint satisfaction tasks. By examining the phase transitions in 3-SAT, we empirically characterize the reasoning abilities of LLMs and show how they vary with the inherent hardness of the problems. Our experimental evidence shows that LLMs cannot perform true reasoning, as is required for solving 3-SAT problems.

[Arxiv](https://arxiv.org/abs/2408.07215)