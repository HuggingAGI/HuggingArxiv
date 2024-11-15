# 多模态大型语言模型里的跨模态一致性

发布时间：2024年11月14日

`LLM应用` `计算机视觉` `多模态模型`

> Cross-Modal Consistency in Multimodal Large Language Models

# 摘要

> 多模态方法的最新进展开启了令人兴奋的新时代，对于擅长处理文本、音频、视觉等各类数据的模型而言意义非凡。像 GPT-4V 这类融合计算机视觉与高级语言处理的模型，在处理需要同时理解文本和视觉信息的复杂任务时表现出色。此前的研究工作已细致评估了这些视觉大型语言模型（VLLMs）在对象检测、图像字幕等诸多领域的效果。然而，现有分析常存在局限，主要是孤立评估每种模态的性能，而忽视了探究其复杂的跨模态交互。具体而言，面对不同模态的相同任务实例，这些模型能否达到相同的准确率这一问题仍无答案。在本研究中，我们引入“跨模态一致性”这一新概念，主动深入探究这些感兴趣的模态间的相互作用与比较。此外，我们基于此概念提出了定量评估框架。从我们精心整理的并行视觉语言数据集得出的实验结果表明，尽管 GPT-4V 被描绘为统一的多模态模型，但其视觉和语言模态之间存在显著的不一致性。我们的研究为这类模型的合理使用提供了思路，并暗示了优化其设计的潜在方向。

> Recent developments in multimodal methodologies have marked the beginning of an exciting era for models adept at processing diverse data types, encompassing text, audio, and visual content. Models like GPT-4V, which merge computer vision with advanced language processing, exhibit extraordinary proficiency in handling intricate tasks that require a simultaneous understanding of both textual and visual information. Prior research efforts have meticulously evaluated the efficacy of these Vision Large Language Models (VLLMs) in various domains, including object detection, image captioning, and other related fields. However, existing analyses have often suffered from limitations, primarily centering on the isolated evaluation of each modality's performance while neglecting to explore their intricate cross-modal interactions. Specifically, the question of whether these models achieve the same level of accuracy when confronted with identical task instances across different modalities remains unanswered. In this study, we take the initiative to delve into the interaction and comparison among these modalities of interest by introducing a novel concept termed cross-modal consistency. Furthermore, we propose a quantitative evaluation framework founded on this concept. Our experimental findings, drawn from a curated collection of parallel vision-language datasets developed by us, unveil a pronounced inconsistency between the vision and language modalities within GPT-4V, despite its portrayal as a unified multimodal model. Our research yields insights into the appropriate utilization of such models and hints at potential avenues for enhancing their design.

[Arxiv](https://arxiv.org/abs/2411.09273)