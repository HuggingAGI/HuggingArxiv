# SlideChat：一款强大的视觉-语言助手，专为全切片病理图像的深度理解而设计。

发布时间：2024年10月15日

`LLM应用` `计算病理学`

> SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding

# 摘要

> 尽管多模态大型语言模型 (MLLM) 在计算病理学领域取得了进展，但它们仍受限于补丁级分析，忽略了整个切片的重要上下文信息。缺乏大规模指令数据集和 WSI 的千兆像素规模带来了重大挑战。本文介绍了 SlideChat，首个能理解千兆像素 WSI 的视觉语言助手，具备卓越的多模态对话能力和响应复杂指令的能力。为支持其开发，我们创建了 SlideInstruction，最大的 WSI 指令跟随数据集，包含 4.2K WSI 标题和 176K VQA 对。此外，我们提出了 SlideBench，结合字幕和 VQA 任务的多模态基准，评估 SlideChat 在不同临床环境中的能力。与通用和专业化的 MLLM 相比，SlideChat 在 22 项任务中的 18 项中表现卓越，达到最先进水平。例如，在 SlideBench-VQA (TCGA) 上准确率为 81.17%，在 SlideBench-VQA (BCNB) 上为 54.15%。我们将完全开源 SlideChat、SlideInstruction 和 SlideBench，以推动计算病理学的研究与开发。

> Despite the progress made by multimodal large language models (MLLMs) in computational pathology, they remain limited by a predominant focus on patch-level analysis, missing essential contextual information at the whole-slide level. The lack of large-scale instruction datasets and the gigapixel scale of whole slide images (WSIs) pose significant developmental challenges. In this paper, we present SlideChat, the first vision-language assistant capable of understanding gigapixel whole-slide images, exhibiting excellent multimodal conversational capability and response complex instruction across diverse pathology scenarios. To support its development, we created SlideInstruction, the largest instruction-following dataset for WSIs consisting of 4.2K WSI captions and 176K VQA pairs with multiple categories. Furthermore, we propose SlideBench, a multimodal benchmark that incorporates captioning and VQA tasks to assess SlideChat's capabilities in varied clinical settings such as microscopy, diagnosis. Compared to both general and specialized MLLMs, SlideChat exhibits exceptional capabilities achieving state-of-the-art performance on 18 of 22 tasks. For example, it achieved an overall accuracy of 81.17% on SlideBench-VQA (TCGA), and 54.15% on SlideBench-VQA (BCNB). We will fully release SlideChat, SlideInstruction and SlideBench as open-source resources to facilitate research and development in computational pathology.

[Arxiv](https://arxiv.org/abs/2410.11761)