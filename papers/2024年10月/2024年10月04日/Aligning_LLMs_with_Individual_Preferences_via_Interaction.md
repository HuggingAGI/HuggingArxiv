# 通过互动，让大型语言模型与个人偏好完美契合

发布时间：2024年10月04日

`LLM应用` `人工智能` `用户体验`

> Aligning LLMs with Individual Preferences via Interaction

# 摘要

> 随着 LLM 能力的不断提升，使其行为与人类价值观和偏好对齐变得尤为重要。尽管现有研究多关注于帮助性、无害性和诚实等通用原则，但个性化和多样化的偏好却常被忽视，这可能影响用户体验的定制化。为此，我们训练了能够“交互对齐”的 LLM，通过多轮对话隐式推断用户的个性化偏好，并动态调整其行为。我们首先创建了 3,310 个不同用户角色，并通过多 LLM 协作生成了 3K+ 多轮对话数据集。随后，我们使用监督微调和强化学习来增强 LLM。为评估效果，我们设计了 ALOE 基准，包含 100 个精选示例和相应指标。实验结果显示，我们的方法能有效实现动态个性化对齐。

> As large language models (LLMs) demonstrate increasingly advanced capabilities, aligning their behaviors with human values and preferences becomes crucial for their wide adoption. While previous research focuses on general alignment to principles such as helpfulness, harmlessness, and honesty, the need to account for individual and diverse preferences has been largely overlooked, potentially undermining customized human experiences. To address this gap, we train LLMs that can ''interact to align'', essentially cultivating the meta-skill of LLMs to implicitly infer the unspoken personalized preferences of the current user through multi-turn conversations, and then dynamically align their following behaviors and responses to these inferred preferences. Our approach involves establishing a diverse pool of 3,310 distinct user personas by initially creating seed examples, which are then expanded through iterative self-generation and filtering. Guided by distinct user personas, we leverage multi-LLM collaboration to develop a multi-turn preference dataset containing 3K+ multi-turn conversations in tree structures. Finally, we apply supervised fine-tuning and reinforcement learning to enhance LLMs using this dataset. For evaluation, we establish the ALOE (ALign With CustOmized PrEferences) benchmark, consisting of 100 carefully selected examples and well-designed metrics to measure the customized alignment performance during conversations. Experimental results demonstrate the effectiveness of our method in enabling dynamic, personalized alignment via interaction.

[Arxiv](https://arxiv.org/abs/2410.03642)