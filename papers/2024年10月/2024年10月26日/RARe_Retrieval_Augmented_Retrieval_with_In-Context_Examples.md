# RARe：具有上下文示例的检索增强式检索

发布时间：2024年10月26日

`LLM应用` `语言模型`

> RARe: Retrieval Augmented Retrieval with In-Context Examples

# 摘要

> 我们探究在仅解码器语言模型（LLMs）中被广泛运用的上下文示例，能否提升检索任务中嵌入模型的性能。和在 LLMs 中的情况不同，在推理时直接把上下文示例（查询 - 文档对）添加到目标查询前，无法直接生效。我们提出了一种简便的方法，让检索器能够运用上下文示例。我们的方法 RARe，用与目标查询语义相近的上下文示例对预训练模型进行微调。这能应用于适配各种基础架构（比如仅解码器语言模型、检索器模型），在各种开放域检索数据集（BeIR、RAR-b）中持续实现高达 +2.72％ nDCG 的性能增益。特别是，我们发现相较于使用不含上下文示例查询的模型，RARe 展现出更强的域外泛化能力，这和 LLMs 中的上下文学习相似。我们进一步对上下文示例扩充的设计选择加以分析，为该领域的未来工作筑牢根基。

> We investigate whether in-context examples, widely used in decoder-only language models (LLMs), can improve embedding model performance in retrieval tasks. Unlike in LLMs, naively prepending in-context examples (query-document pairs) to the target query at inference time does not work out of the box. We introduce a simple approach to enable retrievers to use in-context examples. Our approach, RARe, finetunes a pre-trained model with in-context examples whose query is semantically similar to the target query. This can be applied to adapt various base architectures (i.e., decoder-only language models, retriever models) and consistently achieves performance gains of up to +2.72% nDCG across various open-domain retrieval datasets (BeIR, RAR-b). In particular, we find RARe exhibits stronger out-of-domain generalization compared to models using queries without in-context examples, similar to what is seen for in-context learning in LLMs. We further provide analysis on the design choices of in-context example augmentation and lay the foundation for future work in this space.

[Arxiv](https://arxiv.org/abs/2410.20088)