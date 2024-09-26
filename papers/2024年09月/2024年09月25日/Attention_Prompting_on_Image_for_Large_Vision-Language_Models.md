# 大型视觉-语言模型中的图像注意力提示

发布时间：2024年09月25日

`LLM应用` `人工智能` `计算机视觉`

> Attention Prompting on Image for Large Vision-Language Models

# 摘要

> 相较于 LLM，LVLM 不仅能处理文本，还能接受图像输入，展现出更多有趣的涌现能力，并在视觉-语言任务中表现出色。借鉴 LLM 中的文本提示，视觉提示技术应运而生，旨在提升 LVLM 的视觉信息感知能力。然而，现有技术仅关注视觉输入，忽略了文本查询，限制了模型遵循指令的能力。为此，我们提出了一种名为“图像注意力提示”的新技术，通过在原始图像上叠加文本查询引导的注意力热图，显著提升了 LVLM 在多任务中的表现。具体而言，我们利用 CLIP 等辅助模型生成与文本查询相关的注意力热图，并将其应用于原始图像，形成 LVLM 的输入。实验结果表明，该技术在 MM-Vet 和 LLaVA-Wild 基准上分别将 LLaVA-1.5 提升了 3.8% 和 2.9%，验证了其有效性。

> Compared with Large Language Models (LLMs), Large Vision-Language Models (LVLMs) can also accept images as input, thus showcasing more interesting emergent capabilities and demonstrating impressive performance on various vision-language tasks. Motivated by text prompting in LLMs, visual prompting has been explored to enhance LVLMs' capabilities of perceiving visual information. However, previous visual prompting techniques solely process visual inputs without considering text queries, limiting the models' ability to follow text instructions to complete tasks. To fill this gap, in this work, we propose a new prompting technique named Attention Prompting on Image, which just simply overlays a text-query-guided attention heatmap on the original input image and effectively enhances LVLM on various tasks. Specifically, we generate an attention heatmap for the input image dependent on the text query with an auxiliary model like CLIP. Then the heatmap simply multiplies the pixel values of the original image to obtain the actual input image for the LVLM. Extensive experiments on various vison-language benchmarks verify the effectiveness of our technique. For example, Attention Prompting on Image improves LLaVA-1.5 by 3.8% and 2.9% on MM-Vet and LLaVA-Wild benchmarks, respectively.

[Arxiv](https://arxiv.org/abs/2409.17143)