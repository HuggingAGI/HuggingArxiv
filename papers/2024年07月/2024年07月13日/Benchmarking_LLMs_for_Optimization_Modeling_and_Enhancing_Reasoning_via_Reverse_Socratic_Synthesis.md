# 通过反向苏格拉底合成，我们为 LLM 的优化建模和推理能力设立了基准测试。

发布时间：2024年07月13日

`LLM应用` `人工智能`

> Benchmarking LLMs for Optimization Modeling and Enhancing Reasoning via Reverse Socratic Synthesis

# 摘要

> 大型语言模型 (LLM) 在数学推理中展现了其问题解决能力。然而，当前的 OPT 基准仅解决线性规划，远不能满足复杂现实情况。为此，我们提出了 E-OPT，一个具有人类可读输入和输出的端到端优化问题解决基准，包含丰富的优化问题，全面评估 LLM 的解决能力。此外，为了缓解数据稀缺性，并缩小开源与闭源 LLM 之间的差距，我们提出了 ReSocratic 数据合成方法，通过逐步合成优化场景并反向翻译成问题，构建了 ReSocratic-29k 数据集。实验表明，Llama3-8b 在 E-OPT 上的表现显著提升至 51.7%，DeepSeek-V2 达到 61.0%，接近 GPT-4 的 65.5%。

> Large language models (LLMs) have exhibited their problem-solving ability in mathematical reasoning. Solving realistic optimization (OPT) problems in industrial application scenarios requires advanced and applied math ability. However, current OPT benchmarks that merely solve linear programming are far from complex realistic situations. In this work, we propose E-OPT, a benchmark for end-to-end optimization problem-solving with human-readable inputs and outputs. E-OPT contains rich optimization problems, including linear/nonlinear programming with/without table data, which can comprehensively evaluate LLMs' solving ability. In our benchmark, LLMs are required to correctly understand the problem in E-OPT and call code solver to get precise numerical answers. Furthermore, to alleviate the data scarcity for optimization problems, and to bridge the gap between open-source LLMs on a small scale (e.g., Llama-2-7b and Llama-3-8b) and closed-source LLMs (e.g., GPT-4), we further propose a novel data synthesis method namely ReSocratic. Unlike general data synthesis methods that proceed from questions to answers, ReSocratic first incrementally synthesizes optimization scenarios with mathematical formulations step by step and then back-translates the generated scenarios into questions. In such a way, we construct the ReSocratic-29k dataset from a small seed sample pool with the powerful open-source large model DeepSeek-V2. To demonstrate the effectiveness of ReSocratic, we conduct supervised fine-tuning with ReSocratic-29k on multiple open-source models. The results show that Llama3-8b is significantly improved from 13.6% to 51.7% on E-OPT, while DeepSeek-V2 reaches 61.0%, approaching 65.5% of GPT-4.

[Arxiv](https://arxiv.org/abs/2407.09887)