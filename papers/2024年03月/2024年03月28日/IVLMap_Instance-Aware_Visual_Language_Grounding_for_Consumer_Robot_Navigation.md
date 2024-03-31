# IVLMap：为消费者机器人导航设计的实例感知视觉与语言互动定位系统。

发布时间：2024年03月28日

`Agent` `机器人` `视觉与语言导航`

> IVLMap: Instance-Aware Visual Language Grounding for Consumer Robot Navigation

# 摘要

> 视觉与语言导航（VLN）任务考验着机器人在逼真场景中依据人类自然语言提示进行导航的能力。最新研究尝试通过构建环境的语义空间地图，并借助大型语言模型的推理能力，来指导机器人的行动。但这些方法在处理具体实例和属性级别的导航任务时存在局限，因为它们难以识别同一物体的不同个体。为解决这一问题，我们提出了一种创新方法——实例感知视觉语言地图（IVLMap），它通过融合机器人收集的RGBD视频数据和特别设计的鸟瞰图自然语言索引，赋予机器人进行实例级和属性级语义映射的能力。这种索引细致到具体实例和属性级别。特别是，IVLMap与大型语言模型结合使用时，能够将自然语言转换为带有具体实例和属性信息的导航目标，实现精准定位，并能根据自然语言指令完成零次学习的端到端导航任务。通过大量导航实验验证，我们的方法能将导航精度提升14.4%。相关代码和演示可在 https://ivlmap.github.io/ 查看。

> Vision-and-Language Navigation (VLN) is a challenging task that requires a robot to navigate in photo-realistic environments with human natural language promptings. Recent studies aim to handle this task by constructing the semantic spatial map representation of the environment, and then leveraging the strong ability of reasoning in large language models for generalizing code for guiding the robot navigation. However, these methods face limitations in instance-level and attribute-level navigation tasks as they cannot distinguish different instances of the same object. To address this challenge, we propose a new method, namely, Instance-aware Visual Language Map (IVLMap), to empower the robot with instance-level and attribute-level semantic mapping, where it is autonomously constructed by fusing the RGBD video data collected from the robot agent with special-designed natural language map indexing in the bird's-in-eye view. Such indexing is instance-level and attribute-level. In particular, when integrated with a large language model, IVLMap demonstrates the capability to i) transform natural language into navigation targets with instance and attribute information, enabling precise localization, and ii) accomplish zero-shot end-to-end navigation tasks based on natural language commands. Extensive navigation experiments are conducted. Simulation results illustrate that our method can achieve an average improvement of 14.4\% in navigation accuracy. Code and demo are released at https://ivlmap.github.io/.

[Arxiv](https://arxiv.org/abs/2403.19336)