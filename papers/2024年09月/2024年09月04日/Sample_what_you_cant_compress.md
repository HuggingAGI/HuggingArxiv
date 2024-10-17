# 采撷那些难以压缩的精华

发布时间：2024年09月04日

`其他` `计算机视觉` `图像处理`

> Sample what you cant compress

# 摘要

> 在学习图像表示时，基本自编码器常产生模糊结果。通过加入对抗性（GAN）和感知损失等额外惩罚，重建质量得以提升，但这些方法缺乏理论依据。与此同时，扩散技术在生成高质量、清晰图像方面表现出色，且有坚实的理论支撑。我们的研究首次将自编码器与扩散结合，展示了在扩散损失下联合学习连续编码器和解码器的有效性。与基于GAN的自编码器相比，我们的方法不仅重建质量更佳，且更易调整。此外，所得表示也更易被潜在扩散模型处理。由于解码器具有随机性，它能生成确定性潜在表示中未包含的细节，因此我们称此方法为“采样你无法压缩的内容”（SWYCC）。

> 
Abstract:For learned image representations, basic autoencoders often produce blurry results. Reconstruction quality can be improved by incorporating additional penalties such as adversarial (GAN) and perceptual losses. Arguably, these approaches lack a principled interpretation. Concurrently, in generative settings diffusion has demonstrated a remarkable ability to create crisp, high quality results and has solid theoretical underpinnings (from variational inference to direct study as the Fisher Divergence). Our work combines autoencoder representation learning with diffusion and is, to our knowledge, the first to demonstrate the efficacy of jointly learning a continuous encoder and decoder under a diffusion-based loss. We demonstrate that this approach yields better reconstruction quality as compared to GAN-based autoencoders while being easier to tune. We also show that the resulting representation is easier to model with a latent diffusion model as compared to the representation obtained from a state-of-the-art GAN-based loss. Since our decoder is stochastic, it can generate details not encoded in the otherwise deterministic latent representation; we therefore name our approach "Sample what you can't compress", or SWYCC for short.
    

[Arxiv](https://arxiv.org/pdf/2409.02529)