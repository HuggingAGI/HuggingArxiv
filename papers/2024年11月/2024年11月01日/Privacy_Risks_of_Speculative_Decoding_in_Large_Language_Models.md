# 大型语言模型里推测解码存在的隐私风险

发布时间：2024年11月01日

`LLM应用` `语言模型` `隐私保护`

> Privacy Risks of Speculative Decoding in Large Language Models

# 摘要

> 在大型语言模型（LLMs）中，推测解码能通过低价地推测性预测多个令牌并并行验证，从而加快令牌生成，且已得到广泛应用。在本文中，我们首次研究并揭示了推测解码存在的隐私风险。我们发现，与输入相关的正确和错误预测模式可能会被监测令牌生成时间和数据包大小的对手获取，进而造成隐私泄露。观察正确和错误的推测令牌模式可知，恶意对手能够对查询进行指纹识别，并在三种不同的推测解码技术（BiLD 准确率近乎 100%、LADE 准确率高达 92%、REST 准确率高达 95%）下，以超过 90%的准确率获取私人用户输入。我们还指出，对手甚至能够泄露用于设计这些技术的机密知识产权，比如 REST 中用于预测的数据存储中的数据，每秒超过 25 个令牌，或者 LADE 中用于预测的超参数。此外，我们还探讨了缓解策略，比如在多个迭代中聚合令牌以及用额外字节填充数据包，以防止此类隐私或机密性的泄露。

> Speculative decoding in large language models (LLMs) accelerates token generation by speculatively predicting multiple tokens cheaply and verifying them in parallel, and has been widely deployed. In this paper, we provide the first study demonstrating the privacy risks of speculative decoding. We observe that input-dependent patterns of correct and incorrect predictions can be leaked out to an adversary monitoring token generation times and packet sizes, leading to privacy breaches. By observing the pattern of correctly and incorrectly speculated tokens, we show that a malicious adversary can fingerprint queries and learn private user inputs with more than $90\%$ accuracy across three different speculative decoding techniques - BiLD (almost $100\%$ accuracy), LADE (up to $92\%$ accuracy), and REST (up to $95\%$ accuracy). We show that an adversary can also leak out confidential intellectual property used to design these techniques, such as data from data-stores used for prediction (in REST) at a rate of more than $25$ tokens per second, or even hyper-parameters used for prediction (in LADE). We also discuss mitigation strategies, such as aggregating tokens across multiple iterations and padding packets with additional bytes, to avoid such privacy or confidentiality breaches.

[Arxiv](https://arxiv.org/abs/2411.01076)