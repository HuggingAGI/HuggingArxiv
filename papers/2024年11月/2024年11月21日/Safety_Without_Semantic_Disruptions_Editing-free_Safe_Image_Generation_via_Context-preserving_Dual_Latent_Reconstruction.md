# 安全且语义不中断：借助上下文保留的双重潜在重建达成无编辑的安全图像生成

发布时间：2024年11月21日

`LLM应用` `人工智能` `图像生成`

> Safety Without Semantic Disruptions: Editing-free Safe Image Generation via Context-preserving Dual Latent Reconstruction

# 摘要

> 在大型且未经整理的数据集上训练多模态生成模型，可能致使用户接触到有害、不安全、有争议或文化不适宜的输出。尽管已提出模型编辑来消除或过滤嵌入和潜在空间中的不良概念，但其可能无意损害已学习的流形，扭曲语义相近的概念。我们指出了当前模型编辑技术的局限，表明即便是良性且相近的概念也可能出现偏差。为满足安全内容生成的需求，我们提出了一种模块化、动态的解决方案，借助安全上下文嵌入以及在潜在空间中运用可调加权求和的双重重建过程来生成更安全的图像。我们的方法在不影响已学习流形结构完整性的前提下，保留了全局上下文。我们在安全图像生成基准测试中取得了领先成果，同时实现了模型安全性的可控变化。我们明确了安全与审查之间的权衡，这为道德人工智能模型的发展提供了必要视角。我们会发布代码。
  关键词：文本到图像模型、生成式人工智能、安全、可靠性、模型编辑

> Training multimodal generative models on large, uncurated datasets can result in users being exposed to harmful, unsafe and controversial or culturally-inappropriate outputs. While model editing has been proposed to remove or filter undesirable concepts in embedding and latent spaces, it can inadvertently damage learned manifolds, distorting concepts in close semantic proximity. We identify limitations in current model editing techniques, showing that even benign, proximal concepts may become misaligned. To address the need for safe content generation, we propose a modular, dynamic solution that leverages safety-context embeddings and a dual reconstruction process using tunable weighted summation in the latent space to generate safer images. Our method preserves global context without compromising the structural integrity of the learned manifolds. We achieve state-of-the-art results on safe image generation benchmarks, while offering controllable variation of model safety. We identify trade-offs between safety and censorship, which presents a necessary perspective in the development of ethical AI models. We will release our code.
  Keywords: Text-to-Image Models, Generative AI, Safety, Reliability, Model Editing

[Arxiv](https://arxiv.org/abs/2411.13982)