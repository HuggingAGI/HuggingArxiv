# Movie101v2：提升版的电影叙事基准

发布时间：2024年04月20日

`分类：LLM应用

这篇论文主要研究了自动电影旁白生成的问题，这是一个实际应用场景，涉及到为视障观众提供与视频同步的剧情解说。论文中提到了现有数据集的不足，推出了一个新的大规模双语电影旁白数据集，并针对实现实用电影旁白的难点进行了研究。此外，论文还对包括 GPT-4V 在内的几个前沿视觉-语言模型进行了基准测试，并探讨了现有模型在电影旁白生成上面临的挑战。因此，这篇论文可以归类为 LLM 应用。` `电影制作` `无障碍技术`

> Movie101v2: Improved Movie Narration Benchmark

# 摘要

> 自动电影旁白旨在为视障观众提供与视频同步的剧情解说，这不仅涉及描述关键视觉元素，还包括推断跨多个场景发展的剧情，带来了特别的挑战。为了促进自动电影旁白系统的进展，我们首先回顾了现有数据集的不足，并推出了一个大规模双语电影旁白数据集 Movie101v2。接着，我们针对实现实用电影旁白的难点，将目标分解为三个递进阶段，目前主要关注单个片段内的理解。此外，我们引入了一种新的评估机制，以匹配我们的分阶段任务目标。最后，利用新数据集，我们对包括 GPT-4V 在内的几个前沿视觉-语言模型进行了基准测试，并深入探讨了现有模型在电影旁白生成上面临的挑战。研究结果表明，实现实用的电影旁白生成是一个充满吸引力的目标，需要进行深入的研究。

> Automatic movie narration targets at creating video-aligned plot descriptions to assist visually impaired audiences. It differs from standard video captioning in that it requires not only describing key visual details but also inferring the plots developed across multiple movie shots, thus posing unique and ongoing challenges. To advance the development of automatic movie narrating systems, we first revisit the limitations of existing datasets and develop a large-scale, bilingual movie narration dataset, Movie101v2. Second, taking into account the essential difficulties in achieving applicable movie narration, we break the long-term goal into three progressive stages and tentatively focus on the initial stages featuring understanding within individual clips. We also introduce a new narration assessment to align with our staged task goals. Third, using our new dataset, we baseline several leading large vision-language models, including GPT-4V, and conduct in-depth investigations into the challenges current models face for movie narration generation. Our findings reveal that achieving applicable movie narration generation is a fascinating goal that requires thorough research.

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x1.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x2.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x3.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x4.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x5.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x6.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x7.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x8.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x9.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x10.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x11.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x12.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x13.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x14.png)

![Movie101v2：提升版的电影叙事基准](../../../paper_images/2404.13370/x15.png)

[Arxiv](https://arxiv.org/abs/2404.13370)