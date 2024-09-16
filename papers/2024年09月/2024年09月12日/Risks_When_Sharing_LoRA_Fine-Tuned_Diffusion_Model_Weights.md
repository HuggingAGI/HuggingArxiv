# 共享 LoRA 微调扩散模型权重时需警惕的风险

发布时间：2024年09月12日

`LLM应用` `网络安全` `人工智能`

> Risks When Sharing LoRA Fine-Tuned Diffusion Model Weights

# 摘要

> 随着生成模型的发展和预训练扩散模型的普及，用户可以轻松微调这些模型，生成符合自然语言描述的个人图像或物品。参数高效微调（如 LoRA）已成为节省微调过程中内存和计算资源的主流方法。然而，一个关键问题是：共享模型权重时，微调所用的私人图像是否会被泄露？本文探讨了在实际场景中，仅通过模型权重而非微调图像或提示，对手能否重建私人图像。我们设计并构建了一个变分网络自动编码器，通过模型权重重建图像，并提出了一种高效的训练方法。研究结果令人震惊：对手确实能生成与私人图像身份相同的图像。更令人担忧的是，现有防御手段（包括差分隐私方法）都无法在不损害模型效用的情况下，完全保护微调数据的隐私。

> With the emerging trend in generative models and convenient public access to diffusion models pre-trained on large datasets, users can fine-tune these models to generate images of personal faces or items in new contexts described by natural language. Parameter efficient fine-tuning (PEFT) such as Low Rank Adaptation (LoRA) has become the most common way to save memory and computation usage on the user end during fine-tuning. However, a natural question is whether the private images used for fine-tuning will be leaked to adversaries when sharing model weights. In this paper, we study the issue of privacy leakage of a fine-tuned diffusion model in a practical setting, where adversaries only have access to model weights, rather than prompts or images used for fine-tuning. We design and build a variational network autoencoder that takes model weights as input and outputs the reconstruction of private images. To improve the efficiency of training such an autoencoder, we propose a training paradigm with the help of timestep embedding. The results give a surprising answer to this research question: an adversary can generate images containing the same identities as the private images. Furthermore, we demonstrate that no existing defense method, including differential privacy-based methods, can preserve the privacy of private data used for fine-tuning a diffusion model without compromising the utility of a fine-tuned model.

[Arxiv](https://arxiv.org/abs/2409.08482)