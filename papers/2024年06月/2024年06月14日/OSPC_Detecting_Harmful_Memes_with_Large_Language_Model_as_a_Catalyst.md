# OSPC：借助大型语言模型之力，精准识别有害模因

发布时间：2024年06月14日

`LLM应用

理由：这篇论文主要描述了一种利用大型语言模型（LLM）和其他技术（如图像标题生成、光学字符识别）来检测和分类有害模因的方法。这种方法特别针对新加坡的多元文化和多语言环境，展示了LLM在实际应用中的效能，尤其是在处理多语言内容和提升系统性能方面。因此，它属于LLM应用类别。` `网络安全` `社交媒体`

> OSPC: Detecting Harmful Memes with Large Language Model as a Catalyst

# 摘要

> 模因在网络上的快速传播，既表达个人观点，也加剧了社会偏见和歧视的扩散。本研究针对新加坡多元文化及多语言环境，提出了一种创新的检测有害模因的方法。该方法融合了图像标题生成、光学字符识别及大型语言模型分析，以全面识别和分类有害模因。我们采用BLIP模型生成图像标题，PP-OCR与TrOCR进行多语言文本识别，Qwen LLM进行精细语言理解，有效识别英语、中文、马来语及泰米尔语中的有害模因内容。为提升系统性能，我们利用GPT-4V标记的额外数据进行方法微调，旨在将GPT-4V对有害模因的识别能力融入我们的系统。该框架在AI新加坡举办的在线安全奖挑战赛中荣登公共排行榜首位，AUROC高达0.7749，准确率达0.7087，显著领先于其他团队。与以往基准相比，我们的方法表现更佳，FLAVA的AUROC为0.5695，VisualBERT为0.5561。

> Memes, which rapidly disseminate personal opinions and positions across the internet, also pose significant challenges in propagating social bias and prejudice. This study presents a novel approach to detecting harmful memes, particularly within the multicultural and multilingual context of Singapore. Our methodology integrates image captioning, Optical Character Recognition (OCR), and Large Language Model (LLM) analysis to comprehensively understand and classify harmful memes. Utilizing the BLIP model for image captioning, PP-OCR and TrOCR for text recognition across multiple languages, and the Qwen LLM for nuanced language understanding, our system is capable of identifying harmful content in memes created in English, Chinese, Malay, and Tamil. To enhance the system's performance, we fine-tuned our approach by leveraging additional data labeled using GPT-4V, aiming to distill the understanding capability of GPT-4V for harmful memes to our system. Our framework achieves top-1 at the public leaderboard of the Online Safety Prize Challenge hosted by AI Singapore, with the AUROC as 0.7749 and accuracy as 0.7087, significantly ahead of the other teams. Notably, our approach outperforms previous benchmarks, with FLAVA achieving an AUROC of 0.5695 and VisualBERT an AUROC of 0.5561.

![OSPC：借助大型语言模型之力，精准识别有害模因](../../../paper_images/2406.09779/pipeline.jpg)

![OSPC：借助大型语言模型之力，精准识别有害模因](../../../paper_images/2406.09779/ocrdata.jpg)

[Arxiv](https://arxiv.org/abs/2406.09779)