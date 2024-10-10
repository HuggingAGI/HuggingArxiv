# TeaserGen：为长纪录片打造精彩预告片

发布时间：2024年10月07日

`LLM应用`

> TeaserGen: Generating Teasers for Long Documentaries

# 摘要

> Teasers 在娱乐、商业和教育领域中是推广内容的利器。然而，为长视频制作有效 teaser 却颇具挑战，需在输入视频上进行长距离多模态建模，同时确保视听同步、场景过渡自然且内容准确。由于缺乏公开数据集，相关研究进展受阻。为此，我们推出了 DocumentaryNet，包含 1,269 部纪录片及其 teaser，涵盖视频、语音、音乐、音效和旁白等多模态数据。基于此，我们设计了一个两阶段系统 TeaserGen，用于从长纪录片中生成 teaser。首先，利用预训练大型语言模型从纪录片旁白中生成 teaser 旁白，再通过语言-视觉模型精选最匹配的视觉内容。我们尝试了两种旁白-视频匹配方法：预训练对比语言-视觉模型和深度序列模型。实验显示，预训练方法在挑选相关视觉内容上更胜一筹。

> Teasers are an effective tool for promoting content in entertainment, commercial and educational fields. However, creating an effective teaser for long videos is challenging for it requires long-range multimodal modeling on the input videos, while necessitating maintaining audiovisual alignments, managing scene changes and preserving factual accuracy for the output teasers. Due to the lack of a publicly-available dataset, progress along this research direction has been hindered. In this work, we present DocumentaryNet, a collection of 1,269 documentaries paired with their teasers, featuring multimodal data streams of video, speech, music, sound effects and narrations. With DocumentaryNet, we propose a new two-stage system for generating teasers from long documentaries. The proposed TeaserGen system first generates the teaser narration from the transcribed narration of the documentary using a pretrained large language model, and then selects the most relevant visual content to accompany the generated narration through language-vision models. For narration-video matching, we explore two approaches: a pretraining-based model using pretrained contrastive language-vision models and a deep sequential model that learns the mapping between the narrations and visuals. Our experimental results show that the pretraining-based approach is more effective at identifying relevant visual content than directly trained deep autoregressive models.

[Arxiv](https://arxiv.org/abs/2410.05586)