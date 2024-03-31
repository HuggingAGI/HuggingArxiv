# TextCraftor：用文本编码器掌控图像品质

发布时间：2024年03月27日

`LLM应用` `内容创作` `图像生成`

> TextCraftor: Your Text Encoder Can be Image Quality Controller

# 摘要

> 扩散式文本到图像生成模型，比如 Stable Diffusion，彻底颠覆了内容创作领域，尤其在图像编辑和视频合成方面取得了飞跃性进展。然而，这些模型虽强大，仍存在局限。要生成与文本高度契合的图像并非易事，往往需要多次尝试和精心设计的提示才能达到理想效果。为了克服这些局限，众多研究尝试对预训练的 UNet 扩散模型进行微调，运用了各种技术。但在这些尝试中，文本到图像扩散模型训练的一个核心问题尚未得到充分探讨：我们能否通过微调文本编码器来提升模型性能？我们的研究揭示，不必替换 Stable Diffusion 中的 CLIP 文本编码器，通过我们提出的 TextCraftor 微调方法，就能显著提升性能，无论是在量化评估还是人类评审中都有所体现。更有趣的是，我们的技术还能通过不同文本编码器的微调和插值，实现对图像生成的精确控制。我们还展示了 TextCraftor 与 UNet 微调的互补性，二者结合能进一步提升生成内容的质量。

> Diffusion-based text-to-image generative models, e.g., Stable Diffusion, have revolutionized the field of content generation, enabling significant advancements in areas like image editing and video synthesis. Despite their formidable capabilities, these models are not without their limitations. It is still challenging to synthesize an image that aligns well with the input text, and multiple runs with carefully crafted prompts are required to achieve satisfactory results. To mitigate these limitations, numerous studies have endeavored to fine-tune the pre-trained diffusion models, i.e., UNet, utilizing various technologies. Yet, amidst these efforts, a pivotal question of text-to-image diffusion model training has remained largely unexplored: Is it possible and feasible to fine-tune the text encoder to improve the performance of text-to-image diffusion models? Our findings reveal that, instead of replacing the CLIP text encoder used in Stable Diffusion with other large language models, we can enhance it through our proposed fine-tuning approach, TextCraftor, leading to substantial improvements in quantitative benchmarks and human assessments. Interestingly, our technique also empowers controllable image generation through the interpolation of different text encoders fine-tuned with various rewards. We also demonstrate that TextCraftor is orthogonal to UNet finetuning, and can be combined to further improve generative quality.

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x2.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x3.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x4.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x5.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x6.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x7.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x8.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x9.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x10.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x11.png)

![TextCraftor：用文本编码器掌控图像品质](../../../paper_images/2403.18978/x12.png)

[Arxiv](https://arxiv.org/abs/2403.18978)