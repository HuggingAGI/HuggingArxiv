# DecoPrompt ：当大型语言模型遭遇错误前提时，通过解码提示能够减少幻觉。

发布时间：2024年11月11日

`LLM应用` `语言模型` `提示算法`

> DecoPrompt : Decoding Prompts Reduces Hallucinations when Large Language Models Meet False Premises

# 摘要

> 尽管大型语言模型（LLMs）的能力日益强大，但它们的幻觉输出（偏离事实的陈述）也引发了研究。本文聚焦于一种重要的错误前提情景，即模型虽具备准确回答原始问题的事实知识，却会被不相符的主张干扰。受错误前提提示的熵与引发幻觉生成可能性紧密相关这一发现的启发，我们提出了一种名为 DecoPrompt 的新提示算法来减轻幻觉。DecoPrompt 借助 LLMs 对错误前提提示进行“解码”，而不会真正引发 LLMs 的幻觉输出。我们在两个数据集上开展实验，证明 DecoPrompt 能有效减少不同 LLMs 输出中的幻觉。而且，DecoPrompt 具有跨模型的可迁移性，有助于将其应用于大型 LLMs 或无法获取模型对数等场景。

> While large language models (LLMs) have demonstrated increasing power, they have also called upon studies on their hallucinated outputs that deviate from factually correct statements. In this paper, we focus on one important scenario of false premises, where LLMs are distracted by misaligned claims although the model possesses the required factual knowledge to answer original questions accurately. Inspired by the observation that entropy of the false-premise prompt is closely related to its likelihood to elicit hallucination generation, we propose a new prompting algorithm, named DecoPrompt, to mitigate hallucination. DecoPrompt leverages LLMs to "decode" the false-premise prompts without really eliciting hallucination output from LLMs. We perform experiments on two datasets, demonstrating that DecoPrompt can reduce hallucinations effectively on outputs from different LLMs. Moreover, DecoPrompt exhibits cross-model transferability, which facilitates its applications to scenarios such as LLMs of large sizes or unavailable model logits.

[Arxiv](https://arxiv.org/abs/2411.07457)