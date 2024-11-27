# DreamRunner：借助检索增强的运动适应实现细粒度的故事讲述视频生成
发布时间：2024年11月25日


> DreamRunner: Fine-Grained Storytelling Video Generation with Retrieval-Augmented Motion Adaptation
>
> 讲故事视频生成（SVG）近来成为一项能创作长且多动作、多场景的视频的任务，这些视频始终能体现输入文本脚本所描述的故事。SVG 在媒体和娱乐的多样化内容创作领域潜力巨大；但也面临重大挑战：（1）对象得展现一系列细粒度、复杂的动作，（2）多个对象要在各场景中持续出现，（3）主题在单个场景内可能需要多个动作且要无缝过渡。为应对这些挑战，我们提出了 DreamRunner 这一新颖的故事转视频生成方法：首先，利用大型语言模型（LLM）构建输入脚本，助力粗粒度的场景规划以及细粒度的对象级布局与动作规划。接着，DreamRunner 推出了检索增强的测试时适应，捕捉每个场景中对象的目标动作先验，基于检索到的视频支持多样的动作定制，利于生成具有复杂、脚本化动作的新视频。最后，我们提出了新颖的基于时空区域的 3D 注意力和先验注入模块 SR3AI，用于细粒度的对象 - 动作绑定和逐帧语义控制。我们把 DreamRunner 与各类 SVG 基线作比较，展现出在角色一致性、文本对齐和顺滑过渡方面的顶尖性能。此外，DreamRunner 在组合文本到视频生成中具有强大的细粒度条件跟随能力，在 T2V-ComBench 上远超基线。最后，通过定性示例验证了 DreamRunner 生成多对象交互的强大能力。
>
> https://arxiv.org/abs/2411.16657

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.16657](https://arxiv.org/abs/2411.16657)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)