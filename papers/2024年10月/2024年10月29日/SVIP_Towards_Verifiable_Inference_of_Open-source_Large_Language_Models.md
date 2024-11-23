# SVIP：致力于实现开源大型语言模型的可验证推理

发布时间：2024年10月29日

`LLM应用` `计算服务`

> SVIP: Towards Verifiable Inference of Open-source Large Language Models

# 摘要

> 开源的大型语言模型（LLMs）近来在自然语言的理解与生成领域展现出了卓越的能力，在众多领域被广泛采用。然而，其日益增大的模型规模致使个人用户难以在本地进行部署，使得许多人不得不通过黑盒 API 依赖计算服务提供商来进行推理。这种依赖带来了新的风险：计算提供商可能会在未获用户同意的情况下，悄悄用规模更小、能力更弱的模型替换所请求的 LLM，从而在节省成本的同时给出质量欠佳的输出。在本文中，我们对 LLM 的可验证推理问题进行了规范化。现有的基于密码学或博弈论技术的可验证计算解决方案，要么计算成本过高，要么基于较强的假设。我们推出了 SVIP，这是一种基于秘密的可验证 LLM 推理协议，它借助 LLM 的中间输出作为独特的模型标识。通过针对这些输出训练一个代理任务，并要求计算提供商同时返回生成的文本和处理后的中间输出，用户能够切实地验证计算提供商是否诚信行事。此外，秘密机制的融入进一步提升了我们协议的安全性。我们在多种强大且自适应的对抗场景下对协议进行了全面分析。大量的实验表明，SVIP 准确、通用、计算高效，且能抵御各类攻击。尤为值得一提的是，SVIP 的假阴性率低于 5%，假阳性率低于 3%，且每次查询的验证时间不足 0.01 秒。

> Open-source Large Language Models (LLMs) have recently demonstrated remarkable capabilities in natural language understanding and generation, leading to widespread adoption across various domains. However, their increasing model sizes render local deployment impractical for individual users, pushing many to rely on computing service providers for inference through a blackbox API. This reliance introduces a new risk: a computing provider may stealthily substitute the requested LLM with a smaller, less capable model without consent from users, thereby delivering inferior outputs while benefiting from cost savings. In this paper, we formalize the problem of verifiable inference for LLMs. Existing verifiable computing solutions based on cryptographic or game-theoretic techniques are either computationally uneconomical or rest on strong assumptions. We introduce SVIP, a secret-based verifiable LLM inference protocol that leverages intermediate outputs from LLM as unique model identifiers. By training a proxy task on these outputs and requiring the computing provider to return both the generated text and the processed intermediate outputs, users can reliably verify whether the computing provider is acting honestly. In addition, the integration of a secret mechanism further enhances the security of our protocol. We thoroughly analyze our protocol under multiple strong and adaptive adversarial scenarios. Our extensive experiments demonstrate that SVIP is accurate, generalizable, computationally efficient, and resistant to various attacks. Notably, SVIP achieves false negative rates below 5% and false positive rates below 3%, while requiring less than 0.01 seconds per query for verification.

[Arxiv](https://arxiv.org/abs/2410.22307)