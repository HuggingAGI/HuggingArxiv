# 大型语言模型是否具备理解空间音频的能力？

发布时间：2024年06月12日

`Agent

这篇论文主要探讨了如何赋予大型语言模型（LLMs）理解多通道音频中的空间信息，并将其应用于声源定位、远场语音识别和定位引导的语音提取等任务。这些应用展示了LLMs在物理音频概念上的适应性，并为其在三维环境中的代理应用提供了新的可能性。因此，这篇论文更符合Agent分类，因为它关注的是LLMs在具体任务中的应用，特别是在增强代理在三维环境中的能力方面。` `音频处理` `语音识别`

> Can Large Language Models Understand Spatial Audio?

# 摘要

> 本文旨在赋予大型语言模型（LLMs）理解多通道音频中空间信息的能力，这一技能在当前的听觉型LLMs中尚属空白。借助LLMs的高级认知与推理能力，我们致力于通过音频提升对三维环境的理解。研究涵盖了三个关键任务：声源定位（SSL）、远场语音识别（FSR）及定位引导的语音提取（LSE），并在各领域取得了显著成果。在SSL任务中，我们的方法在Spatial LibriSpeech数据集上实现了2.70°的平均绝对误差，远超先前约6.60°的记录。此外，我们的模型能利用空间线索提升FSR的准确性，并通过文本提示，在重叠语音中精准定位并提取来自特定方向的声音，实现LSE。这些成果展示了LLMs适应物理音频概念的潜力，为基于LLM的代理在三维环境中的应用开辟了新路径。

> This paper explores enabling large language models (LLMs) to understand spatial information from multichannel audio, a skill currently lacking in auditory LLMs. By leveraging LLMs' advanced cognitive and inferential abilities, the aim is to enhance understanding of 3D environments via audio. We study 3 spatial audio tasks: sound source localization (SSL), far-field speech recognition (FSR), and localisation-informed speech extraction (LSE), achieving notable progress in each task. For SSL, our approach achieves an MAE of $2.70^{\circ}$ on the Spatial LibriSpeech dataset, substantially surpassing the prior benchmark of about $6.60^{\circ}$. Moreover, our model can employ spatial cues to improve FSR accuracy and execute LSE by selectively attending to sounds originating from a specified direction via text prompts, even amidst overlapping speech. These findings highlight the potential of adapting LLMs to grasp physical audio concepts, paving the way for LLM-based agents in 3D environments.

![大型语言模型是否具备理解空间音频的能力？](../../../paper_images/2406.07914/x1.png)

![大型语言模型是否具备理解空间音频的能力？](../../../paper_images/2406.07914/x2.png)

![大型语言模型是否具备理解空间音频的能力？](../../../paper_images/2406.07914/x3.png)

[Arxiv](https://arxiv.org/abs/2406.07914)