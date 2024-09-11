# 大型语言模型不在乎你的思考方式：为何思维链提示在主观任务中失效

发布时间：2024年09月09日

`LLM理论` `人工智能`

> Larger Language Models Don't Care How You Think: Why Chain-of-Thought Prompting Fails in Subjective Tasks

# 摘要

> 在大型语言模型 (LLM) 中，In-Context Learning (ICL) 已成为执行自然语言任务的主导技术，因其无需更新模型参数。ICL 承诺以极低成本将 LLM 提升至竞争或领先水平。通过在提示中明确推理过程，ICL 可进一步增强，即 Chain-of-Thought (CoT) 提示。然而，最新研究发现，ICL 主要依赖任务先验检索，而非“学习”，尤其在情感和道德等复杂主观领域，先验固化了预测。本研究探讨“启用”推理是否会导致 LLM 中 CoT 格式检索的推理先验不变。令人惊讶的是，对于更大模型，CoT 确实遭遇与 ICL 相同的后验崩溃。代码详见 https://github.com/gchohla/cot-priors。

> In-Context Learning (ICL) in Large Language Models (LLM) has emerged as the dominant technique for performing natural language tasks, as it does not require updating the model parameters with gradient-based methods. ICL promises to "adapt" the LLM to perform the present task at a competitive or state-of-the-art level at a fraction of the computational cost. ICL can be augmented by incorporating the reasoning process to arrive at the final label explicitly in the prompt, a technique called Chain-of-Thought (CoT) prompting. However, recent work has found that ICL relies mostly on the retrieval of task priors and less so on "learning" to perform tasks, especially for complex subjective domains like emotion and morality, where priors ossify posterior predictions. In this work, we examine whether "enabling" reasoning also creates the same behavior in LLMs, wherein the format of CoT retrieves reasoning priors that remain relatively unchanged despite the evidence in the prompt. We find that, surprisingly, CoT indeed suffers from the same posterior collapse as ICL for larger language models. Code is avalaible at https://github.com/gchochla/cot-priors.

[Arxiv](https://arxiv.org/abs/2409.06173)