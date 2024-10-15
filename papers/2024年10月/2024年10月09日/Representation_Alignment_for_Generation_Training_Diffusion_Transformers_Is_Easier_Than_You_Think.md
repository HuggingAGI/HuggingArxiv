# 生成任务中的表示对齐：训练扩散变换器其实比你想象的更简单

发布时间：2024年10月09日

`LLM理论` `计算机视觉` `生成模型`

> Representation Alignment for Generation: Training Diffusion Transformers Is Easier Than You Think

# 摘要

> 摘要：最新研究发现，扩散模型中的去噪过程能生成有意义的判别性表示，但质量仍不及自监督学习方法。我们认为，训练大规模扩散模型的关键在于有效学习这些表示。通过引入高质量外部视觉表示，而非仅依赖模型自身学习，训练可更高效。我们提出的表示对齐（REPA）方法，将去噪网络中的噪声输入与外部预训练视觉编码器的干净图像表示对齐，显著提升了训练效率和生成质量。例如，SiT训练速度提升17.5倍，400K步内达到7M步SiT-XL模型的性能。最终生成质量达到FID=1.42的业界领先水平。

> 
Abstract:Recent studies have shown that the denoising process in (generative) diffusion models can induce meaningful (discriminative) representations inside the model, though the quality of these representations still lags behind those learned through recent self-supervised learning methods. We argue that one main bottleneck in training large-scale diffusion models for generation lies in effectively learning these representations. Moreover, training can be made easier by incorporating high-quality external visual representations, rather than relying solely on the diffusion models to learn them independently. We study this by introducing a straightforward regularization called REPresentation Alignment (REPA), which aligns the projections of noisy input hidden states in denoising networks with clean image representations obtained from external, pretrained visual encoders. The results are striking: our simple strategy yields significant improvements in both training efficiency and generation quality when applied to popular diffusion and flow-based transformers, such as DiTs and SiTs. For instance, our method can speed up SiT training by over 17.5$\times$, matching the performance (without classifier-free guidance) of a SiT-XL model trained for 7M steps in less than 400K steps. In terms of final generation quality, our approach achieves state-of-the-art results of FID=1.42 using classifier-free guidance with the guidance interval.
    

[Arxiv](https://arxiv.org/pdf/2410.06940)