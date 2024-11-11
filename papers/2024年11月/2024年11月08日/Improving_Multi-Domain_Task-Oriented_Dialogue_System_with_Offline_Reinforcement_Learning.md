# 通过离线强化学习改进多领域任务导向的对话系统

发布时间：2024年11月08日

`LLM应用` `对话系统` `语言模型`

> Improving Multi-Domain Task-Oriented Dialogue System with Offline Reinforcement Learning

# 摘要

> 任务导向型对话（TOD）系统旨在通过对话完成用户定义的任务。TOD 系统通过利用预训练的大型语言模型朝着端到端建模发展。仅使用监督学习对预训练语言模型进行微调会导致曝光偏差和令牌丢失问题，并使模型偏离完成用户的任务。为了解决这些问题，我们提出了一个利用统一的预训练语言模型 GPT2 作为基础模型的 TOD 系统。它使用监督学习和强化学习（RL）进行优化。使用不可微的奖励函数缓解了 TOD 系统中的问题。奖励是通过成功率和 BLEU 评估指标的加权总和计算的。奖励计算中的成功率和 BLEU 指标引导语言模型完成用户任务，同时确保响应连贯流畅。我们的模型是通过在包含用户话语、信念状态、系统动作和系统响应的对话会话级别上对预训练模型进行微调而获得的。在 MultiWOZ2.1 上的实验结果表明，与基线相比，我们的模型将信息率提高了 1.60％，成功率提高了 3.17％。

> Task-oriented dialogue (TOD) system is designed to accomplish user-defined tasks through dialogues. The TOD system has progressed towards end-to-end modeling by leveraging pre-trained large language models. Fine-tuning the pre-trained language models using only supervised learning leads to the exposure bias and token loss problem and it deviates the models from completing the user's task. To address these issues, we propose a TOD system that leverages a unified pre-trained language model, GPT2, as a base model. It is optimized using supervised learning and reinforcement learning (RL). The issues in the TOD system are mitigated using a non-differentiable reward function. The reward is calculated using the weighted sum of the success rate and BLEU evaluation metrics. The success rate and BLEU metrics in reward calculation guide the language model for user task completion while ensuring a coherent and fluent response. Our model is acquired by fine-tuning a pre-trained model on the dialogue-session level which comprises user utterance, belief state, system act, and system response. Experimental results on MultiWOZ2.1 demonstrate that our model increases the inform rate by 1.60% and the success rate by 3.17% compared to the baseline.

[Arxiv](https://arxiv.org/abs/2411.05340)