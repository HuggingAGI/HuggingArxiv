# 视觉语言模型是上下文价值学习者

发布时间：2024年11月07日

`LLM应用` `机器人` `视觉运动`

> Vision Language Models are In-Context Value Learners

# 摘要

> 从视觉轨迹预测时间进展对于能够学习、适应和改进的智能机器人来说非常重要。然而，在不同任务和领域中学习这种进展估计器或时间价值函数，既需要大量的多样化数据，也需要能够扩展和泛化的方法。为了应对这些挑战，我们提出了生成式价值学习（\GVL），这是一种通用的价值函数估计器，它利用嵌入在视觉语言模型（VLMs）中的世界知识来预测任务进展。由于连续帧之间的强时间相关性，天真地要求 VLM 为视频序列预测值效果不佳。相反，GVL 将价值估计设定为对打乱的视频帧的时间排序问题；这个看似更具挑战性的任务鼓励 VLM 更充分地利用其潜在的语义和时间基础能力，根据感知到的任务进展来区分帧，从而产生明显更好的价值预测。无需任何针对机器人或任务的特定训练，GVL 可以在上下文零样本和少样本的情况下，为包括具有挑战性的双手操作任务在内的不同机器人平台上的 300 多个不同的现实世界任务预测有效的值。此外，我们证明 GVL 允许通过来自不同任务和实例（例如人类视频）的示例进行灵活的多模态上下文学习。GVL 的通用性使各种与视觉运动策略学习相关的下游应用成为可能，包括数据集过滤、成功检测和优势加权回归——所有这些都无需任何模型训练或微调。

> Predicting temporal progress from visual trajectories is important for intelligent robots that can learn, adapt, and improve. However, learning such progress estimator, or temporal value function, across different tasks and domains requires both a large amount of diverse data and methods which can scale and generalize. To address these challenges, we present Generative Value Learning (\GVL), a universal value function estimator that leverages the world knowledge embedded in vision-language models (VLMs) to predict task progress. Naively asking a VLM to predict values for a video sequence performs poorly due to the strong temporal correlation between successive frames. Instead, GVL poses value estimation as a temporal ordering problem over shuffled video frames; this seemingly more challenging task encourages VLMs to more fully exploit their underlying semantic and temporal grounding capabilities to differentiate frames based on their perceived task progress, consequently producing significantly better value predictions. Without any robot or task specific training, GVL can in-context zero-shot and few-shot predict effective values for more than 300 distinct real-world tasks across diverse robot platforms, including challenging bimanual manipulation tasks. Furthermore, we demonstrate that GVL permits flexible multi-modal in-context learning via examples from heterogeneous tasks and embodiments, such as human videos. The generality of GVL enables various downstream applications pertinent to visuomotor policy learning, including dataset filtering, success detection, and advantage-weighted regression -- all without any model training or finetuning.

[Arxiv](https://arxiv.org/abs/2411.04549)