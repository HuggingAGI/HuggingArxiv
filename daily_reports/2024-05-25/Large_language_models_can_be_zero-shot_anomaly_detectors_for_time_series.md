# 大型语言模型是否具备零-shot检测时间序列异常的能力？
发布时间：2024年05月23日

`提示工程`
> Large language models can be zero-shot anomaly detectors for time series?
>
> 最新研究表明，大型语言模型不仅能执行时间序列预测等多种任务，还展现出极高的应用灵活性。本文聚焦于一项挑战性任务——时间序列异常检测，探讨了大型语言模型在此领域的应用。该任务要求模型识别输入序列中的异常部分，并处理时间序列数据而非传统文本。我们提出了sigllm框架，通过时间序列到文本的转换和端到端管道，引导语言模型进行异常检测。实验中，我们采用了两种策略：一是直接提示模型识别异常元素，二是利用模型的预测能力辅助检测。在11个多样化的数据集上，预测方法在F1分数上显著优于提示方法。尽管大型语言模型表现出色，但最先进的深度学习模型在性能上仍领先30%。
>
> https://arxiv.org/abs/2405.14755


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14755](https://arxiv.org/abs/2405.14755)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886