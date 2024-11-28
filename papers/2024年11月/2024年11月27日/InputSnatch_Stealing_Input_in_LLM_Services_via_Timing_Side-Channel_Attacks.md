# InputSnatch：借定时侧信道攻击于 LLM 服务里窃取输入

发布时间：2024年11月27日

`LLM应用`

> InputSnatch: Stealing Input in LLM Services via Timing Side-Channel Attacks

# 摘要

> 大型语言模型（LLMs）具备丰富的知识和出色的问答能力，已在金融、医疗咨询等隐私敏感领域广泛应用。在 LLM 推理过程中，常通过缓存共享的方式，对相同或相似的推理请求复用缓存状态或响应，以提升效率。但我们注意到，这些缓存机制存在私人输入泄露的风险，因为缓存会导致响应时间出现可观测的变化，这使其很可能成为基于时间的攻击线索。本研究中，我们提出了一种新型的基于时间的侧信道攻击，用于在 LLM 推理中窃取输入。基于缓存的攻击面临在大搜索空间构建候选输入以命中并窃取缓存用户查询的难题。为应对这些挑战，我们提出了两个主要部分。输入构造器运用机器学习技术和基于 LLM 的方法进行词汇相关性学习，并为通用输入构建实施优化的搜索机制。时间分析器通过具有异常值剔除的统计时间拟合来识别缓存命中模式，持续为构造器的搜索策略提供反馈改进。我们在两种缓存机制上开展实验，结果显示，我们的方法在各类应用中均能持续取得高攻击成功率。我们的工作凸显了与性能优化相关的安全漏洞，强调了在 LLM 推理提升的同时，优先考虑隐私和安全的重要性。

> Large language models (LLMs) possess extensive knowledge and question-answering capabilities, having been widely deployed in privacy-sensitive domains like finance and medical consultation. During LLM inferences, cache-sharing methods are commonly employed to enhance efficiency by reusing cached states or responses for the same or similar inference requests. However, we identify that these cache mechanisms pose a risk of private input leakage, as the caching can result in observable variations in response times, making them a strong candidate for a timing-based attack hint. In this study, we propose a novel timing-based side-channel attack to execute input theft in LLMs inference. The cache-based attack faces the challenge of constructing candidate inputs in a large search space to hit and steal cached user queries. To address these challenges, we propose two primary components. The input constructor employs machine learning techniques and LLM-based approaches for vocabulary correlation learning while implementing optimized search mechanisms for generalized input construction. The time analyzer implements statistical time fitting with outlier elimination to identify cache hit patterns, continuously providing feedback to refine the constructor's search strategy. We conduct experiments across two cache mechanisms and the results demonstrate that our approach consistently attains high attack success rates in various applications. Our work highlights the security vulnerabilities associated with performance optimizations, underscoring the necessity of prioritizing privacy and security alongside enhancements in LLM inference.

[Arxiv](https://arxiv.org/abs/2411.18191)