# 在 LLM 中，如何平衡连续预训练与指令微调，以优化指令跟随能力，是一个关键课题。

发布时间：2024年10月14日

`LLM理论` `人工智能`

> Balancing Continuous Pre-Training and Instruction Fine-Tuning: Optimizing Instruction-Following in LLMs

# 摘要

> 公共使用的 LLM 需要持续预训练以保持数据更新，并通过特定指令微调以准确遵循指令。通常，LLM 分为基础版和指令精炼版。本研究探讨了持续预训练与指令微调的复杂关系，并分析了其对指令遵循能力的影响。此外，指令微调计算量大且需大量手工标注数据。我们旨在找到无需指令数据和微调的高效策略，以获取最新知识和指令遵循能力。通过在 LLaMa 和 Qwen 系列模型上的实证研究，我们全面验证了在不同数据规模和模型设置下的假设。

> Large Language Models (LLMs) for public use require continuous pre-training to remain up-to-date with the latest data. The models also need to be fine-tuned with specific instructions to maintain their ability to follow instructions accurately. Typically, LLMs are released in two versions: the Base LLM, pre-trained on diverse data, and the instruction-refined LLM, additionally trained with specific instructions for better instruction following. The question arises as to which model should undergo continuous pre-training to maintain its instruction-following abilities while also staying current with the latest data. In this study, we delve into the intricate relationship between continuous pre-training and instruction fine-tuning of the LLMs and investigate the impact of continuous pre-training on the instruction following abilities of both the base and its instruction finetuned model. Further, the instruction fine-tuning process is computationally intense and requires a substantial number of hand-annotated examples for the model to learn effectively. This study aims to find the most compute-efficient strategy to gain up-to-date knowledge and instruction-following capabilities without requiring any instruction data and fine-tuning. We empirically prove our findings on the LLaMa 3, 3.1 and Qwen 2, 2.5 family of base and instruction models, providing a comprehensive exploration of our hypotheses across varying sizes of pre-training data corpus and different LLMs settings.

[Arxiv](https://arxiv.org/abs/2410.10739)