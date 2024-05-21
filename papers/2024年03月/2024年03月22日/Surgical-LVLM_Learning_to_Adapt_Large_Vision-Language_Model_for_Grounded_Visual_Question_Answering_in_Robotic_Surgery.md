# Surgical-LVLM：掌握大型视觉-语言模型，为机器人手术中的视觉问答任务提供精准适应性

发布时间：2024年03月22日

`LLM应用

理由：这篇论文介绍了Surgical-LVLM，一种专为复杂手术场景设计的大型视觉语言模型，并详细说明了其在手术视觉问答（Surgical-VQA）和区域定位技术中的应用。论文强调了该模型在处理复杂视觉语言任务时的优越性能，并通过实验证明了其在特定数据集上的性能提升。这表明论文主要关注于大型语言模型（LLM）在特定应用领域（即手术指导自动化）的实际应用和改进，因此属于LLM应用分类。` `机器人`

> Surgical-LVLM: Learning to Adapt Large Vision-Language Model for Grounded Visual Question Answering in Robotic Surgery

# 摘要

> 近期，手术视觉问答（Surgical-VQA）及其相关区域定位技术的发展，为机器人和医疗领域带来了新的希望，特别是在个性化手术指导的自动化方法上。尽管如此，现有模型在处理复杂情况时，因识别长距离依赖和多模态信息对齐的能力不足，往往只能提供简单的结构化答案。为此，我们推出了Surgical-LVLM，一种专为复杂手术场景设计的大型视觉语言模型。通过结合预训练的大型视觉语言模型与专门的视觉感知LoRA（VP-LoRA）模块，Surgical-LVLM在处理手术环境中的复杂视觉语言任务时表现卓越。我们还开发了Token-Interaction（TIT）模块，以增强定位模块与大型视觉语言模型（LVLM）语言响应在潜在空间中的交互。在多个测试中，包括EndoVis-17-VQLA、EndoVis-18-VQLA及新引入的EndoVis对话数据集，Surgical-LVLM均刷新了性能记录。我们的研究为自动化手术指导领域提供了上下文感知的解决方案，推动了该领域的进步。

> Recent advancements in Surgical Visual Question Answering (Surgical-VQA) and related region grounding have shown great promise for robotic and medical applications, addressing the critical need for automated methods in personalized surgical mentorship. However, existing models primarily provide simple structured answers and struggle with complex scenarios due to their limited capability in recognizing long-range dependencies and aligning multimodal information. In this paper, we introduce Surgical-LVLM, a novel personalized large vision-language model tailored for complex surgical scenarios. Leveraging the pre-trained large vision-language model and specialized Visual Perception LoRA (VP-LoRA) blocks, our model excels in understanding complex visual-language tasks within surgical contexts. In addressing the visual grounding task, we propose the Token-Interaction (TIT) module, which strengthens the interaction between the grounding module and the language responses of the Large Visual Language Model (LVLM) after projecting them into the latent space. We demonstrate the effectiveness of Surgical-LVLM on several benchmarks, including EndoVis-17-VQLA, EndoVis-18-VQLA, and a newly introduced EndoVis Conversations dataset, which sets new performance standards. Our work contributes to advancing the field of automated surgical mentorship by providing a context-aware solution.

[Arxiv](https://arxiv.org/abs/2405.10948)