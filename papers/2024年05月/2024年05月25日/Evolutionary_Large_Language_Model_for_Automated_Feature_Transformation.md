# 进化型大型语言模型：自动化特征转换的新篇章

发布时间：2024年05月25日

`LLM应用

这篇论文介绍了一种结合进化算法的LLM框架，用于自动特征转换，旨在重塑原始特征空间以增强下游模型的性能。该框架利用了LLM在序列理解上的优势，并通过强化学习数据收集器和进化策略来维护和优化多人口数据库。这种方法不仅在广阔的特征空间中实现了高效探索，还推动了特征知识的优化，形成了一个更具适应性的搜索模式。因此，这篇论文属于LLM应用类别，因为它展示了如何将LLM技术应用于特征转换和优化问题中。` `机器学习` `数据挖掘`

> Evolutionary Large Language Model for Automated Feature Transformation

# 摘要

> 特征转换旨在重塑原始特征空间，以增强下游模型的性能。但特征组合与操作的激增构成了挑战，使得现有方法难以高效地探索广阔的特征空间。此外，这些方法的优化仅关注特定领域模型的准确性，忽略了获取通用特征知识的重要性。为此，我们提出了一种结合进化算法的LLM框架，用于自动特征转换。该框架包含两个关键部分：首先，通过强化学习数据收集器构建多人口数据库，并运用进化策略维护数据库；其次，利用LLM在序列理解上的优势，通过少量样本提示引导LLM根据特征转换序列的差异生成高质量样本。借助多人口数据库，我们得以广泛搜索并发现优秀的人口。通过筛选与进化，高质量人口获得更多发展机会，进一步推动了最优个体的追求。通过LLM与进化算法的融合，我们不仅在广阔的特征空间中实现了高效探索，还利用特征知识推动了优化，形成了一个更具适应性的搜索模式。最终，我们的实证研究验证了该方法的有效性与通用性。

> Feature transformation aims to reconstruct the feature space of raw features to enhance the performance of downstream models. However, the exponential growth in the combinations of features and operations poses a challenge, making it difficult for existing methods to efficiently explore a wide space. Additionally, their optimization is solely driven by the accuracy of downstream models in specific domains, neglecting the acquisition of general feature knowledge. To fill this research gap, we propose an evolutionary LLM framework for automated feature transformation. This framework consists of two parts: 1) constructing a multi-population database through an RL data collector while utilizing evolutionary algorithm strategies for database maintenance, and 2) utilizing the ability of Large Language Model (LLM) in sequence understanding, we employ few-shot prompts to guide LLM in generating superior samples based on feature transformation sequence distinction. Leveraging the multi-population database initially provides a wide search scope to discover excellent populations. Through culling and evolution, the high-quality populations are afforded greater opportunities, thereby furthering the pursuit of optimal individuals. Through the integration of LLMs with evolutionary algorithms, we achieve efficient exploration within a vast space, while harnessing feature knowledge to propel optimization, thus realizing a more adaptable search paradigm. Finally, we empirically demonstrate the effectiveness and generality of our proposed method.

![进化型大型语言模型：自动化特征转换的新篇章](../../../paper_images/2405.16203/sequence.png)

![进化型大型语言模型：自动化特征转换的新篇章](../../../paper_images/2405.16203/framework.png)

![进化型大型语言模型：自动化特征转换的新篇章](../../../paper_images/2405.16203/prompt.png)

![进化型大型语言模型：自动化特征转换的新篇章](../../../paper_images/2405.16203/rl.png)

[Arxiv](https://arxiv.org/abs/2405.16203)