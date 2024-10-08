# LADEV：机器人操作中视觉-语言-动作模型的语言驱动测试与评估平台

发布时间：2024年10月07日

`LLM应用` `机器人` `人工智能`

> LADEV: A Language-Driven Testing and Evaluation Platform for Vision-Language-Action Models in Robotic Manipulation

# 摘要

> 结合大型语言模型 (LLM) 和视觉语言模型 (VLM) 的最新进展，研究者们推出了视觉-语言-动作 (VLA) 模型，为机器人操作任务提供了一体化解决方案。这些模型通过摄像头图像和自然语言指令，直接生成机器人动作，显著提升了决策与用户交互能力。然而，VLA 模型的数据驱动特性及其不可解释性，使其有效性和鲁棒性的保障充满挑战。为此，我们设计了 LADEV 平台，专门用于 VLA 模型的评估。LADEV 通过语言驱动自动生成模拟环境，减少手动调整，大幅提升测试效率。同时，引入释义机制生成多样任务指令，深入评估语言影响。此外，批量测试方法加速了大规模评估进程。实验证明，LADEV 不仅提升测试效率，还为 VLA 模型评估奠定了坚实基础，推动了更智能机器人系统的发展。

> Building on the advancements of Large Language Models (LLMs) and Vision Language Models (VLMs), recent research has introduced Vision-Language-Action (VLA) models as an integrated solution for robotic manipulation tasks. These models take camera images and natural language task instructions as input and directly generate control actions for robots to perform specified tasks, greatly improving both decision-making capabilities and interaction with human users. However, the data-driven nature of VLA models, combined with their lack of interpretability, makes the assurance of their effectiveness and robustness a challenging task. This highlights the need for a reliable testing and evaluation platform. For this purpose, in this work, we propose LADEV, a comprehensive and efficient platform specifically designed for evaluating VLA models. We first present a language-driven approach that automatically generates simulation environments from natural language inputs, mitigating the need for manual adjustments and significantly improving testing efficiency. Then, to further assess the influence of language input on the VLA models, we implement a paraphrase mechanism that produces diverse natural language task instructions for testing. Finally, to expedite the evaluation process, we introduce a batch-style method for conducting large-scale testing of VLA models. Using LADEV, we conducted experiments on several state-of-the-art VLA models, demonstrating its effectiveness as a tool for evaluating these models. Our results showed that LADEV not only enhances testing efficiency but also establishes a solid baseline for evaluating VLA models, paving the way for the development of more intelligent and advanced robotic systems.

[Arxiv](https://arxiv.org/abs/2410.05191)