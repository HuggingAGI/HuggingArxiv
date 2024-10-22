# ToW：词语的思想助力大型语言模型推理能力的提升

发布时间：2024年10月21日

`LLM理论` `人工智能`

> ToW: Thoughts of Words Improve Reasoning in Large Language Models

# 摘要

> 我们提出了“词的思想”（ToW），一种创新的训练时数据增强方法，用于下一个词预测。ToW 将下一个词预测视为核心推理任务，并在预训练文本中注入细粒度的思想，解释下一个词的选择及其与之前上下文的关系。这解决了现有方法的两个根本问题：事实幻觉和隐含推理过程学习效率低下。我们探索了通过从更大模型中提取来获取 ToW 注释的第一步。仅使用 70K ToW 注释进行持续预训练后，模型的推理性能平均提升了 7% 到 9%，同时模型幻觉减少了高达 10%。此外，ToW 完全与任务和应用无关，不会引入额外的标签或语义偏见。

> We introduce thoughts of words (ToW), a novel training-time data-augmentation method for next-word prediction. ToW views next-word prediction as a core reasoning task and injects fine-grained thoughts explaining what the next word should be and how it is related to the previous contexts in pre-training texts. Our formulation addresses two fundamental drawbacks of existing next-word prediction learning schemes: they induce factual hallucination and are inefficient for models to learn the implicit reasoning processes in raw texts. While there are many ways to acquire such thoughts of words, we explore the first step of acquiring ToW annotations through distilling from larger models. After continual pre-training with only 70K ToW annotations, we effectively improve models' reasoning performances by 7% to 9% on average and reduce model hallucination by up to 10%. At the same time, ToW is entirely agnostic to tasks and applications, introducing no additional biases on labels or semantics.

[Arxiv](https://arxiv.org/abs/2410.16235)