# MotionCom：结合 LLM 与视频扩散先验，实现自动且具有运动感知能力的图像合成

发布时间：2024年09月16日

`LLM应用` `影视制作`

> MotionCom: Automatic and Motion-Aware Image Composition with LLM and Video Diffusion Prior

# 摘要

> MotionCom 是一种无需训练的图像合成技术，能够自动将目标对象无缝融入新场景，生成动态一致的结果，无需微调或优化。传统方法需手动规划对象放置，且常生成静态图像。MotionCom 利用 LVLM 智能规划和视频扩散先验，简化了合成过程。多模态 CoT 提示与 LVLM 结合，自动规划前景对象的放置，考虑其运动和交互。新方法 MotionPaint 从预训练视频扩散模型中提取运动信息，确保对象无缝整合且具真实运动效果。实验结果显示，MotionCom 在简化规划和生成真实运动图像方面表现卓越。

> This work presents MotionCom, a training-free motion-aware diffusion based image composition, enabling automatic and seamless integration of target objects into new scenes with dynamically coherent results without finetuning or optimization. Traditional approaches in this area suffer from two significant limitations: they require manual planning for object placement and often generate static compositions lacking motion realism. MotionCom addresses these issues by utilizing a Large Vision Language Model (LVLM) for intelligent planning, and a Video Diffusion prior for motion-infused image synthesis, streamlining the composition process. Our multi-modal Chain-of-Thought (CoT) prompting with LVLM automates the strategic placement planning of foreground objects, considering their potential motion and interaction within the scenes. Complementing this, we propose a novel method MotionPaint to distill motion-aware information from pretrained video diffusion models in the generation phase, ensuring that these objects are not only seamlessly integrated but also endowed with realistic motion. Extensive quantitative and qualitative results highlight MotionCom's superiority, showcasing its efficiency in streamlining the planning process and its capability to produce compositions that authentically depict motion and interaction.

[Arxiv](https://arxiv.org/abs/2409.10090)