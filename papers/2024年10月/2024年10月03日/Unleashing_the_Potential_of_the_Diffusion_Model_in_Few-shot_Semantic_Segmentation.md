# 探索扩散模型在少样本语义分割中的无限可能

发布时间：2024年10月03日

`LLM应用` `计算机视觉` `语义分割`

> Unleashing the Potential of the Diffusion Model in Few-shot Semantic Segmentation

# 摘要

> 扩散模型不仅在图像生成领域大放异彩，还展示了其作为利用未标记数据进行有效预训练的潜力。借鉴其在语义对应和开放词汇分割方面的广泛潜力，我们开始探索使用潜在扩散模型进行少样本语义分割。受到大型语言模型上下文学习能力的启发，少样本语义分割已演变为上下文分割任务，成为评估通用分割模型的关键。我们专注于少样本语义分割，为未来基于扩散的通用模型奠定基础。首先，我们研究了如何促进查询图像与支持图像的交互，提出了自注意力框架内的KV融合方法。接着，我们优化了支持掩码信息的注入，并重新评估了查询掩码的监督方式。基于此，我们构建了简单有效的DiffewS框架，保留了原始扩散模型的生成框架，并充分利用了预训练先验。实验结果显示，我们的方法在多种设置下显著超越了之前的SOTA模型。

> The Diffusion Model has not only garnered noteworthy achievements in the realm of image generation but has also demonstrated its potential as an effective pretraining method utilizing unlabeled data. Drawing from the extensive potential unveiled by the Diffusion Model in both semantic correspondence and open vocabulary segmentation, our work initiates an investigation into employing the Latent Diffusion Model for Few-shot Semantic Segmentation. Recently, inspired by the in-context learning ability of large language models, Few-shot Semantic Segmentation has evolved into In-context Segmentation tasks, morphing into a crucial element in assessing generalist segmentation models. In this context, we concentrate on Few-shot Semantic Segmentation, establishing a solid foundation for the future development of a Diffusion-based generalist model for segmentation. Our initial focus lies in understanding how to facilitate interaction between the query image and the support image, resulting in the proposal of a KV fusion method within the self-attention framework. Subsequently, we delve deeper into optimizing the infusion of information from the support mask and simultaneously re-evaluating how to provide reasonable supervision from the query mask. Based on our analysis, we establish a simple and effective framework named DiffewS, maximally retaining the original Latent Diffusion Model's generative framework and effectively utilizing the pre-training prior. Experimental results demonstrate that our method significantly outperforms the previous SOTA models in multiple settings.

[Arxiv](https://arxiv.org/abs/2410.02369)