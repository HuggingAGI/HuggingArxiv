# STAB：语音分词评估基准

发布时间：2024年09月03日

`LLM应用` `语音识别` `人工智能`

> STAB: Speech Tokenizer Assessment Benchmark

# 摘要

> 将语音转化为离散令牌，使其格式接近文本，从而能作为大型语言模型（LLM）的输入。尽管已有多种语音令牌器问世，但关于它们在特定任务中的理想特性和泛化能力仍不明确。评估这些令牌器在不同任务中的表现极具挑战，因其计算量大且难以扩展。为此，我们推出了STAB（语音令牌器评估基准），一个系统框架，旨在全面评估并揭示语音令牌器的内在特性。STAB不仅深化了对语音令牌化机制的理解，还为未来令牌器的发展和标准化比较提供了有力支持。我们通过STAB指标，分析了令牌器在多样语音任务中的表现。

> Representing speech as discrete tokens provides a framework for transforming speech into a format that closely resembles text, thus enabling the use of speech as an input to the widely successful large language models (LLMs). Currently, while several speech tokenizers have been proposed, there is ambiguity regarding the properties that are desired from a tokenizer for specific downstream tasks and its overall generalizability. Evaluating the performance of tokenizers across different downstream tasks is a computationally intensive effort that poses challenges for scalability. To circumvent this requirement, we present STAB (Speech Tokenizer Assessment Benchmark), a systematic evaluation framework designed to assess speech tokenizers comprehensively and shed light on their inherent characteristics. This framework provides a deeper understanding of the underlying mechanisms of speech tokenization, thereby offering a valuable resource for expediting the advancement of future tokenizer models and enabling comparative analysis using a standardized benchmark. We evaluate the STAB metrics and correlate this with downstream task performance across a range of speech tasks and tokenizer choices.

[Arxiv](https://arxiv.org/abs/2409.02384)