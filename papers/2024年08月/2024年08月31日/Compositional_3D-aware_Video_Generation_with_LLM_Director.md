# LLM 导演下的组合式 3D 视频创作

发布时间：2024年08月31日

`LLM应用` `视频制作` `人工智能`

> Compositional 3D-aware Video Generation with LLM Director

# 摘要

> 文本到视频生成技术在利用先进生成模型和海量网络数据的基础上取得了长足进步，但在精确操控视频中的细节元素（如角色动作、外观及视角变换）方面仍面临挑战。为此，我们创新性地提出了一种三阶段生成方案：首先，借助LLM将复杂文本指令拆解为具体概念的子任务；其次，通过多模态LLM为各概念的3D表现提供初步布局指导；最后，结合2D扩散模型优化图像质量，确保生成画面自然流畅。实验证明，该方法能灵活调控并生成动作丰富、细节精准的高质量视频。更多详情，请访问项目页面：\url{https://aka.ms/c3v}。

> Significant progress has been made in text-to-video generation through the use of powerful generative models and large-scale internet data. However, substantial challenges remain in precisely controlling individual concepts within the generated video, such as the motion and appearance of specific characters and the movement of viewpoints. In this work, we propose a novel paradigm that generates each concept in 3D representation separately and then composes them with priors from Large Language Models (LLM) and 2D diffusion models. Specifically, given an input textual prompt, our scheme consists of three stages: 1) We leverage LLM as the director to first decompose the complex query into several sub-prompts that indicate individual concepts within the video~(\textit{e.g.}, scene, objects, motions), then we let LLM to invoke pre-trained expert models to obtain corresponding 3D representations of concepts. 2) To compose these representations, we prompt multi-modal LLM to produce coarse guidance on the scales and coordinates of trajectories for the objects. 3) To make the generated frames adhere to natural image distribution, we further leverage 2D diffusion priors and use Score Distillation Sampling to refine the composition. Extensive experiments demonstrate that our method can generate high-fidelity videos from text with diverse motion and flexible control over each concept. Project page: \url{https://aka.ms/c3v}.

[Arxiv](https://arxiv.org/abs/2409.00558)