# DroidSpeak：增强跨大型语言模型通信

发布时间：2024年11月05日

`Agent` `多智能体系统`

> DroidSpeak: Enhancing Cross-LLM Communication

# 摘要

> 在利用大型语言模型（LLMs）的多智能体系统中，智能体之间的通信传统上依赖于自然语言。这种通信通常包括到目前为止查询的完整上下文，这可能会引入显著的预填充阶段延迟，特别是在长上下文的情况下。 我们引入 DroidSpeak，这是一个新颖的框架，通过利用中间数据的重用，如输入嵌入（E-cache）和键值缓存（KV-cache）来针对这种跨 LLM 通信。我们有效地绕过了对相同基础模型的微调版本重新处理整个上下文的需要。这种方法允许更快的上下文集成，同时保持任务性能的质量。实验评估表明 DroidSpeak 能够显著加速智能体间的通信，在预填充延迟方面实现高达 2.78 倍的加速，且精度损失可忽略不计。我们的发现强调了创建更高效和可扩展的多智能体系统的潜力。

> In multi-agent systems utilizing Large Language Models (LLMs), communication between agents traditionally relies on natural language. This communication often includes the full context of the query so far, which can introduce significant prefill-phase latency, especially with long contexts.
  We introduce DroidSpeak, a novel framework to target this cross-LLM communication by leveraging the reuse of intermediate data, such as input embeddings (E-cache) and key-value caches (KV-cache). We efficiently bypass the need to reprocess entire contexts for fine-tuned versions of the same foundational model. This approach allows faster context integration while maintaining the quality of task performance. Experimental evaluations demonstrate DroidSpeak's ability to significantly accelerate inter-agent communication, achieving up to a 2.78x speedup in prefill latency with negligible loss in accuracy. Our findings underscore the potential to create more efficient and scalable multi-agent systems.

[Arxiv](https://arxiv.org/abs/2411.02820)