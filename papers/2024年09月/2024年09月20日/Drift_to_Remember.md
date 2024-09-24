# 记忆漂流

发布时间：2024年09月20日

`LLM应用` `人工智能` `神经科学`

> Drift to Remember

# 摘要

> 终身学习在 AI 中模仿生物大脑的持续学习能力，但面临灾难性遗忘的挑战。神经科学研究发现，生物系统中的神经活动会随时间演变，即使输入和任务不变。我们提出 DriftNet，通过探索损失景观中的局部最小值并动态检索任务，缓解新任务学习中的遗忘问题。实验证明，DriftNet 在图像分类和 NLP 任务中表现优异，且能高效处理情感分析和问答等任务，无需全数据集重新训练。在 GPT-2 和 RoBERTa 上的测试显示，DriftNet 是 LLM 中终身学习的强大且经济高效的解决方案。这项研究不仅推动了 AI 模仿生物学习，还深化了我们对生物神经系统适应机制的理解。

> Lifelong learning in artificial intelligence (AI) aims to mimic the biological brain's ability to continuously learn and retain knowledge, yet it faces challenges such as catastrophic forgetting. Recent neuroscience research suggests that neural activity in biological systems undergoes representational drift, where neural responses evolve over time, even with consistent inputs and tasks. We hypothesize that representational drift can alleviate catastrophic forgetting in AI during new task acquisition. To test this, we introduce DriftNet, a network designed to constantly explore various local minima in the loss landscape while dynamically retrieving relevant tasks. This approach ensures efficient integration of new information and preserves existing knowledge. Experimental studies in image classification and natural language processing demonstrate that DriftNet outperforms existing models in lifelong learning. Importantly, DriftNet is scalable in handling a sequence of tasks such as sentiment analysis and question answering using large language models (LLMs) with billions of parameters on a single Nvidia A100 GPU. DriftNet efficiently updates LLMs using only new data, avoiding the need for full dataset retraining. Tested on GPT-2 and RoBERTa, DriftNet is a robust, cost-effective solution for lifelong learning in LLMs. This study not only advances AI systems to emulate biological learning, but also provides insights into the adaptive mechanisms of biological neural systems, deepening our understanding of lifelong learning in nature.

[Arxiv](https://arxiv.org/abs/2409.13997)