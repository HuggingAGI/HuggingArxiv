# [在视觉-语言预训练中，我们致力于借助丰富的监督信息以增强模型性能。](https://arxiv.org/abs/2403.03346)

发布时间：2024年03月05日

`Agent`

> Enhancing Vision-Language Pre-training with Rich Supervisions

> 我们提出了一项名为“带有屏幕截图的强监督预训练（S4）”的新颖方案，它利用大规模网络截图渲染数据来提升视觉-语言模型的预训练效果。借助网页截图这一宝库，我们能获取图像-文本对所不具备的丰富视觉和文本信息。在S4中，我们巧妙运用HTML元素固有的树形层级结构及空间定位特性，精心设计了10项具备大量标注数据的预训练任务，它们与各领域下游任务高度契合，且获取标注的成本较低。实验结果显示，相较于现行屏幕截图预训练手段，我们的创新预训练方法在九项多样而热门的下游任务中明显提升了图像转文本模型的表现，其中表格检测任务性能提升达76.1%，而Widget标题生成任务至少提高1%。

> We propose Strongly Supervised pre-training with ScreenShots (S4) - a novel pre-training paradigm for Vision-Language Models using data from large-scale web screenshot rendering. Using web screenshots unlocks a treasure trove of visual and textual cues that are not present in using image-text pairs. In S4, we leverage the inherent tree-structured hierarchy of HTML elements and the spatial localization to carefully design 10 pre-training tasks with large scale annotated data. These tasks resemble downstream tasks across different domains and the annotations are cheap to obtain. We demonstrate that, compared to current screenshot pre-training objectives, our innovative pre-training method significantly enhances performance of image-to-text model in nine varied and popular downstream tasks - up to 76.1% improvements on Table Detection, and at least 1% on Widget Captioning.