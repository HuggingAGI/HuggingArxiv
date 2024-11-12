# 大型语言模型的准随机多样本推理

发布时间：2024年11月09日

`LLM应用` `机器翻译`

> Quasi-random Multi-Sample Inference for Large Language Models

# 摘要

> 大型语言模型（LLMs）通常配备多样本解码策略。LLM 隐式地定义了一个算术码本，有助于高效且极易并行化的	extbf{算术采样}，使用准随机码生成多个样本。传统的文本生成方法，如束搜索和基于采样的技术，具有显著的局限性：它们缺乏并行化能力或采样序列的多样性。本研究探索了算术采样的潜力，将其与在两个采用多样本推理的解码任务中的祖先采样进行对比：具有自洽性的思维链推理和具有最小贝叶斯风险解码的机器翻译。我们的结果表明，随着样本大小的增加，算术采样产生了更多样化的样本，显著提高了推理和翻译性能。在 GSM8K 数据集上，我们观察到准确率提高了\mathbf{3 - 5\%}，对于 WMT19 任务，使用算术采样在 COMET 分数上提高了\mathbf{0.45 - 0.89\%}，且没有任何显著的计算开销。

> Large language models (LLMs) are often equipped with multi-sample decoding strategies. An LLM implicitly defines an arithmetic code book, facilitating efficient and embarrassingly parallelizable \textbf{arithmetic sampling} to produce multiple samples using quasi-random codes. Traditional text generation methods, such as beam search and sampling-based techniques, have notable limitations: they lack parallelizability or diversity of sampled sequences. This study explores the potential of arithmetic sampling, contrasting it with ancestral sampling across two decoding tasks that employ multi-sample inference: chain-of-thought reasoning with self-consistency and machine translation with minimum Bayes risk decoding. Our results demonstrate that arithmetic sampling produces more diverse samples, significantly improving reasoning and translation performance as the sample size increases. We observe a $\mathbf{3\text{-}5\%}$ point increase in accuracy on the GSM8K dataset and a $\mathbf{0.45\text{-}0.89\%}$ point increment in COMET score for WMT19 tasks using arithmetic sampling without any significant computational overhead.

[Arxiv](https://arxiv.org/abs/2411.06251)