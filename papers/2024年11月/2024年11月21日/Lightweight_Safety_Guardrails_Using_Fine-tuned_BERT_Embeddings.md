# 基于微调 BERT 嵌入的轻量级安全防护栏

发布时间：2024年11月21日

`LLM应用` `安全防护`

> Lightweight Safety Guardrails Using Fine-tuned BERT Embeddings

# 摘要

> 随着大型语言模型（LLMs）近来的蓬勃发展，企业能够迅速开展概念验证和原型开发。于是，对落实强有力的防护措施来监测、量化和管控LLM行为的需求愈发迫切，以保障其使用可靠、安全、精准，且符合用户预期。此前，诸如LlamaGuard和OpenAI的MOD API等用于过滤不当用户提示或系统输出的方法，通过微调现有LLMs已大获成功。但将微调后的LLMs用作防护栏会带来更高的延迟和维护成本，对于追求成本效益的部署而言，可能不切实际或难以扩展。我们另辟蹊径，专注于微调轻量级架构：Sentence-BERT。此方法将模型规模从LlamaGuard的70亿参数缩减至约6700万，同时在AEGIS安全基准测试中保持了相近的性能。

> With the recent proliferation of large language models (LLMs), enterprises have been able to rapidly develop proof-of-concepts and prototypes. As a result, there is a growing need to implement robust guardrails that monitor, quantize and control an LLM's behavior, ensuring that the use is reliable, safe, accurate and also aligned with the users' expectations. Previous approaches for filtering out inappropriate user prompts or system outputs, such as LlamaGuard and OpenAI's MOD API, have achieved significant success by fine-tuning existing LLMs. However, using fine-tuned LLMs as guardrails introduces increased latency and higher maintenance costs, which may not be practical or scalable for cost-efficient deployments. We take a different approach, focusing on fine-tuning a lightweight architecture: Sentence-BERT. This method reduces the model size from LlamaGuard's 7 billion parameters to approximately 67 million, while maintaining comparable performance on the AEGIS safety benchmark.

[Arxiv](https://arxiv.org/abs/2411.14398)