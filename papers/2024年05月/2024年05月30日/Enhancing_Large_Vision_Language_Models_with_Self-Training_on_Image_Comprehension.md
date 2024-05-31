# 提升大型视觉语言模型在图像理解方面的能力：自我训练的探索

发布时间：2024年05月30日

`LLM应用

理由：这篇论文介绍了一种针对大型视觉语言模型（LVLMs）的自训练方法——STIC，该方法旨在通过模型自身生成的数据来减少对高质量视觉语言数据的依赖，并提升模型的图像理解和推理能力。这种方法直接应用于LLM的实际应用场景中，即通过自训练技术优化视觉语言模型的性能，属于LLM应用的范畴。论文中提到的自训练方法和其在提升模型性能方面的应用，都是针对LLM在实际任务中的应用进行的研究和优化，因此归类为LLM应用。` `计算机视觉`

> Enhancing Large Vision Language Models with Self-Training on Image Comprehension

# 摘要

> 大型视觉语言模型（LVLMs）结合了LLMs与预训练视觉编码器，赋予模型理解图像输入并进行推理的能力。然而，获取提升这一能力所需的高质量视觉语言数据既昂贵又费力。自训练方法在单一模态领域已证明有效，通过模型自身生成的数据减少了对标记数据的依赖。但针对LVLMs特有的视觉感知与推理能力进行自训练仍具挑战。为此，我们提出了专为图像理解设计的自训练方法——STIC。首先，模型利用未标记图像自我构建图像描述偏好数据集，通过逐步提示生成偏好描述，而非偏好描述则源自损坏图像或误导提示。为增强对视觉信息的推理，模型重用少量指令调整数据，并结合自我生成的图像描述。STIC在七个基准测试中显著提升了4.0%的平均性能，同时减少了70%的监督微调数据需求。深入研究STIC的各个方面，揭示了其利用大量未标记图像进行自我训练的潜力。相关代码和数据已公开。

> Large vision language models (LVLMs) integrate large language models (LLMs) with pre-trained vision encoders, thereby activating the perception capability of the model to understand image inputs for different queries and conduct subsequent reasoning. Improving this capability requires high-quality vision-language data, which is costly and labor-intensive to acquire. Self-training approaches have been effective in single-modal settings to alleviate the need for labeled data by leveraging model's own generation. However, effective self-training remains a challenge regarding the unique visual perception and reasoning capability of LVLMs. To address this, we introduce Self-Training on Image Comprehension (STIC), which emphasizes a self-training approach specifically for image comprehension. First, the model self-constructs a preference dataset for image descriptions using unlabeled images. Preferred responses are generated through a step-by-step prompt, while dis-preferred responses are generated from either corrupted images or misleading prompts. To further self-improve reasoning on the extracted visual information, we let the model reuse a small portion of existing instruction-tuning data and append its self-generated image descriptions to the prompts. We validate the effectiveness of STIC across seven different benchmarks, demonstrating substantial performance gains of 4.0% on average while using 70% less supervised fine-tuning data than the current method. Further studies investigate various components of STIC and highlight its potential to leverage vast quantities of unlabeled images for self-training. Code and data are made publicly available.

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x1.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x2.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x3.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x4.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x5.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x6.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x7.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x8.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x9.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x10.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x11.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x12.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x13.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x14.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x15.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x16.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x17.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x18.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x19.png)

![提升大型视觉语言模型在图像理解方面的能力：自我训练的探索](../../../paper_images/2405.19716/x20.png)

[Arxiv](https://arxiv.org/abs/2405.19716)