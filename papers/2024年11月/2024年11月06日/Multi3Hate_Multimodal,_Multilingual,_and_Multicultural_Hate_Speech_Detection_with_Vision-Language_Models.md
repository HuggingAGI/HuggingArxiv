# Multi3Hate：使用视觉语言模型进行多模态、多语言和多元文化的仇恨言论检测

发布时间：2024年11月06日

`LLM应用` `社交媒体` `多语言处理`

> Multi3Hate: Multimodal, Multilingual, and Multicultural Hate Speech Detection with Vision-Language Models

# 摘要

> 警告：本文包含可能具有冒犯性或令人不安的内容。由于内容的多模态和多语言性质以及不同的文化观念，全球平台上的仇恨言论监管带来了独特的挑战。当前的视觉语言模型（VLMs）如何应对这些细微差别？为了对此进行研究，我们创建了第一个多模态和多语言并行仇恨言论数据集，由多元文化的标注员进行标注，称为 Multi3Hate。它包含 5 种语言（英语、德语、西班牙语、印地语和汉语普通话）的 300 个并行的模因样本。我们证明，在我们的数据集中，文化背景显著影响多模态仇恨言论标注。各国之间的平均成对一致性仅为 74％，显著低于随机选择的标注员组。我们的定性分析表明，最低的成对标签一致性——美国和印度之间仅为 67％——可归因于文化因素。然后，我们在零样本设置中对 5 个大型 VLMs 进行实验，发现这些模型与来自美国的标注更一致，而不是与来自其他文化的标注一致，即使模因和提示以其他文化的主导语言呈现。代码和数据集可在 https://github.com/MinhDucBui/Multi3Hate 获得。

> Warning: this paper contains content that may be offensive or upsetting
  Hate speech moderation on global platforms poses unique challenges due to the multimodal and multilingual nature of content, along with the varying cultural perceptions. How well do current vision-language models (VLMs) navigate these nuances? To investigate this, we create the first multimodal and multilingual parallel hate speech dataset, annotated by a multicultural set of annotators, called Multi3Hate. It contains 300 parallel meme samples across 5 languages: English, German, Spanish, Hindi, and Mandarin. We demonstrate that cultural background significantly affects multimodal hate speech annotation in our dataset. The average pairwise agreement among countries is just 74%, significantly lower than that of randomly selected annotator groups. Our qualitative analysis indicates that the lowest pairwise label agreement-only 67% between the USA and India-can be attributed to cultural factors. We then conduct experiments with 5 large VLMs in a zero-shot setting, finding that these models align more closely with annotations from the US than with those from other cultures, even when the memes and prompts are presented in the dominant language of the other culture. Code and dataset are available at https://github.com/MinhDucBui/Multi3Hate.

[Arxiv](https://arxiv.org/abs/2411.03888)