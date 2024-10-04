# 隐秘检索中毒的自然对抗文档的精准生成

发布时间：2024年10月02日

`RAG` `网络安全` `人工智能`

> Controlled Generation of Natural Adversarial Documents for Stealthy Retrieval Poisoning

# 摘要

> 最新研究发现，基于嵌入相似性的检索系统（如检索增强生成）易受中毒攻击。恶意文档能响应广泛查询被检索。我们发现，以往基于 HotFlip 的技术生成的文档极易通过困惑度过滤检测。即便生成低困惑度文本，LLM 仍能识别其不自然，自动过滤。我们设计并实现了一种新受控生成技术，结合对抗性目标与基于开源代理 LLM 的“自然性”目标。生成的对抗性文档（1）难以自动检测，除非付出高误报代价，（2）毒性效果与 HotFlip 生成文档相当，（3）在能量引导生成方面显著优于 COLD 等先前方法。

> Recent work showed that retrieval based on embedding similarity (e.g., for retrieval-augmented generation) is vulnerable to poisoning: an adversary can craft malicious documents that are retrieved in response to broad classes of queries. We demonstrate that previous, HotFlip-based techniques produce documents that are very easy to detect using perplexity filtering. Even if generation is constrained to produce low-perplexity text, the resulting documents are recognized as unnatural by LLMs and can be automatically filtered from the retrieval corpus.
  We design, implement, and evaluate a new controlled generation technique that combines an adversarial objective (embedding similarity) with a "naturalness" objective based on soft scores computed using an open-source, surrogate LLM. The resulting adversarial documents (1) cannot be automatically detected using perplexity filtering and/or other LLMs, except at the cost of significant false positives in the retrieval corpus, yet (2) achieve similar poisoning efficacy to easily-detectable documents generated using HotFlip, and (3) are significantly more effective than prior methods for energy-guided generation, such as COLD.

[Arxiv](https://arxiv.org/abs/2410.02163)