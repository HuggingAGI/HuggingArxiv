# Aquila-plus：用于像素级遥感图像理解的提示驱动视觉语言模型

发布时间：2024年11月09日

`LLM应用` `图像理解`

> Aquila-plus: Prompt-Driven Visual-Language Models for Pixel-Level Remote Sensing Image Understanding

# 摘要

> 视觉语言模型（VLMs）的最新发展通过视觉指令调整在视觉语言集成方面取得了重大进展，并且在遥感图像理解领域迅速发展，展示了其强大的能力。然而，现有的遥感视觉语言模型（RSVLMs）主要关注图像级或帧级理解，难以实现细粒度的像素级视觉语言对齐。此外，基于掩码的指令数据的缺乏限制了它们的进一步发展。在本文中，我们提出了一种称为 Aquila-plus 的掩码文本指令调整方法，通过将细粒度掩码区域纳入语言指令，扩展了 RSVLMs 的能力，以实现像素级视觉理解。为了实现这一点，我们首先精心构建了一个包含 100K 样本的掩码区域 - 文本数据集，然后通过将像素级表示注入大型语言模型（LLM）设计了一个视觉语言模型。具体而言，Aquila-plus 使用卷积 CLIP 作为视觉编码器，并采用掩码感知视觉提取器从高分辨率输入中提取精确的视觉掩码特征。实验结果表明，Aquila-plus 在各种区域理解任务中优于现有方法，展示了其在像素级指令调整方面的新能力。

> The recent development of vision language models (VLMs) has led to significant advances in visual-language integration through visual instruction tuning, and they have rapidly evolved in the field of remote sensing image understanding, demonstrating their powerful capabilities. However, existing RSVLMs mainly focus on image-level or frame-level understanding, making it difficult to achieve fine-grained pixel-level visual-language alignment. Additionally, the lack of mask-based instructional data limits their further development. In this paper, we propose a mask-text instruction tuning method called Aquila-plus, which extends the capabilities of RSVLMs to achieve pixel-level visual understanding by incorporating fine-grained mask regions into language instructions. To achieve this, we first meticulously constructed a mask region-text dataset containing 100K samples, and then designed a visual-language model by injecting pixel-level representations into a large language model (LLM). Specifically, Aquila-plus uses a convolutional CLIP as the visual encoder and employs a mask-aware visual extractor to extract precise visual mask features from high-resolution inputs. Experimental results demonstrate that Aquila-plus outperforms existing methods in various region understanding tasks, showcasing its novel capabilities in pixel-level instruction tuning.

[Arxiv](https://arxiv.org/abs/2411.06142)