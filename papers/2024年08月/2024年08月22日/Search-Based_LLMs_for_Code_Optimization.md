# 利用搜索技术优化代码的 LLM 模型

发布时间：2024年08月22日

`LLM应用` `软件开发` `人工智能`

> Search-Based LLMs for Code Optimization

# 摘要

> 开发者编写的代码常面临效率低下和性能错误的问题，这促使了自动化重构方法的研究，以实现代码优化。早期的优化研究依赖于规则，专注于个别低效问题，但这种方法既耗时又覆盖面有限。近期研究将代码优化视为序列生成问题，并借助深度学习技术，特别是大型语言模型（LLM），直接生成优化代码。尽管这些方法性能卓越，但一步到位的生成模式难以达到最优解，尤其是复杂优化方法难以被LLM捕捉，且在精确注入优化知识方面存在挑战，导致代码优化不足。为此，我们提出了一种基于搜索的LLM框架——SBLLM，该框架通过迭代细化和发现改进的优化方法，有效整合了LLM与进化搜索。SBLLM包含三个核心组件：一是基于执行的代表性样本选择，评估并优先处理有潜力的优化代码；二是自适应优化模式检索，精准注入优化模式，引导LLM逐步提升优化方法；三是受遗传算法启发的心智链提示，协助LLM融合不同优化方法，生成更优的优化方案。

> The code written by developers usually suffers from efficiency problems and contain various performance bugs. These inefficiencies necessitate the research of automated refactoring methods for code optimization. Early research in code optimization employs rule-based methods and focuses on specific inefficiency issues, which are labor-intensive and suffer from the low coverage issue. Recent work regards the task as a sequence generation problem, and resorts to deep learning (DL) techniques such as large language models (LLMs). These methods typically prompt LLMs to directly generate optimized code. Although these methods show state-of-the-art performance, such one-step generation paradigm is hard to achieve an optimal solution. First, complex optimization methods such as combinatorial ones are hard to be captured by LLMs. Second, the one-step generation paradigm poses challenge in precisely infusing the knowledge required for effective code optimization within LLMs, resulting in under-optimized code.To address these problems, we propose to model this task from the search perspective, and propose a search-based LLMs framework named SBLLM that enables iterative refinement and discovery of improved optimization methods. SBLLM synergistically integrate LLMs with evolutionary search and consists of three key components: 1) an execution-based representative sample selection part that evaluates the fitness of each existing optimized code and prioritizes promising ones to pilot the generation of improved code; 2) an adaptive optimization pattern retrieval part that infuses targeted optimization patterns into the model for guiding LLMs towards rectifying and progressively enhancing their optimization methods; and 3) a genetic operator-inspired chain-of-thought prompting part that aids LLMs in combining different optimization methods and generating improved optimization methods.

[Arxiv](https://arxiv.org/abs/2408.12159)