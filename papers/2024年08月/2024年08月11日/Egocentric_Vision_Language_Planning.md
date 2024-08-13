# 自我中心视觉语言规划

发布时间：2024年08月11日

`Agent` `家庭自动化` `人工智能`

> Egocentric Vision Language Planning

# 摘要

> 我们尝试通过大型多模态模型 (LMMs) 和文本到图像模型，打造一个更通用的具身代理。LMMs 虽擅长通过符号抽象进行长期任务规划，但在物理世界的定位上常显不足，难以准确识别图像中的物体位置。为此，我们提出了一种创新方法——以自我为中心的视觉语言规划 (EgoPlan)，旨在从自我中心视角处理家庭场景中的长期任务。该模型通过扩散模型模拟状态与动作间的动态关系，并融合风格转换和光流技术，以提升环境适应性。实验表明，EgoPlan 在家庭场景中从自我中心视角显著提升了长期任务的成功率，超越了传统基线。

> We explore leveraging large multi-modal models (LMMs) and text2image models to build a more general embodied agent. LMMs excel in planning long-horizon tasks over symbolic abstractions but struggle with grounding in the physical world, often failing to accurately identify object positions in images. A bridge is needed to connect LMMs to the physical world. The paper proposes a novel approach, egocentric vision language planning (EgoPlan), to handle long-horizon tasks from an egocentric perspective in varying household scenarios. This model leverages a diffusion model to simulate the fundamental dynamics between states and actions, integrating techniques like style transfer and optical flow to enhance generalization across different environmental dynamics. The LMM serves as a planner, breaking down instructions into sub-goals and selecting actions based on their alignment with these sub-goals, thus enabling more generalized and effective decision-making. Experiments show that EgoPlan improves long-horizon task success rates from the egocentric view compared to baselines across household scenarios.

[Arxiv](https://arxiv.org/abs/2408.05802)