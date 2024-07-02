# 探索并缓解大型视觉-语言模型中多模态幻觉的累积效应

发布时间：2024年06月29日

`LLM应用` `计算机视觉` `人工智能`

> Investigating and Mitigating the Multimodal Hallucination Snowballing in Large Vision-Language Models

# 摘要

> 尽管大型视觉-语言模型（LVLMs）在理解视觉信息方面取得了显著进步，但它们仍面临多模态幻觉的问题。我们担心，在多模态交互中，这些幻觉可能误导LVLMs的后续生成。因此，我们提出疑问：面对与先前幻觉相关的查询时，即使基础视觉信息存在，LVLMs是否会被误导并给出错误答案？为此，我们设计了MMHalSnowball框架，评估LVLMs在幻觉情境下的反应。实验显示，开源LVLMs性能下降至少31%，表明它们易受幻觉影响，做出错误判断。这种现象我们称之为“多模态幻觉滚雪球”。为解决这一问题，我们提出无需额外训练的“残差视觉解码”方法，通过调整输出分布，使模型直接获取视觉信息，有效减少24%以上的幻觉影响，同时保持原有能力。

> Though advanced in understanding visual information with human languages, Large Vision-Language Models (LVLMs) still suffer from multimodal hallucinations. A natural concern is that during multimodal interaction, the generated hallucinations could influence the LVLMs' subsequent generation. Thus, we raise a question: When presented with a query relevant to the previously generated hallucination, will LVLMs be misled and respond incorrectly, even though the ground visual information exists? To answer this, we propose a framework called MMHalSnowball to evaluate LVLMs' behaviors when encountering generated hallucinations, where LVLMs are required to answer specific visual questions within a curated hallucinatory conversation. Crucially, our experiment shows that the performance of open-source LVLMs drops by at least $31\%$, indicating that LVLMs are prone to accept the generated hallucinations and make false claims that they would not have supported without distractions. We term this phenomenon Multimodal Hallucination Snowballing. To mitigate this, we further propose a training-free method called Residual Visual Decoding, where we revise the output distribution of LVLMs with the one derived from the residual visual input, providing models with direct access to the visual information. Experiments show that our method can mitigate more than $24\%$ of the snowballed multimodal hallucination while maintaining capabilities.

[Arxiv](https://arxiv.org/abs/2407.00569)