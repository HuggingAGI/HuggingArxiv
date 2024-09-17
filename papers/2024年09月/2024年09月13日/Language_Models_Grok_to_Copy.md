# 语言模型“Grok”复制之道

发布时间：2024年09月13日

`LLM理论` `人工智能`

> Language Models "Grok" to Copy

# 摘要

> 我们深入探讨了语言模型在预训练阶段的动态表现，特别关注其从前文复制文本的能力，这是包括ICL和RAG在内的多种LLM应用的基础。我们提出，基于Transformer的模型在复制能力的发展上与grokking现象相似，后者指模型在长时间适应训练集后，突然在测试集上实现泛化。实验结果显示：(1) 预训练损失快速下降，而模型复制能力起初滞后，随后迅速饱和；(2) 复制能力的发展速度与训练token数量无关，与grokking速度类似，不受数据集大小影响，前提是数据分布不变；(3) 负责复制的注意力头（归纳头）在训练中从浅层向深层发展，与grokking期间深层电路的发展相呼应。我们相信，grokking与上下文复制之间的关联能为更有效的语言模型训练提供新视角，从而提升上下文性能。例如，我们发现增强grokking的正则化技术，能有效加速或增强模型对上下文文本的复制能力。

> We examine the pre-training dynamics of language models, focusing on their ability to copy text from preceding context--a fundamental skill for various LLM applications, including in-context learning (ICL) and retrieval-augmented generation (RAG). We propose a novel perspective that Transformer-based language models develop copying abilities similarly to grokking, which refers to sudden generalization on test set long after the model fit to the training set. Our experiments yield three arguments: (1) The pre-training loss decreases rapidly, while the context copying ability of models initially lags and then abruptly saturates. (2) The speed of developing copying ability is independent of the number of tokens trained, similarly to how grokking speed is unaffected by dataset size as long as the data distribution is preserved. (3) Induction heads, the attention heads responsible for copying, form from shallow to deep layers during training, mirroring the development of circuits in deeper layers during grokking. We contend that the connection between grokking and context copying can provide valuable insights for more effective language model training, ultimately improving in-context performance. For example, we demonstrated that techniques that enhance grokking, such as regularization, either accelerate or enhance the development of context copying.

[Arxiv](https://arxiv.org/abs/2409.09281)