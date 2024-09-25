# 让文本嵌入器变身少样本学习高手

发布时间：2024年09月23日

`LLM应用` `机器学习`

> Making Text Embedders Few-Shot Learners

# 摘要

> 仅解码器架构的 LLM 展现了强大的 ICL 能力，能通过输入上下文中的示例处理各种任务。我们利用这一特性，提出了一种名为 bge-en-icl 的新模型，通过少量示例生成高质量文本嵌入。该模型将任务示例直接融入查询，显著提升了多任务表现。我们还探讨了如何优化 LLM 作为嵌入模型，发现保持简单框架往往效果最佳。实验证明，我们的方法在 MTEB 和 AIR-Bench 基准测试中创下新纪录。所有资源均可免费访问：https://github.com/FlagOpen/FlagEmbedding。

> Large language models (LLMs) with decoder-only architectures demonstrate remarkable in-context learning (ICL) capabilities. This feature enables them to effectively handle both familiar and novel tasks by utilizing examples provided within their input context. Recognizing the potential of this capability, we propose leveraging the ICL feature in LLMs to enhance the process of text embedding generation. To this end, we introduce a novel model bge-en-icl, which employs few-shot examples to produce high-quality text embeddings. Our approach integrates task-related examples directly into the query side, resulting in significant improvements across various tasks. Additionally, we have investigated how to effectively utilize LLMs as embedding models, including various attention mechanisms, pooling methods, etc. Our findings suggest that retaining the original framework often yields the best results, underscoring that simplicity is best. Experimental results on the MTEB and AIR-Bench benchmarks demonstrate that our approach sets new state-of-the-art (SOTA) performance. Our model, code and dataset are freely available at https://github.com/FlagOpen/FlagEmbedding .

[Arxiv](https://arxiv.org/abs/2409.15700)