# FoPru：针对高效大型视觉语言模型的焦点剪枝

发布时间：2024年11月21日

`LLM应用` `多模态`

> FoPru: Focal Pruning for Efficient Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）能够让强大的大型语言模型（LLMs）理解视觉输入，这标志着在达成卓越多模态能力方面取得了重大进展。通常，LVLMs 借助像 CLIP 这样的视觉编码器把图像转化为视觉标记，接着通过投影层与文本标记对齐后输入 LLM 进行推理。尽管现有的 LVLMs 成果斐然，但大量的视觉标记以及其中潜在的冗余仍限制着其推理效率。为解决此问题，我们提出了焦点修剪（FoPru），这是一种无需训练的方法，它依据视觉编码器得出的基于注意力的标记重要性来修剪视觉标记。具体而言，我们引入了两种不同的修剪策略：1）排名策略，利用所有标记重要性分数从全局视角保留更关键的标记；2）行策略，从局部角度注重保留图像中的连续关键信息。最后，所选标记会重新排序以维持其原有的位置关系。在各类 LVLMs 和多模态数据集中开展的大量实验表明，我们的方法能修剪大量冗余标记，同时保持高准确率，大幅提升推理效率。

> Large Vision-Language Models (LVLMs) represent a significant advancement toward achieving superior multimodal capabilities by enabling powerful Large Language Models (LLMs) to understand visual input. Typically, LVLMs utilize visual encoders, such as CLIP, to transform images into visual tokens, which are then aligned with textual tokens through projection layers before being input into the LLM for inference. Although existing LVLMs have achieved significant success, their inference efficiency is still limited by the substantial number of visual tokens and the potential redundancy among them. To mitigate this issue, we propose Focal Pruning (FoPru), a training-free method that prunes visual tokens based on the attention-based token significance derived from the vision encoder. Specifically, we introduce two alternative pruning strategies: 1) the rank strategy, which leverages all token significance scores to retain more critical tokens in a global view; 2) the row strategy, which focuses on preserving continuous key information in images from a local perspective. Finally, the selected tokens are reordered to maintain their original positional relationships. Extensive experiments across various LVLMs and multimodal datasets demonstrate that our method can prune a large number of redundant tokens while maintaining high accuracy, leading to significant improvements in inference efficiency.

[Arxiv](https://arxiv.org/abs/2411.14164)