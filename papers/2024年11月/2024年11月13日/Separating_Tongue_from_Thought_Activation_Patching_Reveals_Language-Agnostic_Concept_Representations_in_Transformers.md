# 将舌头与思想分离：激活修补揭示了 Transformer 中的语言无关概念表示

发布时间：2024年11月13日

`LLM理论` `语言建模`

> Separating Tongue from Thought: Activation Patching Reveals Language-Agnostic Concept Representations in Transformers

# 摘要

> 在多语言语言建模中，一个核心问题是大型语言模型（LLMs）是否形成了一种与特定语言分离的通用概念表示。在本文中，我们通过分析基于 Transformer 的 LLMs 在单词翻译任务中的潜在表示（latents）来解决这个问题。我们策略性地从源翻译提示中提取潜在表示，并将其插入到目标翻译提示的前向传递中。通过这样做，我们发现输出语言在比要翻译的概念更早的层中被编码在潜在表示中。基于这一见解，我们进行了两个关键实验。首先，我们证明仅通过激活修补就可以在不改变语言的情况下改变概念，反之亦然。其次，我们表明，用不同语言的潜在表示的平均值进行修补不会损害，反而会提高模型在翻译概念方面的性能。我们的结果为所研究的模型中存在与语言无关的概念表示提供了证据。

> A central question in multilingual language modeling is whether large language models (LLMs) develop a universal concept representation, disentangled from specific languages. In this paper, we address this question by analyzing latent representations (latents) during a word translation task in transformer-based LLMs. We strategically extract latents from a source translation prompt and insert them into the forward pass on a target translation prompt. By doing so, we find that the output language is encoded in the latent at an earlier layer than the concept to be translated. Building on this insight, we conduct two key experiments. First, we demonstrate that we can change the concept without changing the language and vice versa through activation patching alone. Second, we show that patching with the mean over latents across different languages does not impair and instead improves the models' performance in translating the concept. Our results provide evidence for the existence of language-agnostic concept representations within the investigated models.

[Arxiv](https://arxiv.org/abs/2411.08745)