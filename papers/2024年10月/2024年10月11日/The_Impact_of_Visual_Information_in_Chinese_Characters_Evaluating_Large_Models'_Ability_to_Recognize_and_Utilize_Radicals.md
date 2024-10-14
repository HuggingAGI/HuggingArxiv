# 视觉信息如何影响汉字识别：探究大型模型对部首的识别与利用能力

发布时间：2024年10月11日

`LLM应用` `中文语言处理`

> The Impact of Visual Information in Chinese Characters: Evaluating Large Models' Ability to Recognize and Utilize Radicals

# 摘要

> 中国汉字系统蕴含丰富的视觉特征，如部首，能提示字义或发音。然而，现代大型语言模型（LLMs）和视觉语言模型（VLMs）是否能通过提示利用这些特征，尚无研究。本研究设立基准，评估模型对汉字视觉元素的理解，包括部首、结构、笔画等。结果显示，模型虽能识别部分视觉信息，但能力有限。为提升模型利用部首的能力，我们尝试在提示中融入部首信息，用于中文语言理解任务。实验表明，提供部首信息能显著提升词性标注效果，暗示整合子字符信息或能增强中文语言处理能力。

> The glyphic writing system of Chinese incorporates information-rich visual features in each character, such as radicals that provide hints about meaning or pronunciation. However, there has been no investigation into whether contemporary Large Language Models (LLMs) and Vision-Language Models (VLMs) can harness these sub-character features in Chinese through prompting. In this study, we establish a benchmark to evaluate LLMs' and VLMs' understanding of visual elements in Chinese characters, including radicals, composition structures, strokes, and stroke counts. Our results reveal that models surprisingly exhibit some, but still limited, knowledge of the visual information, regardless of whether images of characters are provided. To incite models' ability to use radicals, we further experiment with incorporating radicals into the prompts for Chinese language understanding tasks. We observe consistent improvement in Part-Of-Speech tagging when providing additional information about radicals, suggesting the potential to enhance CLP by integrating sub-character information.

[Arxiv](https://arxiv.org/abs/2410.09013)