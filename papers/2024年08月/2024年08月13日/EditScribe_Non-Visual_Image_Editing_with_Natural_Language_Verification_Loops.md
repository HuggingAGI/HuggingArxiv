# EditScribe：借助自然语言验证循环实现非视觉图像编辑

发布时间：2024年08月13日

`LLM应用` `辅助技术` `视觉艺术`

> EditScribe: Non-Visual Image Editing with Natural Language Verification Loops

# 摘要

> 图像编辑过程要求精准的视觉评估与操作，以确保输出符合编辑意图。然而，现有工具未能为视障人士提供便捷交互与充分反馈。为此，我们推出了EditScribe系统，该系统借助大型多模态模型驱动的自然语言验证循环，让图像编辑变得触手可及。用户通过初步的图像描述理解内容，随后以自然语言指令进行编辑。EditScribe执行编辑并提供包括视觉变化概览、AI判断在内的四种反馈，供用户验证。用户可进一步提问以深入了解编辑细节，再进行后续操作。研究显示，EditScribe有效支持视障用户非视觉地完成编辑与验证。我们探讨了不同用户的提示策略及对反馈类型的感知，并分析了自然语言验证循环在视觉创作中的应用潜力。

> Image editing is an iterative process that requires precise visual evaluation and manipulation for the output to match the editing intent. However, current image editing tools do not provide accessible interaction nor sufficient feedback for blind and low vision individuals to achieve this level of control. To address this, we developed EditScribe, a prototype system that makes image editing accessible using natural language verification loops powered by large multimodal models. Using EditScribe, the user first comprehends the image content through initial general and object descriptions, then specifies edit actions using open-ended natural language prompts. EditScribe performs the image edit, and provides four types of verification feedback for the user to verify the performed edit, including a summary of visual changes, AI judgement, and updated general and object descriptions. The user can ask follow-up questions to clarify and probe into the edits or verification feedback, before performing another edit. In a study with ten blind or low-vision users, we found that EditScribe supported participants to perform and verify image edit actions non-visually. We observed different prompting strategies from participants, and their perceptions on the various types of verification feedback. Finally, we discuss the implications of leveraging natural language verification loops to make visual authoring non-visually accessible.

[Arxiv](https://arxiv.org/abs/2408.06632)