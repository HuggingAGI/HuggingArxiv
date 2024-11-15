# 图像再生：借助多模态大型语言模型生成相同图像以评估文本到图像模型

发布时间：2024年11月14日

`LLM应用` `图像生成` `模型评估`

> Image Regeneration: Evaluating Text-to-Image Model via Generating Identical Image with Multimodal Large Language Models

# 摘要

> 扩散模型让图像生成领域重焕活力，在学术研究和艺术表达方面均发挥关键作用。新扩散模型不断涌现，评估文本到图像模型的性能愈发重要。当下的指标着重于将输入文本与生成的图像直接匹配，然而由于跨模态信息不对称，致使评估结果不可靠或不完整。基于此，本研究引入图像再生任务，让 T2I 模型依据参考图像生成图像以进行评估。我们借助 GPT4V 来消除参考图像与 T2I 模型文本输入的差距，使 T2I 模型能理解图像内容。此评估过程得以简化，因为生成图像与参考图像的比较直截了当。引入了两个分别涵盖内容多样和风格多样的评估数据集的再生数据集，用于评估当下现有的领先扩散模型。另外，我们提出 ImageRepainter 框架，通过 MLLM 引导的迭代生成和修订来增强内容理解，进而提升生成图像的质量。我们的综合实验表明了该框架在评估模型生成能力方面的有效性。利用 MLLM，我们证明了强大的 T2M 能够生成更近似参考图像的图像。

> Diffusion models have revitalized the image generation domain, playing crucial roles in both academic research and artistic expression. With the emergence of new diffusion models, assessing the performance of text-to-image models has become increasingly important. Current metrics focus on directly matching the input text with the generated image, but due to cross-modal information asymmetry, this leads to unreliable or incomplete assessment results. Motivated by this, we introduce the Image Regeneration task in this study to assess text-to-image models by tasking the T2I model with generating an image according to the reference image. We use GPT4V to bridge the gap between the reference image and the text input for the T2I model, allowing T2I models to understand image content. This evaluation process is simplified as comparisons between the generated image and the reference image are straightforward. Two regeneration datasets spanning content-diverse and style-diverse evaluation dataset are introduced to evaluate the leading diffusion models currently available. Additionally, we present ImageRepainter framework to enhance the quality of generated images by improving content comprehension via MLLM guided iterative generation and revision. Our comprehensive experiments have showcased the effectiveness of this framework in assessing the generative capabilities of models. By leveraging MLLM, we have demonstrated that a robust T2M can produce images more closely resembling the reference image.

[Arxiv](https://arxiv.org/abs/2411.09449)