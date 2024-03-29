# 一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答

发布时间：2024年03月27日

`LLM应用` `视频处理` `问答系统`

> An Image Grid Can Be Worth a Video: Zero-shot Video Question Answering Using a VLM

# 摘要

> 受最新大型语言模型（LLMs）卓越推理能力的激励，众多连接视频模态的策略应运而生。其中，视频语言模型（VideoLMs）通过训练与视频数据相结合的可学习接口，将先进的视觉编码器与LLMs相连接，尤为突出。最近，一种新兴策略浮出水面，它利用现成的基础模型，例如VideoLMs和LLMs，在多个阶段实现模态桥接。本研究提出了一种简洁而创新的方法，仅利用一个视觉语言模型（VLM）。我们的基本认识是，视频由一系列带有时间信息的图像或帧组成。掌握视频理解的关键在于巧妙处理每个帧的时间和空间细节。我们首先将视频转换为单个复合图像，通过将多个帧排列成网格布局。这个单一的图像被称为图像网格。图像网格格式在保持单一图像外观的同时，有效地在网格结构中保留了时间信息。因此，图像网格方法可以直接应用单一的高性能VLM，无需视频数据训练。我们对十个零样本视频问答基准测试进行了广泛的实验分析，包括五个开放式和五个多项选择基准测试，结果表明，我们提出的图像网格视觉语言模型（IG-VLM）在十个基准测试中的九个中都超越了现有方法。

> Stimulated by the sophisticated reasoning capabilities of recent Large Language Models (LLMs), a variety of strategies for bridging video modality have been devised. A prominent strategy involves Video Language Models (VideoLMs), which train a learnable interface with video data to connect advanced vision encoders with LLMs. Recently, an alternative strategy has surfaced, employing readily available foundation models, such as VideoLMs and LLMs, across multiple stages for modality bridging. In this study, we introduce a simple yet novel strategy where only a single Vision Language Model (VLM) is utilized. Our starting point is the plain insight that a video comprises a series of images, or frames, interwoven with temporal information. The essence of video comprehension lies in adeptly managing the temporal aspects along with the spatial details of each frame. Initially, we transform a video into a single composite image by arranging multiple frames in a grid layout. The resulting single image is termed as an image grid. This format, while maintaining the appearance of a solitary image, effectively retains temporal information within the grid structure. Therefore, the image grid approach enables direct application of a single high-performance VLM without necessitating any video-data training. Our extensive experimental analysis across ten zero-shot video question answering benchmarks, including five open-ended and five multiple-choice benchmarks, reveals that the proposed Image Grid Vision Language Model (IG-VLM) surpasses the existing methods in nine out of ten benchmarks.

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/final_figure1_final2.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/final_figure2_final.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/shape_activity.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/shape_next.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/order_activity.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/order_next.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/ffn_activity.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/ffn_next.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/ex_123_final7.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/ex_456_final3.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/multiple_final2.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/ex_wrong_final.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/wrong_multiple_final2.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/prompt_zeroshot_cot.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/prompt_selfconsistency.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/prompt_plan_and_solve.png)

![一张图像网格胜过千言万语：借助视觉语言模型实现零样本视频问答](../../../paper_images/2403.18406/prompt_describe_and_answer.png)

[Arxiv](https://arxiv.org/abs/2403.18406)