# 大型语言模型在自然语言生成评估中扮演着积极批评者的角色

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Large Language Models Are Active Critics in NLG Evaluation

# 摘要

> 传统上，评估自然语言生成（NLG）系统依赖于大型语言模型（LLM）的两个关键输入：明确的任务定义和预设的评估标准。这种方法将 LLM 视为“被动批评者”，严格遵循人类设定的标准。然而，随着新任务的出现，文本质量的评估标准可能大相径庭，导致传统方法难以适应多样化的任务需求。为此，我们提出了 Active-Critic，一种让 LLM 成为“主动批评者”的新评估协议。该协议分两步进行：首先，LLM 从数据中推断任务并设定评估标准；其次，动态优化提示，使 LLM 的评分更贴近人类判断，并提供详细的评估解释。实验结果显示，Active-Critic 在多个 NLG 任务中表现优于现有方法，且在少量标注数据下仍展现出高效性和可解释性。我们将在 GitHub 上公开代码和数据。

> The conventional paradigm of using large language models (LLMs) for evaluating natural language generation (NLG) systems typically relies on two key inputs: (1) a clear definition of the NLG task to be evaluated and (2) a list of pre-defined evaluation criteria. This process treats LLMs as ''passive critics,'' strictly following human-defined criteria for evaluation. However, as new NLG tasks emerge, the criteria for assessing text quality can vary greatly. Consequently, these rigid evaluation methods struggle to adapt to diverse NLG tasks without extensive prompt engineering customized for each specific task. To address this limitation, we introduce Active-Critic, a novel LLM-based NLG evaluation protocol that enables LLMs to function as ''active critics.'' Specifically, our protocol comprises two key stages. In the first stage, the LLM is instructed to infer the target NLG task and establish relevant evaluation criteria from the data. Building on this self-inferred information, the second stage dynamically optimizes the prompt to guide the LLM toward more human-aligned scoring decisions, while also generating detailed explanations to justify its evaluations. Experiments across four NLG evaluation tasks show that our approach achieves stronger alignment with human judgments than state-of-the-art evaluation methods. Our comprehensive analysis further highlights the effectiveness and explainability of Active-Critic with only a small amount of labeled data. We will share our code and data on GitHub.

[Arxiv](https://arxiv.org/abs/2410.10724)