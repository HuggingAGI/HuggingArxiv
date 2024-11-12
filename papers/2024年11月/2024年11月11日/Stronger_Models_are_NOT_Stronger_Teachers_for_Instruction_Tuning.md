# 更强的模型并非用于指令调优的更强教师

发布时间：2024年11月11日

`LLM应用` `语言模型` `指令调整`

> Stronger Models are NOT Stronger Teachers for Instruction Tuning

# 摘要

> 指令调整已被广泛采用，以确保大型语言模型（LLM）有效地遵循用户指令。LLM 由此产生的指令遵循能力在很大程度上依赖于用于调整的指令数据集。最近，合成指令数据集已成为一种经济上可行的解决方案，为 LLM 提供多样化和高质量的指令。然而，现有的方法通常假设更大或更强的模型是指令调整的更强教师，因此简单地将这些模型用作对合成指令的响应生成器。在本文中，我们对这一普遍采用的假设提出了挑战。我们在五个基础模型和二十个响应生成器上进行的广泛实验表明，更大更强的模型不一定是较小模型的更强教师。我们将这种现象称为“更大模型的悖论”。我们观察到，现有的指标不能准确预测响应生成器的有效性，因为它们忽略了教师和被微调的基础模型之间的兼容性。因此，我们开发了一种新的指标，称为兼容性调整奖励（CAR），以衡量响应生成器的有效性。我们在五个基础模型上的实验表明，CAR 几乎优于所有基线。

> Instruction tuning has been widely adopted to ensure large language models (LLMs) follow user instructions effectively. The resulting instruction-following capabilities of LLMs heavily rely on the instruction datasets used for tuning. Recently, synthetic instruction datasets have emerged as an economically viable solution to provide LLMs diverse and high-quality instructions. However, existing approaches typically assume that larger or stronger models are stronger teachers for instruction tuning, and hence simply adopt these models as response generators to the synthetic instructions. In this paper, we challenge this commonly-adopted assumption. Our extensive experiments across five base models and twenty response generators reveal that larger and stronger models are not necessarily stronger teachers of smaller models. We refer to this phenomenon as the Larger Models' Paradox. We observe that existing metrics cannot precisely predict the effectiveness of response generators since they ignore the compatibility between teachers and base models being fine-tuned. We thus develop a novel metric, named as Compatibility-Adjusted Reward (CAR) to measure the effectiveness of response generators. Our experiments across five base models demonstrate that CAR outperforms almost all baselines.

[Arxiv](https://arxiv.org/abs/2411.07133)