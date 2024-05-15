# Hunyuan-DiT：一款强大的多分辨率扩散Transformer，专为精细中文理解而设计

发布时间：2024年05月14日

`Agent

这篇论文介绍了一款名为Hunyuan-DiT的英汉双语文本至图像扩散变换器，它能够根据用户的多轮对话内容生成并优化图像。这个系统不仅涉及文本到图像的转换，还包括了多模态大型语言模型的训练，以及与用户的交互能力，这些特点符合Agent的定义，即一个能够感知环境、做出决策并执行动作的智能实体。因此，这篇论文应被归类为Agent。` `图像生成`

> Hunyuan-DiT: A Powerful Multi-Resolution Diffusion Transformer with Fine-Grained Chinese Understanding

# 摘要

> 我们推出了Hunyuan-DiT，一款精通英汉双语的文本至图像扩散变换器。我们精心打造了其变换器架构、文本编码器及位置编码，并自建了一套数据处理流水线，以迭代优化模型。为深化语言理解，我们训练了多模态大型语言模型，以精炼图像描述。Hunyuan-DiT能与用户进行多轮对话，根据对话内容生成并优化图像。经过50多位专业评估者的全面评估，Hunyuan-DiT在中文图像生成领域超越了其他开源模型，达到了行业新高度。其代码和预训练模型已在github.com/Tencent/HunyuanDiT公开发布。

> We present Hunyuan-DiT, a text-to-image diffusion transformer with fine-grained understanding of both English and Chinese. To construct Hunyuan-DiT, we carefully design the transformer structure, text encoder, and positional encoding. We also build from scratch a whole data pipeline to update and evaluate data for iterative model optimization. For fine-grained language understanding, we train a Multimodal Large Language Model to refine the captions of the images. Finally, Hunyuan-DiT can perform multi-turn multimodal dialogue with users, generating and refining images according to the context. Through our holistic human evaluation protocol with more than 50 professional human evaluators, Hunyuan-DiT sets a new state-of-the-art in Chinese-to-image generation compared with other open-source models. Code and pretrained models are publicly available at github.com/Tencent/HunyuanDiT

[Arxiv](https://arxiv.org/abs/2405.08748)