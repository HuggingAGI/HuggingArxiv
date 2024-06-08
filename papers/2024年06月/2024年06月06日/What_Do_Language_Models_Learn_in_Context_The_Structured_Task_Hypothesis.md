# 语言模型在上下文中究竟学到了什么？这引出了结构化任务假设的探讨。

发布时间：2024年06月06日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在上下文学习（ICL）方面的能力，并通过对文本分类任务的实验来验证关于ICL的三种主要假设。研究结果表明，LLMs利用预训练期间学习的任务组合来实现上下文学习。这种研究属于对LLMs理论能力的深入探讨，因此应归类为LLM理论。` `机器学习`

> What Do Language Models Learn in Context? The Structured Task Hypothesis

# 摘要

> 大型语言模型（LLMs）能够从演示中的上下文示例学习新任务，这一现象被称为上下文学习（ICL）。研究者们对此进行了广泛探讨，提出了三种主要假设：任务选择、元学习和任务组合。本文通过一系列文本分类任务的实验，验证了这些假设。实验结果否定了前两种假设，支持了第三种假设，即LLMs利用预训练期间学习的任务组合来实现上下文学习。这表明，LLMs能够通过组合预训练任务来学习新任务。

> Large language models (LLMs) exhibit an intriguing ability to learn a novel task from in-context examples presented in a demonstration, termed in-context learning (ICL). Understandably, a swath of research has been dedicated to uncovering the theories underpinning ICL. One popular hypothesis explains ICL by task selection. LLMs identify the task based on the demonstration and generalize it to the prompt. Another popular hypothesis is that ICL is a form of meta-learning, i.e., the models learn a learning algorithm at pre-training time and apply it to the demonstration. Finally, a third hypothesis argues that LLMs use the demonstration to select a composition of tasks learned during pre-training to perform ICL. In this paper, we empirically explore these three hypotheses that explain LLMs' ability to learn in context with a suite of experiments derived from common text classification tasks. We invalidate the first two hypotheses with counterexamples and provide evidence in support of the last hypothesis. Our results suggest an LLM could learn a novel task in context via composing tasks learned during pre-training.

[Arxiv](https://arxiv.org/abs/2406.04216)