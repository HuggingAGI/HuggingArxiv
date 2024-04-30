# 在语言模型中进行真值判断时，信仰的方向会随着上下文的不同而变化。

发布时间：2024年04月29日

`LLM理论` `人工智能`

> Truth-value judgment in language models: belief directions are context sensitive

# 摘要

> 最新研究揭示，大型语言模型（LLM）的潜在空间内蕴含着能预示句子真伪的趋势。多种技术成功复原出这些趋势，并打造出了能够触及模型“知识库”或“信仰体系”的探测工具。本研究深入探讨了这一现象，特别关注了上下文对这些探测工具的影响。实验结果明确了在LLM中，探测预测是如何以前文（相关）句子为条件的。我们具体衡量了探测工具对于存在（或否定）的支持性与反驳性句子的敏感度，并对其一致性进行了评分。此外，通过因果干预实验，我们探究了沿着信仰方向移动前提表示是否会改变假设在同一方向上的位置。研究发现，尽管测试的探测工具普遍对上下文有所反应，但本不应影响真实性的上下文却仍能影响探测结果。实验还指出，错误类型的产生与模型的层次、类型及数据种类息息相关。最终，研究结果暗示信念方向可能是推理过程中整合上下文信息的关键因果因素之一。

> Recent work has demonstrated that the latent spaces of large language models (LLMs) contain directions predictive of the truth of sentences. Multiple methods recover such directions and build probes that are described as getting at a model's "knowledge" or "beliefs". We investigate this phenomenon, looking closely at the impact of context on the probes. Our experiments establish where in the LLM the probe's predictions can be described as being conditional on the preceding (related) sentences. Specifically, we quantify the responsiveness of the probes to the presence of (negated) supporting and contradicting sentences, and score the probes on their consistency. We also perform a causal intervention experiment, investigating whether moving the representation of a premise along these belief directions influences the position of the hypothesis along that same direction. We find that the probes we test are generally context sensitive, but that contexts which should not affect the truth often still impact the probe outputs. Our experiments show that the type of errors depend on the layer, the (type of) model, and the kind of data. Finally, our results suggest that belief directions are (one of the) causal mediators in the inference process that incorporates in-context information.

[Arxiv](https://arxiv.org/abs/2404.18865)