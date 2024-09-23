# 通过内化符号知识，提升小语言模型的 CoT 能力

发布时间：2024年09月19日

`LLM理论` `人工智能`

> : Internalizing Symbolic Knowledge for Distilling Better CoT Capabilities into Small Language Models

# 摘要

> 小型语言模型 (SLM) 因大型语言模型 (LLM) 的高计算需求和隐私问题而备受关注。一些研究通过从 LLM 中提取的思维链 (CoT) 数据微调 SLM，以提升其推理能力。此外，某些 CoT 蒸馏方法引入外部符号知识，以增强 SLM 的知识记忆、推理能力和域外 (OOD) 泛化能力。然而，这增加了计算负担并引入了潜在噪声。本文提出 $\textit{SKIntern}$，一种创新方法，通过渐进式微调，在课程学习的指导下，逐步内化符号知识和少量示例。$\textit{SKIntern}$ 通过高效内化知识，减少计算开销，并在推理时专注于问题，加速推理过程。在域内 (ID) 和域外 (OOD) 任务中，$\textit{SKIntern}$ 在广泛的 SLM 上，性能超越最先进基线 5\% 以上，同时将推理成本降低高达 4 倍。代码将在 \url{https://github.com/Xnhyacinth/SKIntern} 上发布。

> Small Language Models (SLMs) are attracting attention due to the high computational demands and privacy concerns of Large Language Models (LLMs). Some studies fine-tune SLMs using Chains of Thought (CoT) data distilled from LLMs, aiming to enhance their reasoning ability. Furthermore, Some CoT distillation methods introduce external symbolic knowledge into the generation process to improve the limited knowledge memory, reasoning ability and out-of-domain (OOD) generalization of SLMs. However, the introduction of symbolic knowledge increases computational overhead and introduces potential noise. In this paper, we introduce $\textit{SKIntern}$, an innovative approach that empowers SLMs to internalize symbolic knowledge and few-shot examples gradually through a progressive fine-tuning process, guided by a predefined linear decay schedule under curriculum learning. By efficiently internalizing knowledge, $\textit{SKIntern}$ reduces computational overhead and speeds up the reasoning process by focusing solely on the question during inference. It outperforms state-of-the-art baselines by over 5\%, while reducing inference costs (measured in FLOPs) by up to $4\times$ across a wide range of SLMs in both in-domain (ID) and out-of-domain (OOD) tasks. Our code will be available at \url{https://github.com/Xnhyacinth/SKIntern}.

[Arxiv](https://arxiv.org/abs/2409.13183)