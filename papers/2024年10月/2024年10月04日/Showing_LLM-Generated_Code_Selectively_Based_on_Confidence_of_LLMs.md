# 根据 LLM 的置信度，智能筛选并展示其生成的代码

发布时间：2024年10月04日

`LLM应用` `软件开发` `人工智能`

> Showing LLM-Generated Code Selectively Based on Confidence of LLMs

# 摘要

> LLM 在代码生成方面表现出色，但有时会产出错误程序。阅读代码比编写代码耗时十倍，展示错误代码不仅浪费开发者精力，还带来安全隐患。为此，我们推出了 HonestCoder，一种基于 LLM 的代码生成新方法。HonestCoder 根据 LLM 的置信度，智能筛选并展示代码，为代码正确性提供有力参考。我们通过多模态相似性测量，创新性地评估 LLM 的代码生成置信度。  我们还发布了包含 2,265 个样本的 TruthCodeBench 基准，涵盖 Python 和 Java 两种主流编程语言。实验表明，HonestCoder 在置信度评估和代码正确性判断上表现优异，显著减少错误代码展示，且仅增加极少时间开销（约 0.4 秒/需求）。未来，我们将继续探索 LLM 在软件开发中的应用，期待激发更多关于 LLM 输出可靠性的讨论。

> Large Language Models (LLMs) have shown impressive abilities in code generation, but they may generate erroneous programs. Reading a program takes ten times longer than writing it. Showing these erroneous programs to developers will waste developers' energies and introduce security risks to software.
  To address the above limitations, we propose HonestCoder, a novel LLM-based code generation approach. HonestCoder selectively shows the generated programs to developers based on LLMs' confidence. The confidence provides valuable insights into the correctness of generated programs. To achieve this goal, we propose a novel approach to estimate LLMs' confidence in code generation. It estimates confidence by measuring the multi-modal similarity between LLMs-generated programs.
  We collect and release a multilingual benchmark named TruthCodeBench, which consists of 2,265 samples and covers two popular programming languages (i.e., Python and Java). We apply HonestCoder to four popular LLMs (e.g., DeepSeek-Coder and Code Llama) and evaluate it on TruthCodeBench. Based on the experiments, we obtain the following insights. (1) HonestCoder can effectively estimate LLMs' confidence and accurately determine the correctness of generated programs. For example, HonestCoder outperforms the state-of-the-art baseline by 27.79% in AUROC and 63.74% in AUCPR. (2) HonestCoder can decrease the number of erroneous programs shown to developers. Compared to eight baselines, it can show more correct programs and fewer erroneous programs to developers. (3) Compared to showing code indiscriminately, HonestCoder only adds slight time overhead (approximately 0.4 seconds per requirement). (4) We discuss future directions to facilitate the application of LLMs in software development. We hope this work can motivate broad discussions about measuring the reliability of LLMs' outputs in performing code-related tasks.

[Arxiv](https://arxiv.org/abs/2410.03234)