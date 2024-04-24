# 在大型语言模型中，引入了一种模式感知的思考链路提示方法。

发布时间：2024年04月23日

`LLM应用` `人工智能`

> Pattern-Aware Chain-of-Thought Prompting in Large Language Models

# 摘要

> 链式思考（CoT）提示法能够引领语言模型进行复杂的多步逻辑推理。示例的质量对下游推理任务的成效起着决定性作用。尽管现有的自动化方法在示例制作上更注重准确性与语义，我们的研究却发现，推理模式本身在这些任务中更为关键。本文提出了一种新的提示方法——模式感知CoT（PA-CoT），它考虑了不同示例模式的多样性。PA-CoT通过融合步骤长度和中间推理步骤的模式，有效减少了示例带来的偏差，并提升了对不同情境的泛化能力。我们在两个开源的大型语言模型上针对九个推理基准任务进行了实验，实验结果表明，PA-CoT显著提升了推理效率，并且在面对错误时表现出了强大的鲁棒性。相关代码将向公众开放。

> Chain-of-thought (CoT) prompting can guide language models to engage in complex multi-step reasoning. The quality of provided demonstrations significantly impacts the success of downstream inference tasks. While existing automated methods prioritize accuracy and semantics in these demonstrations, we show that the underlying reasoning patterns play a more crucial role in such tasks. In this paper, we propose Pattern-Aware CoT, a prompting method that considers the diversity of demonstration patterns. By incorporating patterns such as step length and reasoning process within intermediate steps, PA-CoT effectively mitigates the issue of bias induced by demonstrations and enables better generalization to diverse scenarios. We conduct experiments on nine reasoning benchmark tasks using two open-source LLMs. The results show that our method substantially enhances reasoning performance and exhibits robustness to errors. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2404.14812)