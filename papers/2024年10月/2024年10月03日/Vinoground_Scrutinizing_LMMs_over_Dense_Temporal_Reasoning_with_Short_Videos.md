# Vinoground：通过短片深入探究大型多模态模型在密集时间推理中的表现

发布时间：2024年10月03日

`LLM应用` `视频分析` `人工智能`

> Vinoground: Scrutinizing LMMs over Dense Temporal Reasoning with Short Videos

# 摘要

> 近期，人们普遍认为现代大型多模态模型 (LMMs) 已基本解决了短视频理解的关键难题。然而，我们的研究发现，LMMs 在处理短视频时仍存在诸多基本推理能力的不足。为此，我们推出了 Vinoground，一个包含 1000 个短自然视频-字幕对的时间反事实评估基准。实验显示，现有 LMMs 在区分动作和物体变换的时间差异上表现不佳，最佳模型 GPT-4o 仅达到约 50% 的准确率，远低于人类基准的 90%。开源和基于 CLIP 的模型表现更差，几乎只能随机猜测。这表明，短视频中的时间推理问题仍待解决。数据集和评估代码已公开，访问 https://vinoground.github.io 即可获取。

> There has been growing sentiment recently that modern large multimodal models (LMMs) have addressed most of the key challenges related to short video comprehension. As a result, both academia and industry are gradually shifting their attention towards the more complex challenges posed by understanding long-form videos. However, is this really the case? Our studies indicate that LMMs still lack many fundamental reasoning capabilities even when dealing with short videos. We introduce Vinoground, a temporal counterfactual LMM evaluation benchmark encompassing 1000 short and natural video-caption pairs. We demonstrate that existing LMMs severely struggle to distinguish temporal differences between different actions and object transformations. For example, the best model GPT-4o only obtains ~50% on our text and video scores, showing a large gap compared to the human baseline of ~90%. All open-source multimodal models and CLIP-based models perform much worse, producing mostly random chance performance. Through this work, we shed light onto the fact that temporal reasoning in short videos is a problem yet to be fully solved. The dataset and evaluation code are available at https://vinoground.github.io.

[Arxiv](https://arxiv.org/abs/2410.02763)