# 深入探讨大语言模型中的覆盖标准：基于越狱攻击的详尽研究

发布时间：2024年08月27日

`LLM应用` `人工智能` `网络安全`

> Investigating Coverage Criteria in Large Language Models: An In-Depth Study Through Jailbreak Attacks

# 摘要

> 大型语言模型的快速发展深刻影响了人工智能领域，但其在敏感领域的应用因易受恶意利用而引发严重担忧。这凸显了现有部署前测试的不足，迫切需要更严格的评估方法。本研究通过全面实证分析，评估了传统覆盖标准在识别漏洞方面的有效性，特别关注越狱攻击。我们首先对模型隐藏状态进行聚类分析，发现这些状态的内在特征能有效区分不同查询类型。接着，我们在标准、层级和令牌三个维度评估这些标准的表现，发现正常与越狱查询间神经元激活模式存在显著差异。基于此，我们提出一种利用神经激活特征实时检测越狱攻击的新方法，分类器准确率高达96.33%，包括可能引发对抗性攻击的查询。本研究通过全面应对LLM安全挑战，为未来集成LLM的系统提供实时检测能力，推进了LLM安全测试的理解，并为构建更健壮的AI系统奠定基础。

> The swift advancement of large language models (LLMs) has profoundly shaped the landscape of artificial intelligence; however, their deployment in sensitive domains raises grave concerns, particularly due to their susceptibility to malicious exploitation. This situation underscores the insufficiencies in pre-deployment testing, highlighting the urgent need for more rigorous and comprehensive evaluation methods. This study presents a comprehensive empirical analysis assessing the efficacy of conventional coverage criteria in identifying these vulnerabilities, with a particular emphasis on the pressing issue of jailbreak attacks. Our investigation begins with a clustering analysis of the hidden states in LLMs, demonstrating that intrinsic characteristics of these states can distinctly differentiate between various types of queries. Subsequently, we assess the performance of these criteria across three critical dimensions: criterion level, layer level, and token level. Our findings uncover significant disparities in neuron activation patterns between the processing of normal and jailbreak queries, thereby corroborating the clustering results. Leveraging these findings, we propose an innovative approach for the real-time detection of jailbreak attacks by utilizing neural activation features. Our classifier demonstrates remarkable accuracy, averaging 96.33% in identifying jailbreak queries, including those that could lead to adversarial attacks. The importance of our research lies in its comprehensive approach to addressing the intricate challenges of LLM security. By enabling instantaneous detection from the model's first token output, our method holds promise for future systems integrating LLMs, offering robust real-time detection capabilities. This study advances our understanding of LLM security testing, and lays a critical foundation for the development of more resilient AI systems.

[Arxiv](https://arxiv.org/abs/2408.15207)