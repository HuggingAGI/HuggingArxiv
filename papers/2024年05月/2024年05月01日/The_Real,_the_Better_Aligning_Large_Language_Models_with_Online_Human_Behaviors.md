# 追求真实，更上一层楼：使大型语言模型与网民在线行为同步。

发布时间：2024年05月01日

`LLM应用` `人工智能`

> The Real, the Better: Aligning Large Language Models with Online Human Behaviors

# 摘要

> 为防止大型语言模型（LLM）生成无益或有害的回答，对其对齐的研究和应用已相当广泛。但训练周期的漫长和固有的偏好偏差限制了其适应网络中多样化的人类偏好。本论文提出了一种名为“基于人类行为的强化学习（RLHB）”的对齐框架，该框架直接利用在线真实人类行为来调整 LLM。在生成对抗网络的框架下，训练生成器以模仿预期的人类行为做出回应，同时鉴别器负责判断查询、回答和人类行为的组合是否源自真实的在线情境。自然语言的行为建模和多模型联合训练机制，确保了在线对齐的活跃性和可持续性。实验结果通过人工和自动化评估验证了我们提出方法的有效性。

> Large language model alignment is widely used and studied to avoid LLM producing unhelpful and harmful responses. However, the lengthy training process and predefined preference bias hinder adaptation to online diverse human preferences. To this end, this paper proposes an alignment framework, called Reinforcement Learning with Human Behavior (RLHB), to align LLMs by directly leveraging real online human behaviors. By taking the generative adversarial framework, the generator is trained to respond following expected human behavior; while the discriminator tries to verify whether the triplets of query, response, and human behavior come from real online environments. Behavior modeling in natural-language form and the multi-model joint training mechanism enable an active and sustainable online alignment. Experimental results confirm the effectiveness of our proposed methods by both human and automatic evaluations.

[Arxiv](https://arxiv.org/abs/2405.00578)