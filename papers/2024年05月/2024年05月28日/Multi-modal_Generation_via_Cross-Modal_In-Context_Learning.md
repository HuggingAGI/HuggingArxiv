# 跨模态上下文学习驱动多模态内容生成

发布时间：2024年05月28日

`LLM应用

这篇论文介绍了一种名为MGCC的新方法，它利用大型语言模型（LLM）和扩散模型的结合来处理复杂的多元模态提示序列，以生成新颖的图像。这种方法特别关注于跨模态上下文学习，通过创新的模块来处理文本与图像在LLM嵌入空间中的相互依赖，以及精确生成多对象场景中的对象边界框。因此，这项研究属于LLM的应用范畴，因为它展示了如何将LLM技术应用于图像生成和多模态对话中，以提高生成图像的质量和上下文连贯性。` `图像生成` `多模态学习`

> Multi-modal Generation via Cross-Modal In-Context Learning

# 摘要

> 本研究探讨了如何从复杂的多元模态提示序列中创造新颖图像。尽管现有技术在文本到图像转换上表现不俗，但它们在处理长篇提示时难以捕捉细微之处，且难以维持提示序列的上下文连贯性。特别是当提示涉及多个对象时，生成的图像往往与提示不符。为此，我们开发了一种名为MGCC的新方法，它结合了大型语言模型和扩散模型的力量，通过跨模态上下文学习来生成图像。MGCC包含一个创新的跨模态细化模块，专门用于学习文本与图像在LLM嵌入空间中的相互依赖，以及一个上下文对象定位模块，旨在为多对象场景精确生成对象边界框。MGCC不仅能够生成新颖图像，还能促进多模态对话和文本创作。实验结果显示，在VIST和VisDial两个数据集上，MGCC的表现均优于现有技术，分别达到0.652和0.660的CLIP相似度分数，显著超越了SOTA方法的0.641和0.645。代码已公开：https://github.com/VIROBO-15/MGCC。

> In this work, we study the problem of generating novel images from complex multimodal prompt sequences. While existing methods achieve promising results for text-to-image generation, they often struggle to capture fine-grained details from lengthy prompts and maintain contextual coherence within prompt sequences. Moreover, they often result in misaligned image generation for prompt sequences featuring multiple objects. To address this, we propose a Multi-modal Generation via Cross-Modal In-Context Learning (MGCC) method that generates novel images from complex multimodal prompt sequences by leveraging the combined capabilities of large language models (LLMs) and diffusion models. Our MGCC comprises a novel Cross-Modal Refinement module to explicitly learn cross-modal dependencies between the text and image in the LLM embedding space, and a contextual object grounding module to generate object bounding boxes specifically targeting scenes with multiple objects. Our MGCC demonstrates a diverse range of multimodal capabilities, like novel image generation, the facilitation of multimodal dialogue, and generation of texts. Experimental evaluations on two benchmark datasets, demonstrate the effectiveness of our method. On Visual Story Generation (VIST) dataset with multimodal inputs, our MGCC achieves a CLIP Similarity score of $0.652$ compared to SOTA GILL $0.641$. Similarly, on Visual Dialogue Context (VisDial) having lengthy dialogue sequences, our MGCC achieves an impressive CLIP score of $0.660$, largely outperforming existing SOTA method scoring $0.645$. Code: https://github.com/VIROBO-15/MGCC

![跨模态上下文学习驱动多模态内容生成](../../../paper_images/2405.18304/x2.png)

![跨模态上下文学习驱动多模态内容生成](../../../paper_images/2405.18304/x3.png)

![跨模态上下文学习驱动多模态内容生成](../../../paper_images/2405.18304/x4.png)

![跨模态上下文学习驱动多模态内容生成](../../../paper_images/2405.18304/x5.png)

![跨模态上下文学习驱动多模态内容生成](../../../paper_images/2405.18304/x6.png)

![跨模态上下文学习驱动多模态内容生成](../../../paper_images/2405.18304/x7.png)

[Arxiv](https://arxiv.org/abs/2405.18304)