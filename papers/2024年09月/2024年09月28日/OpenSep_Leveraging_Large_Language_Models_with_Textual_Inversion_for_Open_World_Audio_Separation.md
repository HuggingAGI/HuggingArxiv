# OpenSep：借助大型语言模型与文本反转技术，实现开放世界音频分离

发布时间：2024年09月28日

`LLM应用` `音频处理` `人工智能`

> OpenSep: Leveraging Large Language Models with Textual Inversion for Open World Audio Separation

# 摘要

> 在现实场景中，音频分离面临巨大挑战，尤其是当混合音频包含多种来源时，现有模型常出现过度或不足分离，且依赖预设训练源。为此，我们推出了OpenSep，一个利用大型语言模型（LLM）实现自动化音频分离的创新框架。OpenSep无需人工干预，通过文本反转技术，利用现成的音频字幕模型生成混合音频的字幕，精准识别声音来源。随后，通过少样本LLM提示，提取各来源的详细音频属性，实现对未知混合音频的分离。此外，我们还开发了多层次的混合与分离训练框架，同时处理单一声源和混合音频，提升模态对齐效果。实验结果显示，OpenSep在处理复杂混合音频时表现卓越，超越了当前最先进的方法。代码已公开发布，详见https://github.com/tanvir-utexas/OpenSep.git。

> Audio separation in real-world scenarios, where mixtures contain a variable number of sources, presents significant challenges due to limitations of existing models, such as over-separation, under-separation, and dependence on predefined training sources. We propose OpenSep, a novel framework that leverages large language models (LLMs) for automated audio separation, eliminating the need for manual intervention and overcoming source limitations. OpenSep uses textual inversion to generate captions from audio mixtures with off-the-shelf audio captioning models, effectively parsing the sound sources present. It then employs few-shot LLM prompting to extract detailed audio properties of each parsed source, facilitating separation in unseen mixtures. Additionally, we introduce a multi-level extension of the mix-and-separate training framework to enhance modality alignment by separating single source sounds and mixtures simultaneously. Extensive experiments demonstrate OpenSep's superiority in precisely separating new, unseen, and variable sources in challenging mixtures, outperforming SOTA baseline methods. Code is released at https://github.com/tanvir-utexas/OpenSep.git

[Arxiv](https://arxiv.org/abs/2409.19270)