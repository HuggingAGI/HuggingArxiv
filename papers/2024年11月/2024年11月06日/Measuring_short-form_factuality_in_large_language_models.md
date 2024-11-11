# 测量大型语言模型中的短格式真实性

发布时间：2024年11月06日

`LLM应用` `语言模型` `评估基准`

> Measuring short-form factuality in large language models

# 摘要

> 我们提出了 SimpleQA，这是一个评估语言模型回答简短、寻求事实问题能力的基准。在设计这个评估时，我们优先考虑了两个特性。首先，SimpleQA 具有挑战性，因为它是针对 GPT-4 的回答进行对抗性收集的。其次，回答易于评分，因为问题的创建方式使得只有一个单一、无可争议的答案。SimpleQA 中的每个答案都被评为正确、不正确或未尝试。具有理想行为的模型会尽可能多地答对问题，同时不会尝试那些它不确定自己知道正确答案的问题。SimpleQA 是对模型是否“知道自己知道什么”的一个简单、有针对性的评估，我们希望这个基准在接下来的几代前沿模型中仍然具有相关性。SimpleQA 可以在 https://github.com/openai/simple-evals 找到。

> We present SimpleQA, a benchmark that evaluates the ability of language models to answer short, fact-seeking questions. We prioritized two properties in designing this eval. First, SimpleQA is challenging, as it is adversarially collected against GPT-4 responses. Second, responses are easy to grade, because questions are created such that there exists only a single, indisputable answer. Each answer in SimpleQA is graded as either correct, incorrect, or not attempted. A model with ideal behavior would get as many questions correct as possible while not attempting the questions for which it is not confident it knows the correct answer. SimpleQA is a simple, targeted evaluation for whether models "know what they know," and our hope is that this benchmark will remain relevant for the next few generations of frontier models. SimpleQA can be found at https://github.com/openai/simple-evals.

[Arxiv](https://arxiv.org/abs/2411.04368)