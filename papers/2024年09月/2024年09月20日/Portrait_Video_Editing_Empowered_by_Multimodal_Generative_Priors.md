# 多模态生成先验赋能的肖像视频编辑

发布时间：2024年09月20日

`LLM应用` `视频编辑`

> Portrait Video Editing Empowered by Multimodal Generative Priors

# 摘要

> 我们推出了 PortraitGen，一种通过多模态提示实现一致且富有表现力的肖像视频编辑方法。传统方法在 3D 和时间一致性上常遇挑战，且渲染质量和效率不足。为此，我们将视频帧提升至统一的动态 3D 高斯场，确保帧间结构和时间连贯。我们还设计了神经高斯纹理机制，实现复杂风格编辑并达到 100FPS 以上的渲染速度。通过整合大规模 2D 生成模型的知识，我们的方法处理多模态输入。系统还包括表情相似性指导和人脸感知编辑模块，有效应对数据集迭代更新带来的退化问题。实验证明，我们的方法在时间一致性、编辑效率和渲染质量上表现卓越。该方法广泛适用于文本、图像驱动编辑及重新照明等应用，展示了其在视频编辑领域的巨大潜力。更多详情请访问项目页面：https://ustc3dv.github.io/PortraitGen/

> We introduce PortraitGen, a powerful portrait video editing method that achieves consistent and expressive stylization with multimodal prompts. Traditional portrait video editing methods often struggle with 3D and temporal consistency, and typically lack in rendering quality and efficiency. To address these issues, we lift the portrait video frames to a unified dynamic 3D Gaussian field, which ensures structural and temporal coherence across frames. Furthermore, we design a novel Neural Gaussian Texture mechanism that not only enables sophisticated style editing but also achieves rendering speed over 100FPS. Our approach incorporates multimodal inputs through knowledge distilled from large-scale 2D generative models. Our system also incorporates expression similarity guidance and a face-aware portrait editing module, effectively mitigating degradation issues associated with iterative dataset updates. Extensive experiments demonstrate the temporal consistency, editing efficiency, and superior rendering quality of our method. The broad applicability of the proposed approach is demonstrated through various applications, including text-driven editing, image-driven editing, and relighting, highlighting its great potential to advance the field of video editing. Demo videos and released code are provided in our project page: https://ustc3dv.github.io/PortraitGen/

[Arxiv](https://arxiv.org/abs/2409.13591)