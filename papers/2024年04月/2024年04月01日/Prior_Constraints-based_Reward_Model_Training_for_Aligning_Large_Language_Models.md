# 通过先验约束引导的奖励模型训练，实现大型语言模型的精准对齐。

发布时间：2024年04月01日

`LLM理论` `人工智能`

> Prior Constraints-based Reward Model Training for Aligning Large Language Models

# 摘要

> 在大型语言模型（LLMs）的强化学习中，引入人类反馈来训练奖励模型，通常采用排名损失和对比对的方式。但这个过程存在一个问题：由于训练奖励模型时缺少限制，导致奖励分数在强化学习中无序扩展。为此，我们提出了一种名为PCRM的先验约束奖励模型训练方法，以解决这一难题。PCRM在训练过程中引入了长度比和输出间余弦相似度的先验约束，用以调整优化强度和控制分数间隔。我们通过比较PCRM与人类偏好的排名相关性，以及其在通过RL对LLMs进行对齐的效果，全面评估了该方法。实验结果显示，PCRM通过有效限制奖励分数的扩展，显著提升了对齐效果。此外，我们的方法还能轻松融合进其他基于排名的对齐方法，如直接偏好优化，并能持续提升性能。

> Reinforcement learning with human feedback for aligning large language models (LLMs) trains a reward model typically using ranking loss with comparison pairs.However, the training procedure suffers from an inherent problem: the uncontrolled scaling of reward scores during reinforcement learning due to the lack of constraints while training the reward model.This paper proposes a Prior Constraints-based Reward Model (namely PCRM) training method to mitigate this problem. PCRM incorporates prior constraints, specifically, length ratio and cosine similarity between outputs of each comparison pair, during reward model training to regulate optimization magnitude and control score margins. We comprehensively evaluate PCRM by examining its rank correlation with human preferences and its effectiveness in aligning LLMs via RL. Experimental results demonstrate that PCRM significantly improves alignment performance by effectively constraining reward score scaling. As another bonus, our method is easily integrated into arbitrary rank-based alignment methods, such as direct preference optimization, and can yield consistent improvement.

[Arxiv](https://arxiv.org/abs/2404.00978)