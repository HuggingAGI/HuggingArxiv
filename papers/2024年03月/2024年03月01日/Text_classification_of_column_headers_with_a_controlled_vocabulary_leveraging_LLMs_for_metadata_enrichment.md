# [借助LLMs，本研究探讨如何运用受控词汇对列标题进行文本分类，以实现元数据的有效丰富。]

发布时间：2024年03月01日

`LLM应用`

> Text classification of column headers with a controlled vocabulary: leveraging LLMs for metadata enrichment

> 传统数据检索体系侧重于元数据索引而轻视实际数据内容，高度依赖人力标注及高标准元数据，此类过程耗时费力且不易自动化。我们创新性地采用ChatGPT-3.5、GoogleBard和GoogleGemini三种大型语言模型，为列头添加主题注解以丰富元数据。本研究探究这些LLMs能否根据预设领域主题从受控词汇表中准确分类列头。评估过程中，我们考察了LLMs自身一致性、不同模型间的一致性以及人机在主题分类任务上的共识度。同时，我们也调查了上下文信息（例如数据集描述）对分类结果的影响力。实验结果显示，ChatGPT和GoogleGemini在保持内部一致性和与人类判断一致性上均超越了GoogleBard，令人意外的是，上下文信息并未对LLMs的性能产生明显影响。这项研究提出了一种崭新的利用LLMs结合受控主题词汇表进行文本分类的方法，有望推动元数据自动丰富进程，进而提升数据集检索效果，更好地实现Web上研究数据FAIR原则（可查找、可访问、可交互和可重复使用）。

> Traditional dataset retrieval systems index on metadata information rather than on the data values. Thus relying primarily on manual annotations and high-quality metadata, processes known to be labour-intensive and challenging to automate. We propose a method to support metadata enrichment with topic annotations of column headers using three Large Language Models (LLMs): ChatGPT-3.5, GoogleBard and GoogleGemini. We investigate the LLMs ability to classify column headers based on domain-specific topics from a controlled vocabulary. We evaluate our approach by assessing the internal consistency of the LLMs, the inter-machine alignment, and the human-machine agreement for the topic classification task. Additionally, we investigate the impact of contextual information (i.e. dataset description) on the classification outcomes. Our results suggest that ChatGPT and GoogleGemini outperform GoogleBard for internal consistency as well as LLM-human-alignment. Interestingly, we found that context had no impact on the LLMs performances. This work proposes a novel approach that leverages LLMs for text classification using a controlled topic vocabulary, which has the potential to facilitate automated metadata enrichment, thereby enhancing dataset retrieval and the Findability, Accessibility, Interoperability and Reusability (FAIR) of research data on the Web.

[Arxiv](https://arxiv.org/abs/2403.00884)