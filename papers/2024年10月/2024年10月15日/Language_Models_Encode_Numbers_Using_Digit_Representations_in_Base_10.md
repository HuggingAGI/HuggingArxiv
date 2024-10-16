# 语言模型通过十进制数字表示来编码数字

发布时间：2024年10月15日

`LLM理论` `人工智能` `数值计算`

> Language Models Encode Numbers Using Digit Representations in Base 10

# 摘要

> 大型语言模型（LLM）在处理简单数值问题时也常犯错，如比较小数。我们推测，这些错误源于 LLM 的数字表示方式，特别是其是否准确捕捉数值。通过观察 LLM 在数值任务中的错误分布，我们发现这些错误常集中在答案的数字上，而非数值本身。经过一系列实验和干预，我们揭示了 LLM 内部采用每位数字的独立循环表示来处理十进制数字。这种按位表示方式，不同于传统的数值表示，有助于解释模型在数值推理任务中的错误模式，并为未来研究 LLM 的数值机制提供了新视角。

> Large language models (LLMs) frequently make errors when handling even simple numerical problems, such as comparing two small numbers. A natural hypothesis is that these errors stem from how LLMs represent numbers, and specifically, whether their representations of numbers capture their numeric values. We tackle this question from the observation that LLM errors on numerical tasks are often distributed across \textit{the digits} of the answer rather than normally around \textit{its numeric value}. Through a series of probing experiments and causal interventions, we show that LLMs internally represent numbers with individual circular representations per-digit in base 10. This digit-wise representation, as opposed to a value representation, sheds light on the error patterns of models on tasks involving numerical reasoning and could serve as a basis for future studies on analyzing numerical mechanisms in LLMs.

[Arxiv](https://arxiv.org/abs/2410.11781)