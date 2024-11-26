# 借助具有测试时和训练时监督的批判模型来提升 LLM 的推理能力

发布时间：2024年11月25日

`LLM应用` `推理模型`

> Enhancing LLM Reasoning via Critique Models with Test-Time and Training-Time Supervision

# 摘要

> 训练大型语言模型（LLMs）在作出回应前多花时间思考和反思，这对于在科学、编码和数学等领域有效解决复杂推理任务极为关键。然而，像自我反思和自我纠正这类机制的成效取决于模型准确评估自身表现的能力，而这可能会受初始准确率、问题难度以及缺乏外部反馈等因素所限。在本文中，我们深入探究了一种将推理和评论模型角色分离的双人范式，其中评论模型在测试和训练时都为推理（演员）模型提供步骤级反馈。我们首先提出了 AutoMathCritique，这是一个自动且可扩展的收集评论数据的框架，由此生成了一个包含 76,321 个响应与步骤级反馈配对的数据集。用此数据集对语言模型进行微调，能让它们为数学推理生成自然语言反馈。我们证明，评论模型在测试时持续提升演员在困难查询上的表现，尤其是在加大推理时间计算的情况下。受这些发现的启发，我们将基于评论的监督引入演员的自我训练过程，提出了一种循环评论的自我改进方法。实验表明，该方法提高了演员的探索效率和解决方案的多样性，特别是在棘手的查询上，造就了更强大的推理模型。最后，我们初步尝试通过评论监督来训练自我对话推理模型，并展示了其潜力。我们的代码和数据集在 \href{https://mathcritique.github.io/}{https://mathcritique.github.io/} 。

> Training large language models (LLMs) to spend more time thinking and reflection before responding is crucial for effectively solving complex reasoning tasks in fields such as science, coding, and mathematics. However, the effectiveness of mechanisms like self-reflection and self-correction depends on the model's capacity to accurately assess its own performance, which can be limited by factors such as initial accuracy, question difficulty, and the lack of external feedback. In this paper, we delve into a two-player paradigm that separates the roles of reasoning and critique models, where the critique model provides step-level feedback to supervise the reasoning (actor) model during both test-time and train-time. We first propose AutoMathCritique, an automated and scalable framework for collecting critique data, resulting in a dataset of $76,321$ responses paired with step-level feedback. Fine-tuning language models with this dataset enables them to generate natural language feedback for mathematical reasoning. We demonstrate that the critique models consistently improve the actor's performance on difficult queries at test-time, especially when scaling up inference-time computation. Motivated by these findings, we introduce the critique-based supervision to the actor's self-training process, and propose a critique-in-the-loop self-improvement method. Experiments show that the method improves the actor's exploration efficiency and solution diversity, especially on challenging queries, leading to a stronger reasoning model. Lastly, we take the preliminary step to explore training self-talk reasoning models via critique supervision and showcase its potential. Our code and datasets are at \href{https://mathcritique.github.io/}{https://mathcritique.github.io/}.

[Arxiv](https://arxiv.org/abs/2411.16579)