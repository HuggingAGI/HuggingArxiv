# 基于事后再生强化学习的交互式对话代理

发布时间：2024年11月07日

`Agent` `医疗保健` `慈善捐赠`

> Interactive Dialogue Agents via Reinforcement Learning on Hindsight Regenerations

# 摘要

> 近期大型语言模型（LLMs）的进步让对话代理能够生成极为自然且合理的文本。然而，当下的 LLM 语言生成主要聚焦于精准回应问题和请求，并给出单一有效的回答。实际上，众多真实对话是互动性的，意味着代理的言辞会对其对话伙伴产生影响、引出信息或者改变其观点。在从医疗保健到偏好获取等诸多对话任务中，思考代理如何有效引导对话是一项关键能力。现有的用于微调对话代理以完成此类任务的方法依赖于整理一定量的专家数据。但这样做往往需要理解对话伙伴的潜在认知过程，这是人类和基于人类数据训练的 LLM 都难以可靠做到的。我们的关键发现是，尽管 LLM 或许不擅长预先或在正在进行的对话中确定引导对话的有效策略，但它们能够在事后，也就是看到对话伙伴的回应之后做到。我们借助这一事实来重写和扩充现有的次优数据，并通过离线强化学习（RL）训练出一个比提示和从未改动的人类示范中学习更出色的代理。我们将我们的方法应用于需要理解人类心理状态、智能交互和说服的两个领域：心理健康支持和慈善捐赠募集。我们在与真实人类进行的用户研究结果显示，我们的方法大幅优于现有的最先进对话代理。

> Recent progress on large language models (LLMs) has enabled dialogue agents to generate highly naturalistic and plausible text. However, current LLM language generation focuses on responding accurately to questions and requests with a single effective response. In reality, many real dialogues are interactive, meaning an agent's utterances will influence their conversational partner, elicit information, or change their opinion. Accounting for how an agent can effectively steer a conversation is a crucial ability in many dialogue tasks, from healthcare to preference elicitation. Existing methods for fine-tuning dialogue agents to accomplish such tasks would rely on curating some amount of expert data. However, doing so often requires understanding the underlying cognitive processes of the conversational partner, which is a skill neither humans nor LLMs trained on human data can reliably do. Our key insight is that while LLMs may not be adept at identifying effective strategies for steering conversations a priori, or in the middle of an ongoing conversation, they can do so post-hoc, or in hindsight, after seeing how their conversational partner responds. We use this fact to rewrite and augment existing suboptimal data, and train via offline reinforcement learning (RL) an agent that outperforms both prompting and learning from unaltered human demonstrations. We apply our approach to two domains that require understanding human mental state, intelligent interaction, and persuasion: mental health support, and soliciting charitable donations. Our results in a user study with real humans show that our approach greatly outperforms existing state-of-the-art dialogue agents.

[Arxiv](https://arxiv.org/abs/2411.05194)