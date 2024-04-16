# 你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。

发布时间：2024年04月10日

`LLM理论` `知识更新` `动态基准测试`

> Is Your LLM Outdated? Benchmarking LLMs & Alignment Algorithms for Time-Sensitive Knowledge

# 摘要

> 本研究探讨了大型语言模型（LLMs）作为知识库的适宜性，特别是针对如何及时更新LLMs中的事实知识这一难题。鉴于目前鲜有研究关注LLMs内过时知识的识别，我们构建了一个动态基准测试，为每个相关事实问题提供最新的正确答案。我们对十八个顶尖的开源及闭源LLMs进行了评估，这些模型能够实时从Wikidata获取与政治、体育和组织相关的时间敏感知识。同时，我们分析了模型在预训练和微调阶段所掌握信息的时效性。此外，我们还检验了各种知识编辑方法在更新LLMs知识以符合最新事实方面的有效性，并将其与检索增强生成技术的性能进行了对比。这个动态基准测试不仅可直接用来衡量LLMs的知识更新程度，还可通过分享代码、数据集及评估、可视化工具，扩展应用于其他领域。

> We study the appropriateness of Large Language Models (LLMs) as knowledge repositories. We focus on the challenge of maintaining LLMs' factual knowledge up-to-date over time. Motivated by the lack of studies on identifying outdated knowledge within LLMs, we design and develop a dynamic benchmark with up-to-date ground truth answers for each target factual question. We evaluate eighteen open-source and closed-source state-of-the-art LLMs on time-sensitive knowledge retrieved in real-time from Wikidata. We select time-sensitive domain facts in politics, sports, and organizations, and estimate the recency of the information learned by the model during pre-training\fine-tuning. In the second contribution, we evaluate the effectiveness of knowledge editing methods for aligning LLMs with up-to-date factual knowledge and compare their performance with Retrieval Augmented Generation. The dynamic benchmark is designed to be used as-is to assess LLMs's up-to-dateness, as well as to be extended to other domains by sharing the code, the dataset, as well as evaluation and visualization scripts.

![你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。](../../../paper_images/2404.08700/x1.png)

![你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。](../../../paper_images/2404.08700/observed_data.png)

![你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。](../../../paper_images/2404.08700/scala_number_and_percentage.png)

![你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。](../../../paper_images/2404.08700/ragdocs.png)

![你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。](../../../paper_images/2404.08700/observed_data_appendix1.png)

![你的大型语言模型（LLM）落伍了吗？本文旨在评估适用于时效性知识的 LLM 和对齐算法的性能基准。](../../../paper_images/2404.08700/observed_data_appendix2.png)

[Arxiv](https://arxiv.org/abs/2404.08700)