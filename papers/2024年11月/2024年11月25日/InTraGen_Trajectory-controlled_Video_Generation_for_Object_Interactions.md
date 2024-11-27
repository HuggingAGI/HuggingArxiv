# InTraGen：针对对象交互的轨迹控制视频生成

发布时间：2024年11月25日

`其他` `视频生成` `计算机视觉`

> InTraGen: Trajectory-controlled Video Generation for Object Interactions

# 摘要

> 视频生成领域的进步极大地提升了所创场景的逼真度和质量，这使得开发能让用户将视频生成用作世界模拟器的直观工具备受关注。文本到视频（T2V）生成便是其中一种方式，仅依靠文本描述就能进行视频创作。不过，鉴于文本本身的模糊性以及文本提示所提供的有限时间信息，研究人员探索了像轨迹引导系统这样的额外控制信号，以实现更精准的 T2V 生成。但目前仍缺少评估 T2V 模型能否生成多个对象间真实交互的方法。我们推出了 InTraGen，这是一个用于优化基于轨迹的对象交互场景生成的流程。我们提出了 4 个新的数据集和一种全新的轨迹质量衡量标准，用于评估所提出的 InTraGen 的表现。为达成对象交互，我们引入了带有对象 ID 注入机制的多模态交互编码流程，丰富了对象与环境的交互。我们的成果显示在视觉保真度和定量性能上均有提升。代码和数据集可在 https://github.com/insait-institute/InTraGen 获取。

> Advances in video generation have significantly improved the realism and quality of created scenes. This has fueled interest in developing intuitive tools that let users leverage video generation as world simulators. Text-to-video (T2V) generation is one such approach, enabling video creation from text descriptions only. Yet, due to the inherent ambiguity in texts and the limited temporal information offered by text prompts, researchers have explored additional control signals like trajectory-guided systems, for more accurate T2V generation. Nonetheless, methods to evaluate whether T2V models can generate realistic interactions between multiple objects are lacking. We introduce InTraGen, a pipeline for improved trajectory-based generation of object interaction scenarios. We propose 4 new datasets and a novel trajectory quality metric to evaluate the performance of the proposed InTraGen. To achieve object interaction, we introduce a multi-modal interaction encoding pipeline with an object ID injection mechanism that enriches object-environment interactions. Our results demonstrate improvements in both visual fidelity and quantitative performance. Code and datasets are available at https://github.com/insait-institute/InTraGen

[Arxiv](https://arxiv.org/abs/2411.16804)