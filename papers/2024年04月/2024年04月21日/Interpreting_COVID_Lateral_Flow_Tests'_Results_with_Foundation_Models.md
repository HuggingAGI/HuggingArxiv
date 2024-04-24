# 借助基础模型，我们能够更准确地解读 COVID 侧向流动测试的结果。

发布时间：2024年04月21日

`分类：LLM应用

这篇论文探讨了使用现代基础视觉语言模型（VLMs）来解读侧流检测（LFTs）结果的能力。研究构建了一个新的标记数据集LFT-Grounding，并评估了八种现代VLMs在零样本环境下的性能。这篇论文的研究重点是将现有的视觉语言模型应用于实际的健康问题检测场景，因此它属于LLM应用分类。` `健康监测` `计算机视觉`

> Interpreting COVID Lateral Flow Tests' Results with Foundation Models

# 摘要

> 侧流检测（LFTs）为Covid、怀孕、HIV和疟疾等健康问题提供了一种快速且经济的检测方式。LFT结果的自动化读取器不仅能够帮助视障人士自主了解健康状况，还能通过单张照片加快大规模监测（如Covid疫情）的数据录入速度。基于此，本研究探讨了现代基础视觉语言模型（VLMs）解读LFT结果的能力。为此，我们首先构建了一个新的标记数据集LFT-Grounding，它包含了对每个LFT测试及其内嵌的测试结果窗口的层次化分割。随后，我们对八种现代VLMs在零样本环境下进行了性能评估。研究发现，现有VLMs在准确识别LFT测试类型、解读测试结果、定位测试的内嵌结果窗口以及识别部分遮挡的LFT测试方面存在不足。为了推动自动化LFT读取技术的社区进步，我们公开了相关数据集，可通过 https://iamstuti.github.io/lft_grounding_foundation_models/ 获取。

> Lateral flow tests (LFTs) enable rapid, low-cost testing for health conditions including Covid, pregnancy, HIV, and malaria. Automated readers of LFT results can yield many benefits including empowering blind people to independently learn about their health and accelerating data entry for large-scale monitoring (e.g., for pandemics such as Covid) by using only a single photograph per LFT test. Accordingly, we explore the abilities of modern foundation vision language models (VLMs) in interpreting such tests. To enable this analysis, we first create a new labeled dataset with hierarchical segmentations of each LFT test and its nested test result window. We call this dataset LFT-Grounding. Next, we benchmark eight modern VLMs in zero-shot settings for analyzing these images. We demonstrate that current VLMs frequently fail to correctly identify the type of LFT test, interpret the test results, locate the nested result window of the LFT tests, and recognize LFT tests when they partially obfuscated. To facilitate community-wide progress towards automated LFT reading, we publicly release our dataset at https://iamstuti.github.io/lft_grounding_foundation_models/.

[Arxiv](https://arxiv.org/abs/2404.14990)