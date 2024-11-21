# 深入探究高效推理方法：关于推测解码的调研

发布时间：2024年11月20日

`LLM应用` `语言模型`

> Closer Look at Efficient Inference Methods: A Survey of Speculative Decoding

# 摘要

> 随着大型语言模型（LLMs）的规模和复杂性不断增大，高效推理已成为关键焦点。传统的自回归解码虽有效，但因其顺序生成令牌的过程存在计算效率低的问题。推测解码通过引入起草和验证的两阶段框架来解决此瓶颈。由较小且高效的模型生成初步草案，再由更大、更复杂的模型进行完善。本文对推测解码方法展开全面调研，将其分为以草案为中心和以模型为中心两类方法。我们探讨了每种方法的关键思路，突出了它们在扩展 LLM 推理方面的潜力。此次调研旨在为未来优化推测解码及其融入实际 LLM 应用的研究提供指导。

> Efficient inference in large language models (LLMs) has become a critical focus as their scale and complexity grow. Traditional autoregressive decoding, while effective, suffers from computational inefficiencies due to its sequential token generation process. Speculative decoding addresses this bottleneck by introducing a two-stage framework: drafting and verification. A smaller, efficient model generates a preliminary draft, which is then refined by a larger, more sophisticated model. This paper provides a comprehensive survey of speculative decoding methods, categorizing them into draft-centric and model-centric approaches. We discuss key ideas associated with each method, highlighting their potential for scaling LLM inference. This survey aims to guide future research in optimizing speculative decoding and its integration into real-world LLM applications.

[Arxiv](https://arxiv.org/abs/2411.13157)