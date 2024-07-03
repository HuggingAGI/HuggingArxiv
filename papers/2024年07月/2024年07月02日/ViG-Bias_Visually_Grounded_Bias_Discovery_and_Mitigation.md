# ViG-Bias：通过视觉基础技术发现并缓解偏见

发布时间：2024年07月02日

`LLM应用` `计算机视觉` `人工智能`

> ViG-Bias: Visually Grounded Bias Discovery and Mitigation

# 摘要

> 机器学习模型在关键决策中的广泛应用，使得偏差的发现与缓解变得尤为重要。然而，偏差背后的原因往往隐藏在难以察觉的虚假相关性中，不易识别。传统方法通过分析模型在具有共同属性（如性别或种族）的子组中的表现来进行偏差审计。但视觉识别系统的失败模式往往难以预知。近期研究提出利用大型视觉语言模型，通过提取跨模态嵌入和生成文本描述来发现模型表现不佳的子组。我们提出，结合视觉解释（如热图）能有效提升偏差发现与缓解框架的性能。为此，我们开发了视觉基础偏差发现与缓解技术（ViG-Bias），该技术简单高效，可集成于多种框架，显著提升性能。在多个挑战性数据集上的全面评估表明，视觉解释的引入显著增强了现有技术，如 DOMINO、FACTS 和 Bias-to-Text。

> The proliferation of machine learning models in critical decision making processes has underscored the need for bias discovery and mitigation strategies. Identifying the reasons behind a biased system is not straightforward, since in many occasions they are associated with hidden spurious correlations which are not easy to spot. Standard approaches rely on bias audits performed by analyzing model performance in pre-defined subgroups of data samples, usually characterized by common attributes like gender or ethnicity when it comes to people, or other specific attributes defining semantically coherent groups of images. However, it is not always possible to know a-priori the specific attributes defining the failure modes of visual recognition systems. Recent approaches propose to discover these groups by leveraging large vision language models, which enable the extraction of cross-modal embeddings and the generation of textual descriptions to characterize the subgroups where a certain model is underperforming. In this work, we argue that incorporating visual explanations (e.g. heatmaps generated via GradCAM or other approaches) can boost the performance of such bias discovery and mitigation frameworks. To this end, we introduce Visually Grounded Bias Discovery and Mitigation (ViG-Bias), a simple yet effective technique which can be integrated to a variety of existing frameworks to improve both, discovery and mitigation performance. Our comprehensive evaluation shows that incorporating visual explanations enhances existing techniques like DOMINO, FACTS and Bias-to-Text, across several challenging datasets, including CelebA, Waterbirds, and NICO++.

[Arxiv](https://arxiv.org/abs/2407.01996)