# 超越示例：借助 MCTS 在上下文学习中的高级自动化推理模式

发布时间：2024年11月27日

`LLM应用`

> Beyond Examples: High-level Automated Reasoning Paradigm in In-Context Learning via MCTS

# 摘要

> In-context Learning（ICL）能让大型语言模型（LLMs）借助复杂的提示和高质量的示范来应对下游任务。不过，这种传统的 ICL 范式在应对复杂数学推理任务时存在局限性，主要原因在于其对示例质量的高度依赖以及在困难场景下需要人工介入。为克服这些局限，本文提出了 HiAR-ICL，这是 ICL 中的一种	extbf{高级自动推理}范式，将关注点从特定示例转向抽象思维模式，拓展了 ICL 中上下文的传统概念。HiAR-ICL 引入了五个原子推理动作作为构建链结构模式的基本组成部分。通过蒙特卡罗树搜索，我们探索推理路径并构建思维卡片以指导后续推理。随后，我们开发了一个认知复杂性框架，能动态地将问题与合适的思维卡片相匹配。实验结果表明 HiAR-ICL 行之有效，在 MATH 基准测试中使用 Qwen2.5-7B-Instruct 达到了 79.6％的最先进准确率，超过了 GPT-4o（76.6％）和 Claude 3.5（71.1％）。

> In-context Learning (ICL) enables large language models (LLMs) to tackle downstream tasks through sophisticated prompting and high-quality demonstrations. However, this traditional ICL paradigm shows limitations when facing complex mathematical reasoning tasks, primarily due to its heavy dependence on example quality and the necessity for human intervention in challenging scenarios. To address these limitations, this paper presents HiAR-ICL, a \textbf{Hi}gh-level \textbf{A}utomated \textbf{R}easoning paradigm in \textbf{ICL} that shifts focus from specific examples to abstract thinking patterns, extending the conventional concept of context in ICL. HiAR-ICL introduces five atomic reasoning actions as fundamental components for constructing chain-structured patterns. Using Monte Carlo Tree Search, we explore reasoning paths and construct thought cards to guide subsequent inference. We then develop a cognitive complexity framework that dynamically matches problems with appropriate thought cards. Experimental results demonstrate HiAR-ICL's effectiveness, achieving state-of-the-art accuracy (79.6$\%$) on the MATH benchmark with Qwen2.5-7B-Instruct, surpassing GPT-4o (76.6$\%$) and Claude 3.5 (71.1$\%$).

[Arxiv](https://arxiv.org/abs/2411.18478)