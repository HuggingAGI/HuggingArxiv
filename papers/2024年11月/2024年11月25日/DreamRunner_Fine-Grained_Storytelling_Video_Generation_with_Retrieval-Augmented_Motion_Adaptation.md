# DreamRunner：借助检索增强的运动适应实现细粒度的故事讲述视频生成

发布时间：2024年11月25日

`LLM应用`

> DreamRunner: Fine-Grained Storytelling Video Generation with Retrieval-Augmented Motion Adaptation

# 摘要

> 讲故事视频生成（SVG）近来成为一项能创作长且多动作、多场景的视频的任务，这些视频始终能体现输入文本脚本所描述的故事。SVG 在媒体和娱乐的多样化内容创作领域潜力巨大；但也面临重大挑战：（1）对象得展现一系列细粒度、复杂的动作，（2）多个对象要在各场景中持续出现，（3）主题在单个场景内可能需要多个动作且要无缝过渡。为应对这些挑战，我们提出了 DreamRunner 这一新颖的故事转视频生成方法：首先，利用大型语言模型（LLM）构建输入脚本，助力粗粒度的场景规划以及细粒度的对象级布局与动作规划。接着，DreamRunner 推出了检索增强的测试时适应，捕捉每个场景中对象的目标动作先验，基于检索到的视频支持多样的动作定制，利于生成具有复杂、脚本化动作的新视频。最后，我们提出了新颖的基于时空区域的 3D 注意力和先验注入模块 SR3AI，用于细粒度的对象 - 动作绑定和逐帧语义控制。我们把 DreamRunner 与各类 SVG 基线作比较，展现出在角色一致性、文本对齐和顺滑过渡方面的顶尖性能。此外，DreamRunner 在组合文本到视频生成中具有强大的细粒度条件跟随能力，在 T2V-ComBench 上远超基线。最后，通过定性示例验证了 DreamRunner 生成多对象交互的强大能力。

> Storytelling video generation (SVG) has recently emerged as a task to create long, multi-motion, multi-scene videos that consistently represent the story described in the input text script. SVG holds great potential for diverse content creation in media and entertainment; however, it also presents significant challenges: (1) objects must exhibit a range of fine-grained, complex motions, (2) multiple objects need to appear consistently across scenes, and (3) subjects may require multiple motions with seamless transitions within a single scene. To address these challenges, we propose DreamRunner, a novel story-to-video generation method: First, we structure the input script using a large language model (LLM) to facilitate both coarse-grained scene planning as well as fine-grained object-level layout and motion planning. Next, DreamRunner presents retrieval-augmented test-time adaptation to capture target motion priors for objects in each scene, supporting diverse motion customization based on retrieved videos, thus facilitating the generation of new videos with complex, scripted motions. Lastly, we propose a novel spatial-temporal region-based 3D attention and prior injection module SR3AI for fine-grained object-motion binding and frame-by-frame semantic control. We compare DreamRunner with various SVG baselines, demonstrating state-of-the-art performance in character consistency, text alignment, and smooth transitions. Additionally, DreamRunner exhibits strong fine-grained condition-following ability in compositional text-to-video generation, significantly outperforming baselines on T2V-ComBench. Finally, we validate DreamRunner's robust ability to generate multi-object interactions with qualitative examples.

[Arxiv](https://arxiv.org/abs/2411.16657)