# Surgical-LVLM：掌握大型视觉-语言模型，助力机器人手术中的场景化视觉问答

发布时间：2024年03月22日

`LLM应用

这篇论文介绍了Surgical-LVLM，一种专为复杂手术环境设计的大型视觉语言模型，它通过预训练的大型视觉语言模型和专用的视觉感知模块来提高在复杂手术环境中的视觉问答能力。这种模型特别强调了在医疗领域中的应用，尤其是在自动化手术指导方面。因此，它属于LLM应用类别，因为它展示了大型语言模型在特定领域（即医疗手术）的应用和优化。` `机器人`

> Surgical-LVLM: Learning to Adapt Large Vision-Language Model for Grounded Visual Question Answering in Robotic Surgery

# 摘要

> 近期，手术视觉问答（Surgical-VQA）及其相关区域定位技术的发展，为机器人和医疗领域带来了新的希望，特别是在个性化手术指导的自动化方法上。尽管如此，现有模型在处理复杂情况时，由于识别长距离依赖和多模态信息对齐的能力不足，往往只能提供简单的答案。为此，我们推出了Surgical-LVLM，一种专为复杂手术环境设计的大型视觉语言模型。借助预训练的大型视觉语言模型和专用的视觉感知LoRA（VP-LoRA）模块，Surgical-LVLM在理解手术中的复杂视觉语言任务上表现卓越。我们还开发了Token-Interaction（TIT）模块，以增强视觉定位模块与大型视觉语言模型（LVLM）语言响应在潜在空间中的交互。通过在EndoVis-17-VQLA、EndoVis-18-VQLA及新引入的EndoVis对话数据集上的测试，Surgical-LVLM展现了其卓越性能，为自动化手术指导领域树立了新的标杆。

> Recent advancements in Surgical Visual Question Answering (Surgical-VQA) and related region grounding have shown great promise for robotic and medical applications, addressing the critical need for automated methods in personalized surgical mentorship. However, existing models primarily provide simple structured answers and struggle with complex scenarios due to their limited capability in recognizing long-range dependencies and aligning multimodal information. In this paper, we introduce Surgical-LVLM, a novel personalized large vision-language model tailored for complex surgical scenarios. Leveraging the pre-trained large vision-language model and specialized Visual Perception LoRA (VP-LoRA) blocks, our model excels in understanding complex visual-language tasks within surgical contexts. In addressing the visual grounding task, we propose the Token-Interaction (TIT) module, which strengthens the interaction between the grounding module and the language responses of the Large Visual Language Model (LVLM) after projecting them into the latent space. We demonstrate the effectiveness of Surgical-LVLM on several benchmarks, including EndoVis-17-VQLA, EndoVis-18-VQLA, and a newly introduced EndoVis Conversations dataset, which sets new performance standards. Our work contributes to advancing the field of automated surgical mentorship by providing a context-aware solution.

[Arxiv](https://arxiv.org/abs/2405.10948)