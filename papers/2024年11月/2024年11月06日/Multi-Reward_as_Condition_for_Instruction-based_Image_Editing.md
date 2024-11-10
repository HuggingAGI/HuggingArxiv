# 多奖励作为基于指令的图像编辑的条件

发布时间：2024年11月06日

`LLM应用` `图像编辑` `视觉语言模型`

> Multi-Reward as Condition for Instruction-based Image Editing

# 摘要

> 高质量的训练三元组（指令、原始图像、编辑图像）对于基于指令的图像编辑至关重要。主要的训练数据集（例如，InsPix2Pix）是使用并非为图像编辑而训练的文本到图像生成模型（例如，Stable Diffusion、DALL-E）创建的。因此，这些数据集存在指令遵循不准确、细节保留不佳和生成伪影的问题。在本文中，我们提议用多视角奖励数据而不是改进真实图像质量来解决训练数据质量问题。1）我们首先基于一流的 LVLM（大型视觉语言模型），即我们案例中的 GPT-4o，设计了一个定量指标系统，从三个角度评估生成质量，即指令遵循、细节保留和生成质量。对于每个角度，我们收集了 0 到 5 之间的定量分数以及关于真实编辑图像中特定失败点的文本描述性反馈，从而形成了一个高质量的编辑奖励数据集，即 RewardEdit20K。2）我们进一步提出了一个新颖的训练框架，将被视为多奖励的指标输出无缝集成到编辑模型中，以便从不完美的训练三元组中学习。在训练期间，奖励分数和文本描述被编码为嵌入，并作为辅助条件输入到编辑模型的潜在空间和 U-Net 中。在推理期间，我们将这些额外条件设置为最高分且没有失败点的文本描述，以实现最佳生成结果。实验表明，我们的多奖励条件模型在两个流行的编辑管道（即 InsPix2Pix 和 SmartEdit）上优于无奖励的对应模型。代码和数据集将发布。

> High-quality training triplets (instruction, original image, edited image) are essential for instruction-based image editing. Predominant training datasets (e.g., InsPix2Pix) are created using text-to-image generative models (e.g., Stable Diffusion, DALL-E) which are not trained for image editing. Accordingly, these datasets suffer from inaccurate instruction following, poor detail preserving, and generation artifacts. In this paper, we propose to address the training data quality issue with multi-perspective reward data instead of refining the ground-truth image quality. 1) we first design a quantitative metric system based on best-in-class LVLM (Large Vision Language Model), i.e., GPT-4o in our case, to evaluate the generation quality from 3 perspectives, namely, instruction following, detail preserving, and generation quality. For each perspective, we collected quantitative score in $0\sim 5$ and text descriptive feedback on the specific failure points in ground-truth edited images, resulting in a high-quality editing reward dataset, i.e., RewardEdit20K. 2) We further proposed a novel training framework to seamlessly integrate the metric output, regarded as multi-reward, into editing models to learn from the imperfect training triplets. During training, the reward scores and text descriptions are encoded as embeddings and fed into both the latent space and the U-Net of the editing models as auxiliary conditions. During inference, we set these additional conditions to the highest score with no text description for failure points, to aim at the best generation outcome. Experiments indicate that our multi-reward conditioned model outperforms its no-reward counterpart on two popular editing pipelines, i.e., InsPix2Pix and SmartEdit. The code and dataset will be released.

[Arxiv](https://arxiv.org/abs/2411.04713)