# 语言模型在上下文中究竟学到了什么？这引出了结构化任务假设的探讨。

发布时间：2024年06月06日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在上下文学习（ICL）方面的理论机制，具体分析了三种不同的假设，并通过实验对这些假设进行了验证。由于论文主要关注的是LLMs的理论理解和机制解释，而不是具体的应用或Agent的设计，因此最合适的分类是LLM理论。` `机器学习`

> What Do Language Models Learn in Context? The Structured Task Hypothesis

# 摘要

> 大型语言模型（LLMs）能够从演示中的上下文示例学习新任务，这一现象被称为上下文学习（ICL）。研究界对此现象背后的理论进行了广泛探讨。一种观点认为，LLMs通过任务选择机制识别并推广任务至新提示。另一种观点则认为ICL是元学习的一种形式，模型在预训练阶段学习了一种学习策略，并将其应用于新演示。第三种观点则提出，LLMs利用演示来组合预训练期间学习的任务以实现ICL。本文通过一系列文本分类任务的实验，对这三种假设进行了实证检验。我们通过反例否定了前两种假设，并提供了支持第三种假设的证据。研究结果显示，LLMs能够通过组合预训练期间学习的任务，在上下文中学习新任务。

> Large language models (LLMs) exhibit an intriguing ability to learn a novel task from in-context examples presented in a demonstration, termed in-context learning (ICL). Understandably, a swath of research has been dedicated to uncovering the theories underpinning ICL. One popular hypothesis explains ICL by task selection. LLMs identify the task based on the demonstration and generalize it to the prompt. Another popular hypothesis is that ICL is a form of meta-learning, i.e., the models learn a learning algorithm at pre-training time and apply it to the demonstration. Finally, a third hypothesis argues that LLMs use the demonstration to select a composition of tasks learned during pre-training to perform ICL. In this paper, we empirically explore these three hypotheses that explain LLMs' ability to learn in context with a suite of experiments derived from common text classification tasks. We invalidate the first two hypotheses with counterexamples and provide evidence in support of the last hypothesis. Our results suggest an LLM could learn a novel task in context via composing tasks learned during pre-training.

[Arxiv](https://arxiv.org/abs/2406.04216)