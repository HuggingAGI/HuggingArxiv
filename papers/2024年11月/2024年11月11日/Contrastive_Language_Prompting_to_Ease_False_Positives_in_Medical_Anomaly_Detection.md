# 通过对比语言提示来减轻医疗异常检测中的误报情况

发布时间：2024年11月11日

`LLM应用` `异常检测`

> Contrastive Language Prompting to Ease False Positives in Medical Anomaly Detection

# 摘要

> 预训练的视觉语言模型——对比语言图像预训练（CLIP），凭借文本提示能出色完成各类下游任务，像查找图像或者定位图像中的区域。虽说 CLIP 的多模态数据能力强大，可在专业领域（比如医疗应用）中仍有局限。正因如此，诸如 BioMedCLIP、MedCLIP-SAMv2 等众多 CLIP 变体应运而生，但与正常区域相关的假阳性问题依然存在。所以，我们致力于提出一个简单却关键的目标——在医学异常检测中降低假阳性。我们引入了一种对比语言提示（CLAP）方法，它同时利用了正文本提示和负文本提示。这种直白的方法通过对给定图像中正向提示的视觉关注来识别潜在病变区域。为减少假阳性，我们借助负向提示来降低对正常区域的关注。针对包含六个生物医学基准的 BMAD 数据集展开的大量实验表明，CLAP 方法提升了异常检测性能。我们未来的规划包括开发一种自动化的精细提示方法，以便更实用。

> A pre-trained visual-language model, contrastive language-image pre-training (CLIP), successfully accomplishes various downstream tasks with text prompts, such as finding images or localizing regions within the image. Despite CLIP's strong multi-modal data capabilities, it remains limited in specialized environments, such as medical applications. For this purpose, many CLIP variants-i.e., BioMedCLIP, and MedCLIP-SAMv2-have emerged, but false positives related to normal regions persist. Thus, we aim to present a simple yet important goal of reducing false positives in medical anomaly detection. We introduce a Contrastive LAnguage Prompting (CLAP) method that leverages both positive and negative text prompts. This straightforward approach identifies potential lesion regions by visual attention to the positive prompts in the given image. To reduce false positives, we attenuate attention on normal regions using negative prompts. Extensive experiments with the BMAD dataset, including six biomedical benchmarks, demonstrate that CLAP method enhances anomaly detection performance. Our future plans include developing an automated fine prompting method for more practical usage.

[Arxiv](https://arxiv.org/abs/2411.07546)