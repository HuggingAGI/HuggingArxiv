# 借助权重解耦技术，我们实现了从微调到预训练大型语言模型的模型合并扩展。

发布时间：2024年08月06日

`LLM应用` `人工智能` `软件开发`

> Extend Model Merging from Fine-Tuned to Pre-Trained Large Language Models via Weight Disentanglement

# 摘要

> 合并大型语言模型 (LLM) 的目标是将多个同源 LLM 融合为一个全能模型。理想情况下，共享相同骨干的 LLM 无论经过微调 (FT) 还是预训练 (PT)，都应该能够合并。然而，现有方法通常手动分配模型重要性，仅适用于参数变化相似的 LLM。本文首次尝试将合并技术的适用性从 FT 扩展到 PT LLM。我们发现当前方法在处理 PT LLM 时效果不佳，因此引入了一种基于权重解纠缠 (WIDEN) 的新方法，该方法通过解耦模型权重并进行自适应融合，有效扩展了合并范围。实验中，我们将具有指令遵循技能的 FT LLM Qwen1.5-Chat 与具有多语言能力的 PT LLM Sailor 合并，结果显示 WIDEN 不仅成功注入了 Sailor 的多语言能力，还使 Qwen1.5-Chat 精通东南亚语言，并在基本能力上实现增强。此外，我们还合并了多个 13B FT LLM，WIDEN 实现了指令遵循、数学推理和代码生成技能的平衡融合。

> Merging Large Language Models (LLMs) aims to amalgamate multiple homologous LLMs into one with all the capabilities. Ideally, any LLMs sharing the same backbone should be mergeable, irrespective of whether they are Fine-Tuned (FT) with minor parameter changes or Pre-Trained (PT) with substantial parameter shifts. However, existing methods often manually assign the model importance, rendering them feasible only for LLMs with similar parameter alterations, such as multiple FT LLMs. The diverse parameter changed ranges between FT and PT LLMs pose challenges for current solutions in empirically determining the optimal combination. In this paper, we make a pioneering effort to broaden the applicability of merging techniques from FT to PT LLMs. We initially examine the efficacy of current methods in merging FT and PT LLMs, discovering that they struggle to deal with PT LLMs. Subsequently, we introduce an approach based on WeIght DisENtanglement (WIDEN) to effectively extend the merging scope, which first disentangles model weights into magnitude and direction components, and then performs adaptive fusion by considering their respective contributions. In the experiments, we merge Qwen1.5-Chat (an FT LLM with instruction-following skills) with Sailor (a PT LLM with multilingual abilities) across 7B and 14B model scales. Results reveal that: (1) existing solutions usually fail when merging Sailor, either losing both abilities or only retaining instruction-following skills; (2) WIDEN successfully injects the multilingual abilities of Sailor into Qwen1.5-Chat and make it proficient in Southeast Asian languages, achieving enhancements in the fundamental capabilities. In light of previous research, we also merge multiple 13B FT LLMs and observe that WIDEN achieves a balanced amalgamation of instruction following, mathematical reasoning, and code generation skills.

[Arxiv](https://arxiv.org/abs/2408.03092)