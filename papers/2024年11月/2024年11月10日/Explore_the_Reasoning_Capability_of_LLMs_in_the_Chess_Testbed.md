# 探索大型语言模型（LLMs）在国际象棋测试平台中的推理能力

发布时间：2024年11月10日

`LLM应用` `人工智能`

> Explore the Reasoning Capability of LLMs in the Chess Testbed

# 摘要

> 推理是人类智力的核心能力。近年来，随着大规模数据集的出现，预训练的大型语言模型已经出现了新的能力，包括推理。然而，这些模型在长期、复杂的推理任务上仍然存在困难，比如下棋。基于专家棋手采用将长期战略玩法与短期战术玩法以及语言解释相结合的双重方法这一观察，我们提出通过整合注释的战略和战术来提高大型语言模型在下棋中的推理能力。具体来说，我们收集了一个名为 MATE 的数据集，其中包含 100 万个由国际象棋专家注释了战略和战术的候选走法的棋局位置。我们对 LLaMA-3-8B 模型进行了微调，并将其与最先进的商业语言模型在选择更好的国际象棋走法的任务中进行了比较。我们的实验表明，我们的模型比 GPT、Claude 和 Gemini 模型表现更好。我们发现语言解释可以增强大型语言模型的推理能力。

> Reasoning is a central capability of human intelligence. In recent years, with the advent of large-scale datasets, pretrained large language models have emerged with new capabilities, including reasoning. However, these models still struggle with long-term, complex reasoning tasks, such as playing chess. Based on the observation that expert chess players employ a dual approach combining long-term strategic play with short-term tactical play along with language explanation, we propose improving the reasoning capability of large language models in chess by integrating annotated strategy and tactic. Specifically, we collect a dataset named MATE, which consists of 1 million chess positions with candidate moves annotated by chess experts for strategy and tactics. We finetune the LLaMA-3-8B model and compare it against state-of-the-art commercial language models in the task of selecting better chess moves. Our experiments show that our models perform better than GPT, Claude, and Gemini models. We find that language explanations can enhance the reasoning capability of large language models.

[Arxiv](https://arxiv.org/abs/2411.06655)