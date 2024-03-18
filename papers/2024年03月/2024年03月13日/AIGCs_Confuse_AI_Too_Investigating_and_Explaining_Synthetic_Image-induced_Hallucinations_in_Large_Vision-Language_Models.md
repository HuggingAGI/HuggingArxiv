# AIGC 生成的内容同样能迷惑 AI，我们正致力于探究大型视觉-语言模型在面对合成图像时产生的幻觉现象，并对其进行深入解析。

发布时间：2024年03月13日

`LLM应用` `人工智能` `计算机视觉`

> AIGCs Confuse AI Too: Investigating and Explaining Synthetic Image-induced Hallucinations in Large Vision-Language Models

> 随着AIGC质量的不断提升，它所带来的新挑战也愈发显现——尽管AI生成的内容在多种AI模型中担当要角，其可能带来的隐性风险却尚未经过深入探究。不仅局限于针对人类的伪造识别，AI生成的内容甚至对那些原以处理自然数据为目的的AI模型产生了影响。研究发现，在LVLMs中，AI合成图像导致的幻觉现象更为显著。令人瞩目的是，研究揭示了一种持续存在的AIGC\textbf{幻觉倾向}：即便相比自然图像，合成图像并未展现出超现实或额外的相关视觉特性，其所诱发的对象幻觉却呈现出数量更多、位置分布更均匀的特点。进一步地，通过对Q-former和线性投影器的研究，我们了解到合成图像在经过视觉投影后可能出现标记偏差，这无疑进一步加剧了幻觉倾向的问题。

> The evolution of Artificial Intelligence Generated Contents (AIGCs) is advancing towards higher quality. The growing interactions with AIGCs present a new challenge to the data-driven AI community: While AI-generated contents have played a crucial role in a wide range of AI models, the potential hidden risks they introduce have not been thoroughly examined. Beyond human-oriented forgery detection, AI-generated content poses potential issues for AI models originally designed to process natural data. In this study, we underscore the exacerbated hallucination phenomena in Large Vision-Language Models (LVLMs) caused by AI-synthetic images. Remarkably, our findings shed light on a consistent AIGC \textbf{hallucination bias}: the object hallucinations induced by synthetic images are characterized by a greater quantity and a more uniform position distribution, even these synthetic images do not manifest unrealistic or additional relevant visual features compared to natural images. Moreover, our investigations on Q-former and Linear projector reveal that synthetic images may present token deviations after visual projection, thereby amplifying the hallucination bias.

![AIGC 生成的内容同样能迷惑 AI，我们正致力于探究大型视觉-语言模型在面对合成图像时产生的幻觉现象，并对其进行深入解析。](../../../paper_images/2403.08542/Introduction.jpg)

![AIGC 生成的内容同样能迷惑 AI，我们正致力于探究大型视觉-语言模型在面对合成图像时产生的幻觉现象，并对其进行深入解析。](../../../paper_images/2403.08542/semantic_translation_01.jpg)

![AIGC 生成的内容同样能迷惑 AI，我们正致力于探究大型视觉-语言模型在面对合成图像时产生的幻觉现象，并对其进行深入解析。](../../../paper_images/2403.08542/caption-revision_01.jpg)

![AIGC 生成的内容同样能迷惑 AI，我们正致力于探究大型视觉-语言模型在面对合成图像时产生的幻觉现象，并对其进行深入解析。](../../../paper_images/2403.08542/Redar.jpg)

[Arxiv](https://arxiv.org/abs/2403.08542)