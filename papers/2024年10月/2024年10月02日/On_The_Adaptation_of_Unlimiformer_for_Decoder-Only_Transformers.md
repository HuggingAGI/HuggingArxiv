# 探讨 Unlimiformer 在仅解码器 Transformer 中的适应性

发布时间：2024年10月02日

`LLM应用` `人工智能`

> On The Adaptation of Unlimiformer for Decoder-Only Transformers

# 摘要

> 当前大型语言模型面临的主要问题是上下文长度有限。尽管 GPT-4 和 Claude 2 等专有模型已引入更长的上下文，但大多数常见模型如 LLama-2 的上下文长度仍不超过 4k。Unlimiformer 是一种向量检索增强方法，但其与仅解码器变压器不兼容。我们在此基础上进行了改进，使其适应仅解码器变压器，并扩展了实验范围，包括自由形式问答和自定义 GPT 模型。实验结果表明，改进后的方法在总结任务中表现出色，与上下文长度为 2 倍的模型相当。此外，我们还探讨了自由形式问答和指令调优模型的未来发展方向。

> One of the prominent issues stifling the current generation of large language models is their limited context length. Recent proprietary models such as GPT-4 and Claude 2 have introduced longer context lengths, 8k/32k and 100k, respectively; however, despite the efforts in the community, most common models, such as LLama-2, have a context length of 4k or less. Unlimiformer (Bertsch et al., 2023) is a recently popular vector-retrieval augmentation method that offloads cross-attention computations to a kNN index. However, its main limitation is incompatibility with decoder-only transformers out of the box. In this work, we explore practical considerations of adapting Unlimiformer to decoder-only transformers and introduce a series of modifications to overcome this limitation. Moreover, we expand the original experimental setup on summarization to include a new task (i.e., free-form Q&A) and an instruction-tuned model (i.e., a custom 6.7B GPT model). Our results showcase the effectiveness of these modifications on summarization, performing on par with a model with 2x the context length. Moreover, we discuss limitations and future directions for free-form Q&A and instruction-tuned models.

[Arxiv](https://arxiv.org/abs/2410.01637)