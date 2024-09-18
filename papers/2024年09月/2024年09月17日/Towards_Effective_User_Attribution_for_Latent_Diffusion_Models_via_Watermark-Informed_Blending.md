# 利用水印信息混合技术，实现潜在扩散模型的用户归属优化

发布时间：2024年09月17日

`LLM应用` `图像生成` `版权保护`

> Towards Effective User Attribution for Latent Diffusion Models via Watermark-Informed Blending

# 摘要

> 多模态大型语言模型的迅猛发展，使得从文本生成超现实图像成为现实。然而，未经授权使用的担忧也随之而来，限制了其广泛应用。传统水印方法复杂且影响图像质量。为此，我们推出了TEAWIB框架，通过水印信息混合实现潜在扩散模型的有效用户归属。TEAWIB采用即用型配置，无缝集成用户特定水印，确保用户无需修改模型参数即可应用预设参数，同时保持图像质量。像素级嵌入的噪声和增强操作进一步提升了水印图像的安全性和稳定性。实验证明，TEAWIB在感知质量和归属准确性方面表现卓越，达到了行业领先水平。

> Rapid advancements in multimodal large language models have enabled the creation of hyper-realistic images from textual descriptions. However, these advancements also raise significant concerns about unauthorized use, which hinders their broader distribution. Traditional watermarking methods often require complex integration or degrade image quality. To address these challenges, we introduce a novel framework Towards Effective user Attribution for latent diffusion models via Watermark-Informed Blending (TEAWIB). TEAWIB incorporates a unique ready-to-use configuration approach that allows seamless integration of user-specific watermarks into generative models. This approach ensures that each user can directly apply a pre-configured set of parameters to the model without altering the original model parameters or compromising image quality. Additionally, noise and augmentation operations are embedded at the pixel level to further secure and stabilize watermarked images. Extensive experiments validate the effectiveness of TEAWIB, showcasing the state-of-the-art performance in perceptual quality and attribution accuracy.

[Arxiv](https://arxiv.org/abs/2409.10958)