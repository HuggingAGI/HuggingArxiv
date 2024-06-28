# 利用大型语言模型对休闲对话的ASR N最佳假设进行重评分：探讨领域适应与上下文传递的影响

发布时间：2024年06月27日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在自动语音识别（ASR）中的应用，特别是在非正式对话场景下的重评分能力。通过使用Llama2模型在CHiME-7远场ASR任务上对N-最佳ASR假设进行重评分，研究了领域适应和上下文传递对LLM性能的影响。这表明LLMs在特定应用场景下的潜力和优化方向，属于LLM应用的范畴。` `自动语音识别` `对话系统`

> Applying LLMs for Rescoring N-best ASR Hypotheses of Casual Conversations: Effects of Domain Adaptation and Context Carry-over

# 摘要

> 大型语言模型（LLMs）在自动语音识别（ASR）假设的重评分方面已取得成功应用，但其在非正式对话场景下的重评分能力仍未被充分挖掘。本研究通过在CHiME-7远场ASR任务上运用Llama2对N-最佳ASR假设进行重评分，揭示了这一潜力。Llama2作为顶尖的LLMs之一，而CHiME-7 DASR任务则提供了多人非正式对话的数据集。我们探讨了领域适应和上下文传递对LLM在N-最佳重评分中的影响。实验结果显示，即便未经领域适应，Llama2在长上下文使用时仍超越了标准大小的领域适应Transformer-LM。领域适应不仅提升了Llama2的性能，还减少了其所需的上下文长度，从而降低了计算成本。

> Large language models (LLMs) have been successfully applied for rescoring automatic speech recognition (ASR) hypotheses. However, their ability to rescore ASR hypotheses of casual conversations has not been sufficiently explored. In this study, we reveal it by performing N-best ASR hypotheses rescoring using Llama2 on the CHiME-7 distant ASR (DASR) task. Llama2 is one of the most representative LLMs, and the CHiME-7 DASR task provides datasets of casual conversations between multiple participants. We investigate the effects of domain adaptation of the LLM and context carry-over when performing N-best rescoring. Experimental results show that, even without domain adaptation, Llama2 outperforms a standard-size domain-adapted Transformer-LM, especially when using a long context. Domain adaptation shortens the context length needed with Llama2 to achieve its best performance, i.e., it reduces the computational cost of Llama2.

[Arxiv](https://arxiv.org/abs/2406.18972)