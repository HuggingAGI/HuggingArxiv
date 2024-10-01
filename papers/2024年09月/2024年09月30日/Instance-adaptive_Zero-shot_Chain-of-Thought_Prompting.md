# 实例自适应零-shot 思维链提示

发布时间：2024年09月30日

`LLM理论` `人工智能`

> Instance-adaptive Zero-shot Chain-of-Thought Prompting

# 摘要

> 零-shot Chain-of-Thought (CoT) prompting 是一种简单有效的策略，能显著提升大型语言模型 (LLM) 在实际推理任务中的表现。然而，单一任务级别的提示在所有实例中统一应用的效果有限，因为一个提示无法适用于所有情况。更佳的方法应细致考虑提示与每个实例之间的互动。为此，我们引入了一种实例自适应提示算法，通过自适应区分好与坏的提示，作为零-shot CoT 推理的替代方案。具体来说，我们通过信息流的视角分析 LLM，发现从问题到提示和从问题到推理的信息流共同影响推理结果。我们提出，更好的零-shot CoT 推理需要提示从问题中获取语义信息，然后推理直接和间接地从问题和提示中聚合足够的信息。基于此，我们提出了实例自适应提示策略 (IAP)。在 LLaMA-2、LLaMA-3 和 Qwen 上进行的数学、逻辑和常识推理任务实验中，取得了显著改进，表明实例自适应零-shot CoT 提示优于其他任务级别的方法，即使使用精心设计的提示或复杂程序，也凸显了我们在零-shot CoT 推理机制中的发现的重要性。

> Zero-shot Chain-of-Thought (CoT) prompting emerges as a simple and effective strategy for enhancing the performance of large language models (LLMs) in real-world reasoning tasks. Nonetheless, the efficacy of a singular, task-level prompt uniformly applied across the whole of instances is inherently limited since one prompt cannot be a good partner for all, a more appropriate approach should consider the interaction between the prompt and each instance meticulously. This work introduces an instance-adaptive prompting algorithm as an alternative zero-shot CoT reasoning scheme by adaptively differentiating good and bad prompts. Concretely, we first employ analysis on LLMs through the lens of information flow to detect the mechanism under zero-shot CoT reasoning, in which we discover that information flows from question to prompt and question to rationale jointly influence the reasoning results most. We notice that a better zero-shot CoT reasoning needs the prompt to obtain semantic information from the question then the rationale aggregates sufficient information from the question directly and via the prompt indirectly. On the contrary, lacking any of those would probably lead to a bad one. Stem from that, we further propose an instance-adaptive prompting strategy (IAP) for zero-shot CoT reasoning. Experiments conducted with LLaMA-2, LLaMA-3, and Qwen on math, logic, and commonsense reasoning tasks (e.g., GSM8K, MMLU, Causal Judgement) obtain consistent improvement, demonstrating that the instance-adaptive zero-shot CoT prompting performs better than other task-level methods with some curated prompts or sophisticated procedures, showing the significance of our findings in the zero-shot CoT reasoning mechanism.

[Arxiv](https://arxiv.org/abs/2409.20441)