# Surgical-LVLM：掌握大型视觉-语言模型，助力机器人手术中的场景化视觉问答

发布时间：2024年03月22日

`LLM应用

理由：这篇论文介绍了Surgical-LVLM，一种专为复杂手术场景设计的大型视觉语言模型，并详细说明了其在手术视觉问答（Surgical-VQA）和相关区域定位技术中的应用。论文强调了该模型在处理复杂视觉语言任务上的优越性能，并通过多个基准测试展示了其效果。这表明论文主要关注的是大型语言模型（LLM）在特定应用领域（即手术指导）的实际应用和性能提升，因此属于LLM应用分类。` `机器人`

> Surgical-LVLM: Learning to Adapt Large Vision-Language Model for Grounded Visual Question Answering in Robotic Surgery

# 摘要

> 近期，手术视觉问答（Surgical-VQA）及其相关区域定位技术的发展，为机器人和医疗领域带来了新的希望，满足了个性化手术指导中自动化方法的迫切需求。尽管如此，现有模型在处理复杂场景时，由于识别长距离依赖和多模态信息对齐的能力有限，往往只能提供简单的结构化答案。为此，我们推出了Surgical-LVLM，一种专为复杂手术场景设计的大型视觉语言模型。借助预训练的大型视觉语言模型和特制的视觉感知LoRA（VP-LoRA）模块，Surgical-LVLM在理解手术环境中的复杂视觉语言任务上表现卓越。针对视觉定位任务，我们创新性地提出了Token-Interaction（TIT）模块，该模块在潜在空间中加强了定位模块与大型视觉语言模型（LVLM）语言响应之间的交互。通过在EndoVis-17-VQLA、EndoVis-18-VQLA及新引入的EndoVis对话数据集等多个基准上的测试，Surgical-LVLM展现了其卓越性能，为自动化手术指导领域树立了新的标杆。我们的研究为推动该领域的发展提供了上下文感知的解决方案。

> Recent advancements in Surgical Visual Question Answering (Surgical-VQA) and related region grounding have shown great promise for robotic and medical applications, addressing the critical need for automated methods in personalized surgical mentorship. However, existing models primarily provide simple structured answers and struggle with complex scenarios due to their limited capability in recognizing long-range dependencies and aligning multimodal information. In this paper, we introduce Surgical-LVLM, a novel personalized large vision-language model tailored for complex surgical scenarios. Leveraging the pre-trained large vision-language model and specialized Visual Perception LoRA (VP-LoRA) blocks, our model excels in understanding complex visual-language tasks within surgical contexts. In addressing the visual grounding task, we propose the Token-Interaction (TIT) module, which strengthens the interaction between the grounding module and the language responses of the Large Visual Language Model (LVLM) after projecting them into the latent space. We demonstrate the effectiveness of Surgical-LVLM on several benchmarks, including EndoVis-17-VQLA, EndoVis-18-VQLA, and a newly introduced EndoVis Conversations dataset, which sets new performance standards. Our work contributes to advancing the field of automated surgical mentorship by providing a context-aware solution.

[Arxiv](https://arxiv.org/abs/2405.10948)