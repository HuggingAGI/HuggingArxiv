# 无需算法的算术：语言模型凭借一堆启发式方法来解决数学问题

发布时间：2024年10月28日

`LLM理论` `人工智能`

> Arithmetic Without Algorithms: Language Models Solve Math With a Bag of Heuristics

# 摘要

> 大型语言模型（LLMs）究竟是通过学习稳健的通用算法来解决推理任务，还是靠记忆训练数据呢？为探究此问题，我们以算术推理作为典型任务。借助因果分析，我们找出了模型的一个子集（一个电路），它能解释基本算术逻辑中模型的大部分行为，并对其功能进行了审视。聚焦到单个电路神经元层面，我们发现了一组稀疏但重要的神经元，它们实现了简单的启发式策略。每个启发式策略能识别一种数字输入模式并给出相应答案。我们推测这些启发式神经元的组合就是生成正确算术答案的机制。为验证这一推测，我们将每个神经元划分成若干启发式类型，比如当操作数处于特定范围时激活的神经元，结果发现这些启发式类型的无序组合正是解释模型在算术提示上大部分准确性的机制。最后，我们证实这种机制在训练早期就成为了算术准确性的主要来源。总之，我们在多个 LLMs 上的实验结果表明，LLMs 做算术既非依靠强大算法，也非依赖记忆，而是依赖“一堆启发式策略”。

> Do large language models (LLMs) solve reasoning tasks by learning robust generalizable algorithms, or do they memorize training data? To investigate this question, we use arithmetic reasoning as a representative task. Using causal analysis, we identify a subset of the model (a circuit) that explains most of the model's behavior for basic arithmetic logic and examine its functionality. By zooming in on the level of individual circuit neurons, we discover a sparse set of important neurons that implement simple heuristics. Each heuristic identifies a numerical input pattern and outputs corresponding answers. We hypothesize that the combination of these heuristic neurons is the mechanism used to produce correct arithmetic answers. To test this, we categorize each neuron into several heuristic types-such as neurons that activate when an operand falls within a certain range-and find that the unordered combination of these heuristic types is the mechanism that explains most of the model's accuracy on arithmetic prompts. Finally, we demonstrate that this mechanism appears as the main source of arithmetic accuracy early in training. Overall, our experimental results across several LLMs show that LLMs perform arithmetic using neither robust algorithms nor memorization; rather, they rely on a "bag of heuristics".

[Arxiv](https://arxiv.org/abs/2410.21272)