# 自监督偏好优化：让您的语言模型更智能地感知偏好程度

发布时间：2024年09月26日

`LLM理论` `人工智能`

> Self-supervised Preference Optimization: Enhance Your Language Model with Preference Degree Awareness

# 摘要

> 近期，直接偏好优化（DPO）等方法在强化学习与人类反馈（RLHF）中替代奖励模型引起了广泛关注。这些方法通过成对样本的二元交叉熵机制，分别处理偏好与非偏好响应的损失。然而，这种策略虽简化了奖励模型，却忽略了响应间偏好的细微差别。我们认为，这正是LLMs难以充分理解人类偏好的症结所在。为此，我们推出了自监督偏好优化（SPO）框架，结合自监督的偏好程度损失与对齐损失，助力LLMs更精准地把握偏好程度。实验结果显示，SPO不仅能与现有方法无缝融合，还能显著提升性能，达到业界领先水平。详细分析进一步证实了SPO的有效性。代码已公开，详见https://github.com/lijian16/SPO。

> Recently, there has been significant interest in replacing the reward model in Reinforcement Learning with Human Feedback (RLHF) methods for Large Language Models (LLMs), such as Direct Preference Optimization (DPO) and its variants. These approaches commonly use a binary cross-entropy mechanism on pairwise samples, i.e., minimizing and maximizing the loss based on preferred or dis-preferred responses, respectively. However, while this training strategy omits the reward model, it also overlooks the varying preference degrees within different responses. We hypothesize that this is a key factor hindering LLMs from sufficiently understanding human preferences. To address this problem, we propose a novel Self-supervised Preference Optimization (SPO) framework, which constructs a self-supervised preference degree loss combined with the alignment loss, thereby helping LLMs improve their ability to understand the degree of preference. Extensive experiments are conducted on two widely used datasets of different tasks. The results demonstrate that SPO can be seamlessly integrated with existing preference optimization methods and significantly boost their performance to achieve state-of-the-art performance. We also conduct detailed analyses to offer comprehensive insights into SPO, which verifies its effectiveness. The code is available at https://github.com/lijian16/SPO.

[Arxiv](https://arxiv.org/abs/2409.17791)