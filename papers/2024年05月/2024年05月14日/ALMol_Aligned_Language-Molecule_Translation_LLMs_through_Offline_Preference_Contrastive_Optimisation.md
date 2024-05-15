# ALMol：借助离线偏好对比优化，实现语言与分子间精准翻译的大型语言模型

发布时间：2024年05月14日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在化学领域的应用，特别是在机器语言与分子间的翻译方面。它提出了一种创新的对比偏好优化训练策略，旨在提高模型的训练效率和泛化能力，同时减少对庞大模型和数据集的依赖。此外，论文还开发了一种可扩展的细粒度评估方法，以确保评估的责任性。这些内容涉及LLMs的理论和方法论改进，因此属于LLM理论分类。` `人工智能`

> ALMol: Aligned Language-Molecule Translation LLMs through Offline Preference Contrastive Optimisation

# 摘要

> 化学与AI的交汇点正成为加速科学发现的热点研究领域。LLMs与科学模式的融合展现出巨大潜力。尽管如此，训练效率和分布外问题仍是待解难题，尤其是当前方法依赖于庞大的模型和数据集。我们聚焦于机器语言与分子间的翻译，并采用了一种创新的对比偏好优化训练策略，旨在避免仅产生足够而非完美的翻译。为了提升模型的泛化能力并减少记忆效应，我们仅用10%的数据进行实验，结果显示我们的模型性能提升了高达32%。此外，我们还开发了一种可扩展的细粒度评估方法，确保了评估的责任性。

> The field of chemistry and Artificial Intelligence (AI) intersection is an area of active research that aims to accelerate scientific discovery. The integration of large language models (LLMs) with scientific modalities has shown significant promise in this endeavour. However, challenges persist in effectively addressing training efficacy and the out-of-distribution problem, particularly as existing approaches rely on larger models and datasets. In this context, we focus on machine language-molecule translation and deploy a novel training approach called contrastive preference optimisation, which avoids generating translations that are merely adequate but not perfect. To ensure generalisability and mitigate memorisation effects, we conduct experiments using only 10\% of the data. Our results demonstrate that our models achieve up to a 32\% improvement compared to counterpart models. We also introduce a scalable fine-grained evaluation methodology that accommodates responsibility.

[Arxiv](https://arxiv.org/abs/2405.08619)