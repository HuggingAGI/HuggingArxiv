# RISSOLE 模型通过块级生成与检索引导，实现了参数效率更高的扩散模型。

发布时间：2024年08月30日

`RAG` `计算机视觉` `人工智能`

> RISSOLE: Parameter-efficient Diffusion Models via Block-wise Generation and Retrieval-Guidance

# 摘要

> 扩散模型虽生成能力出众，但其庞大的参数使其难以适应资源有限的设备。为此，我们探索了块状生成这一高效方案，通过逐块生成而非一次性全图生成，有效减小了模型体积。然而，确保块间连贯性是一大挑战。我们提出的检索增强生成（RAG）方法，巧妙利用检索块来条件化模型训练与生成，确保了块间连贯性。此方法不仅适用于潜在扩散模型，还可扩展至其他去噪扩散模型。通过大量实验，我们验证了该方法在保持模型紧凑与生成质量卓越方面的显著成效。

> Diffusion-based models demonstrate impressive generation capabilities. However, they also have a massive number of parameters, resulting in enormous model sizes, thus making them unsuitable for deployment on resource-constraint devices. Block-wise generation can be a promising alternative for designing compact-sized (parameter-efficient) deep generative models since the model can generate one block at a time instead of generating the whole image at once. However, block-wise generation is also considerably challenging because ensuring coherence across generated blocks can be non-trivial. To this end, we design a retrieval-augmented generation (RAG) approach and leverage the corresponding blocks of the images retrieved by the RAG module to condition the training and generation stages of a block-wise denoising diffusion model. Our conditioning schemes ensure coherence across the different blocks during training and, consequently, during generation. While we showcase our approach using the latent diffusion model (LDM) as the base model, it can be used with other variants of denoising diffusion models. We validate the solution of the coherence problem through the proposed approach by reporting substantive experiments to demonstrate our approach's effectiveness in compact model size and excellent generation quality.

[Arxiv](https://arxiv.org/abs/2408.17095)