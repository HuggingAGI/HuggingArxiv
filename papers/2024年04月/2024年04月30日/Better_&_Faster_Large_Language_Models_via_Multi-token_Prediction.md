# 通过多令牌预测技术，我们能够打造性能更优、响应更迅速的大型语言模型。

发布时间：2024年04月30日

`LLM理论`

> Better & Faster Large Language Models via Multi-token Prediction

# 摘要

> 诸如 GPT 和 Llama 这样的大型语言模型通常通过预测下一个词元来进行训练。本研究提出，让模型同时预测多个后续词元可以提升样本效率。具体来说，训练时，模型需在语料库的每个点预测接下来的 n 个词元，通过 n 个独立的输出头实现，这些输出头共同作用于一个共享的模型主体。将这种多词元预测作为辅助训练手段，我们在不增加训练时长的前提下，对代码和自然语言模型的下游性能进行了提升。这种方法对于大型模型尤为有效，且在多轮训练中同样适用。特别是在编程等生成任务中，我们的模型在性能上显著超越了传统基线模型。以 13B 参数模型为例，其在 HumanEval 和 MBPP 测试中解决问题的能力分别提升了 12% 和 17%。此外，多词元预测还有助于提升模型的归纳和算法推理能力。另一个优势是，经过 4 词元预测训练的模型在推理时速度更快，速度提升高达 3 倍，即便在处理大规模数据批次时也是如此。

> Large language models such as GPT and Llama are trained with a next-token prediction loss. In this work, we suggest that training language models to predict multiple future tokens at once results in higher sample efficiency. More specifically, at each position in the training corpus, we ask the model to predict the following n tokens using n independent output heads, operating on top of a shared model trunk. Considering multi-token prediction as an auxiliary training task, we measure improved downstream capabilities with no overhead in training time for both code and natural language models. The method is increasingly useful for larger model sizes, and keeps its appeal when training for multiple epochs. Gains are especially pronounced on generative benchmarks like coding, where our models consistently outperform strong baselines by several percentage points. Our 13B parameter models solves 12 % more problems on HumanEval and 17 % more on MBPP than comparable next-token models. Experiments on small algorithmic tasks demonstrate that multi-token prediction is favorable for the development of induction heads and algorithmic reasoning capabilities. As an additional benefit, models trained with 4-token prediction are up to 3 times faster at inference, even with large batch sizes.

[Arxiv](https://arxiv.org/abs/2404.19737)