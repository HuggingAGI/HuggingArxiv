# 优化思维链推理：通过计划增强解决排列瓶颈

发布时间：2024年10月22日

`LLM应用` `工具利用`

> Optimizing Chain-of-Thought Reasoning: Tackling Arranging Bottleneck via Plan Augmentation

# 摘要

> 大型语言模型的多步推理能力在数学和工具利用等任务中至关重要。当前的研究主要侧重于通过使用思维链（CoT）步骤进行微调来提高这些多步推理任务中的模型性能，但这些方法往往是启发式的，既没有探索也没有解决瓶颈问题。在本研究中，我们将 CoT 推理细分为两个部分：安排和执行，并确定模型的瓶颈主要在于安排而不是执行。基于这一发现，我们提出了一种基于计划的训练和推理方法，引导模型通过抽象计划生成安排步骤。我们在数学（GSM8k）和工具利用（ToolBench）基准上进行了实验。结果表明，与直接使用 CoT 数据进行微调相比，我们的方法在缓解安排瓶颈方面取得了更好的性能，特别是在长距离推理泛化方面表现出色。

> Multi-step reasoning ability of large language models is crucial in tasks such as math and tool utilization. Current researches predominantly focus on enhancing model performance in these multi-step reasoning tasks through fine-tuning with Chain-of-Thought (CoT) steps, yet these methods tend to be heuristic, without exploring nor resolving the bottleneck. In this study, we subdivide CoT reasoning into two parts: arranging and executing, and identify that the bottleneck of models mainly lies in arranging rather than executing. Based on this finding, we propose a plan-based training and reasoning method that guides models to generate arranging steps through abstract plans. We experiment on both math (GSM8k) and tool utilization (ToolBench) benchmarks. Results show that compared to fine-tuning directly with CoT data, our approach achieves a better performance on alleviating arranging bottleneck, particularly excelling in long-distance reasoning generalization.

[Arxiv](https://arxiv.org/abs/2410.16812)