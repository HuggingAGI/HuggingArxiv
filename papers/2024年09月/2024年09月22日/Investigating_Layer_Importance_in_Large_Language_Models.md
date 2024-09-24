# 探索大型语言模型中的层级重要性

发布时间：2024年09月22日

`LLM理论` `人工智能` `机器学习`

> Investigating Layer Importance in Large Language Models

# 摘要

> 大型语言模型 (LLM) 因其强大的文本理解和处理能力备受瞩目，但其内部机制仍如黑匣子般神秘。这种不透明性不仅限制了其在高风险场景中的应用，也阻碍了更优模型的研发。本研究深入探索 LLM 的内部结构，聚焦于各层的重要性。我们设计了一种高效采样方法，利用 Shapley 值这一广泛应用于特征归因和数据估值的解释框架，精准评估各层的影响力。此外，通过层消融实验，我们揭示了某些早期层（即基石层）对模型性能的巨大贡献。移除这些基石层会导致模型性能骤降，甚至沦为随机猜测。而移除非基石层则仅带来微乎其微的性能波动。本研究不仅识别了 LLM 中的关键基石层，更为未来研究指明了方向。

> Large language models (LLMs) have gained increasing attention due to their prominent ability to understand and process texts. Nevertheless, LLMs largely remain opaque. The lack of understanding of LLMs has obstructed the deployment in safety-critical scenarios and hindered the development of better models. In this study, we advance the understanding of LLM by investigating the significance of individual layers in LLMs. We propose an efficient sampling method to faithfully evaluate the importance of layers using Shapley values, a widely used explanation framework in feature attribution and data valuation. In addition, we conduct layer ablation experiments to assess the performance degradation resulting from the exclusion of specific layers. Our findings reveal the existence of cornerstone layers, wherein certain early layers can exhibit a dominant contribution over others. Removing one cornerstone layer leads to a drastic collapse of the model performance, often reducing it to random guessing. Conversely, removing non-cornerstone layers results in only marginal performance changes. This study identifies cornerstone layers in LLMs and underscores their critical role for future research.

[Arxiv](https://arxiv.org/abs/2409.14381)