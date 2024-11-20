# 针对大型语言模型的自我进化奖励学习

发布时间：2024年11月01日

`LLM应用` `语言模型`

> Self-Evolved Reward Learning for LLMs

# 摘要

> 强化学习从人类反馈（RLHF）是让语言模型契合人类偏好的关键技术，在诸如 GPT-4、ChatGPT 以及 Llama 2 等对话模型的成功中起着关键作用。运用 RLHF 的核心难题在于训练可靠的奖励模型（RM），这依赖于通常由人类专家或先进的人工智能系统提供的高质量标签。这些方法成本可能较高，还可能引入影响语言模型响应的偏差。随着语言模型的进步，人类输入在进一步提升其性能方面可能效力渐弱。在本文中，我们提出了自我进化奖励学习（SER）这一新方法，其中 RM 生成额外的训练数据来迭代改进自身。我们在 HH-RLHF 和 UltraFeedback 等多个数据集上，使用 Mistral 和 Llama 3 等模型进行了大量实验，并将 SER 与各种基线进行了对比。我们的结果显示，即便人类标注的数据有限，从自我反馈中学习也能有力提升 RM 性能，进而增强大型语言模型（LLMs）的能力。

> Reinforcement Learning from Human Feedback (RLHF) is a crucial technique for aligning language models with human preferences, playing a pivotal role in the success of conversational models like GPT-4, ChatGPT, and Llama 2. A core challenge in employing RLHF lies in training a reliable reward model (RM), which relies on high-quality labels typically provided by human experts or advanced AI system. These methods can be costly and may introduce biases that affect the language model's responses. As language models improve, human input may become less effective in further enhancing their performance. In this paper, we propose Self-Evolved Reward Learning (SER), a novel approach where the RM generates additional training data to iteratively improve itself. We conducted extensive experiments on multiple datasets such as HH-RLHF and UltraFeedback, using models like Mistral and Llama 3, and compare SER against various baselines. Our results demonstrate that even with limited human-annotated data, learning from self-feedback can robustly enhance RM performance, thereby boosting the capabilities of large language models (LLMs).

[Arxiv](https://arxiv.org/abs/2411.00418)