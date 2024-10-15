# CoMAT：通过链式数学思维注释，提升数学推理能力

发布时间：2024年10月14日

`LLM应用` `人工智能`

> CoMAT: Chain of Mathematically Annotated Thought Improves Mathematical Reasoning

# 摘要

> 尽管在 Chain-of-Thought (CoT) 等提示技术方面有所进步，数学推理对 LLM 仍是一大难题。我们提出的 $\textbf{Chain of Mathematically Annotated Thought (CoMAT)}$ 通过 $\textit{Symbolic Conversion}$ 和 $\textit{Reasoning Execution}$ 两阶段，显著提升推理能力。CoMAT 仅依赖单个 LLM，无需外部工具。在多个 LLM 测试中，CoMAT 在七项基准测试中六项超越传统 CoT，尤其在 MMLU-Redux (MATH) 和 GaoKao MCQ 上分别提升 4.48% 和 4.58%。此外，CoMAT 确保推理过程透明、可验证，为复杂数学任务提供可靠解决方案。

> Mathematical reasoning remains a significant challenge for large language models (LLMs), despite progress in prompting techniques such as Chain-of-Thought (CoT). We present $\textbf{Chain of Mathematically Annotated Thought (CoMAT)}$, which enhances reasoning through two stages: $\textit{Symbolic Conversion}$ (converting natural language queries into symbolic form) and $\textit{Reasoning Execution}$ (deriving answers from symbolic representations). CoMAT operates entirely with a single LLM and without external solvers. Across four LLMs, CoMAT outperforms traditional CoT on six out of seven benchmarks, achieving gains of 4.48% on MMLU-Redux (MATH) and 4.58% on GaoKao MCQ. In addition to improved performance, CoMAT ensures faithfulness and verifiability, offering a transparent reasoning process for complex mathematical tasks

[Arxiv](https://arxiv.org/abs/2410.10336)