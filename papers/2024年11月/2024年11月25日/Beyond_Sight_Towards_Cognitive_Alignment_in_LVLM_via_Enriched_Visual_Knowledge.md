# 超越视觉：借助丰富的视觉知识在 LVLM 中达成认知对齐

发布时间：2024年11月25日

`LLM应用` `计算机视觉` `多模态系统`

> Beyond Sight: Towards Cognitive Alignment in LVLM via Enriched Visual Knowledge

# 摘要

> 看到就意味着知道吗？大型视觉语言模型（LVLMs）融合了分别预训练的视觉和语言部分，常以 CLIP-ViT 作为视觉核心。然而，这类模型往往存在视觉编码器（VE）与大型语言模型（LLM）之间“认知错位”的关键问题。具体而言，VE 对视觉信息的呈现可能与 LLM 的认知框架不完全契合，致使出现视觉特征超出语言模型解释范畴的不匹配情况。为解决此问题，我们探究了 VE 表征的变化对 LVLMs 理解能力的影响，尤其是当 LLM 面对 VE 未知数据——那些模糊的视觉表征对 VE 解释精度构成挑战的图像时。于是，我们构建了一个多粒度的地标数据集，并系统地考察了 VE 已知和 VE 未知数据对解读能力的作用。我们的成果显示，VE 未知数据限制了 LVLMs 准确理解的能力，而富含独特特征的 VE 已知数据有助于降低认知错位。基于这些发现，我们提出了实体增强认知对齐（EECA）方法，它通过多粒度监督生成视觉丰富、对齐良好的标记，这些标记不但融入 LLM 的嵌入空间，还与 LLM 的认知框架相符。这种对齐显著提升了 LVLMs 在地标识别方面的表现。我们的研究结果凸显了 VE 未知数据带来的挑战，也突显了认知对齐在推进多模态系统中的关键作用。

> Does seeing always mean knowing? Large Vision-Language Models (LVLMs) integrate separately pre-trained vision and language components, often using CLIP-ViT as vision backbone. However, these models frequently encounter a core issue of "cognitive misalignment" between the vision encoder (VE) and the large language model (LLM). Specifically, the VE's representation of visual information may not fully align with LLM's cognitive framework, leading to a mismatch where visual features exceed the language model's interpretive range. To address this, we investigate how variations in VE representations influence LVLM comprehension, especially when the LLM faces VE-Unknown data-images whose ambiguous visual representations challenge the VE's interpretive precision. Accordingly, we construct a multi-granularity landmark dataset and systematically examine the impact of VE-Known and VE-Unknown data on interpretive abilities. Our results show that VE-Unknown data limits LVLM's capacity for accurate understanding, while VE-Known data, rich in distinctive features, helps reduce cognitive misalignment. Building on these insights, we propose Entity-Enhanced Cognitive Alignment (EECA), a method that employs multi-granularity supervision to generate visually enriched, well-aligned tokens that not only integrate within the LLM's embedding space but also align with the LLM's cognitive framework. This alignment markedly enhances LVLM performance in landmark recognition. Our findings underscore the challenges posed by VE-Unknown data and highlight the essential role of cognitive alignment in advancing multimodal systems.

[Arxiv](https://arxiv.org/abs/2411.16824)