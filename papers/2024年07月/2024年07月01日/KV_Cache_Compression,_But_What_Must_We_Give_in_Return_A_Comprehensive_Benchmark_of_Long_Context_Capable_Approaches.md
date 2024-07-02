# KV缓存压缩：我们需付出何种代价？长上下文能力方法的全面基准测试

发布时间：2024年07月01日

`LLM理论` `软件开发` `人工智能`

> KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches

# 摘要

> 大型语言模型（LLM）的长上下文能力至关重要，它减轻了人类阅读长篇文本的负担，使得书籍摘要、代码辅助等复杂任务成为可能。然而，基于transformer的LLM在处理长上下文时面临挑战，如KV缓存膨胀和输入处理的复杂性。为此，业界提出了多种高效方法，如KV缓存量化和混合架构，以提升模型性能。尽管如此，这些方法尚未在统一环境中得到全面评估。本研究填补了这一空白，通过分类法评估了七大类长上下文任务的10多种前沿方法，揭示了新现象，并为未来LLM的发展提供了见解和工作平台。源代码将在GitHub上公开。

> Long context capability is a crucial competency for large language models (LLMs) as it mitigates the human struggle to digest long-form texts. This capability enables complex task-solving scenarios such as book summarization, code assistance, and many more tasks that are traditionally manpower-intensive. However, transformer-based LLMs face significant challenges with long context input due to the growing size of the KV cache and the intrinsic complexity of attending to extended inputs; where multiple schools of efficiency-driven approaches -- such as KV cache quantization, token dropping, prompt compression, linear-time sequence models, and hybrid architectures -- have been proposed to produce efficient yet long context-capable models. Despite these advancements, no existing work has comprehensively benchmarked these methods in a reasonably aligned environment. In this work, we fill this gap by providing a taxonomy of current methods and evaluating 10+ state-of-the-art approaches across seven categories of long context tasks. Our work reveals numerous previously unknown phenomena and offers insights -- as well as a friendly workbench -- for the future development of long context-capable LLMs. The source code will be available at https://github.com/henryzhongsc/longctx_bench

[Arxiv](https://arxiv.org/abs/2407.01527)