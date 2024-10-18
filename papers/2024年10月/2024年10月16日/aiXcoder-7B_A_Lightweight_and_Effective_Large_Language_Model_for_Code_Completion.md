# aiXcoder-7B：一款轻巧高效的代码补全大型语言模型

发布时间：2024年10月16日

`LLM应用` `软件开发` `人工智能`

> aiXcoder-7B: A Lightweight and Effective Large Language Model for Code Completion

# 摘要

> 大型语言模型（LLM）在代码补全中的应用日益广泛，但扩大模型规模虽能提升准确性，却也增加了响应时间和开发者的负担。为此，我们推出了轻量高效的 aiXcoder-7B，它在仅 70 亿参数的规模下，代码补全准确性超越了众多更大规模的模型。aiXcoder-7B 的成功得益于三大创新：多目标训练，包括我们独创的结构化填空（SFIM），有效提升了模型对代码语法结构的理解；多样化的数据采样策略，增强了模型跨文件上下文的理解能力；以及海量高质量数据的支撑，确保了模型对代码分布的广泛学习。在多个代码补全基准测试中，aiXcoder-7B 表现卓越，不仅胜过同规模模型，甚至超越了部分更大规模的竞争对手，成为学术界和工业界的理想选择。此外，我们还总结了三条宝贵经验，助力下一代代码 LLM 的训练。aiXcoder-7B 的开源项目已获得 2,193 个 GitHub Stars，备受瞩目。

> Large Language Models (LLMs) have been widely used in code completion, and researchers are focusing on scaling up LLMs to improve their accuracy. However, larger LLMs will increase the response time of code completion and decrease the developers' productivity. In this paper, we propose a lightweight and effective LLM for code completion named aiXcoder-7B. Compared to existing LLMs, aiXcoder-7B achieves higher code completion accuracy while having smaller scales (i.e., 7 billion parameters). We attribute the superiority of aiXcoder-7B to three key factors: (1) Multi-objective training. We employ three training objectives, one of which is our proposed Structured Fill-In-the-Middle (SFIM). SFIM considers the syntax structures in code and effectively improves the performance of LLMs for code. (2) Diverse data sampling strategies. They consider inter-file relationships and enhance the capability of LLMs in understanding cross-file contexts. (3) Extensive high-quality data. We establish a rigorous data collection pipeline and consume a total of 1.2 trillion unique tokens for training aiXcoder-7B. This vast volume of data enables aiXcoder-7B to learn a broad distribution of code. We evaluate aiXcoder-7B in five popular code completion benchmarks and a new benchmark collected by this paper. The results show that aiXcoder-7B outperforms the latest six LLMs with similar sizes and even surpasses four larger LLMs (e.g., StarCoder2-15B and CodeLlama-34B), positioning aiXcoder-7B as a lightweight and effective LLM for academia and industry. Finally, we summarize three valuable insights for helping practitioners train the next generations of LLMs for code. aiXcoder-7B has been open-souced and gained significant attention. As of the submission date, aiXcoder-7B has received 2,193 GitHub Stars.

[Arxiv](https://arxiv.org/abs/2410.13187)