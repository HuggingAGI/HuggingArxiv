# 借助有原则的合成逻辑语料库提升大型语言模型（LLMs）的推理能力

发布时间：2024年11月19日

`LLM应用` `人工智能` `逻辑推理`

> Enhancing Reasoning Capabilities of LLMs via Principled Synthetic Logic Corpus

# 摘要

> 大型语言模型（LLMs）能应对各类任务，然而在推理上却表现不佳。为此，我们提出了“附加逻辑训练（ALT）”，旨在借助程序生成的逻辑推理样本提升 LLMs 的推理能力。我们先是结合符号逻辑理论和过往经验见解确定了设计优质样本的原则。接着，依循这些原则，构建了名为“形式逻辑推导多样”（“FLD”×2）的合成语料库，其中涵盖众多包含未知事实、多样推理规则、多样语言表述以及颇具挑战性干扰项的多步推导样本。最终，实验表明，在 FLD×2 上进行的 ALT 显著增强了包括 LLaMA-3.1-70B 在内的前沿 LLMs 的推理能力，比如在逻辑推理基准上提升多达 30 分，在数学和编码基准上提升多达 10 分，在基准套件 BBH 上提升 5 分。

> Large language models (LLMs) are capable of solving a wide range of tasks, yet they have struggled with reasoning. To address this, we propose $\textbf{Additional Logic Training (ALT)}$, which aims to enhance LLMs' reasoning capabilities by program-generated logical reasoning samples. We first establish principles for designing high-quality samples by integrating symbolic logic theory and previous empirical insights. Then, based on these principles, we construct a synthetic corpus named $\textbf{Formal Logic Deduction Diverse}$ ($\textbf{FLD}$$^{\times 2}$), comprising numerous samples of multi-step deduction with unknown facts, diverse reasoning rules, diverse linguistic expressions, and challenging distractors. Finally, we empirically show that ALT on FLD$^{\times2}$ substantially enhances the reasoning capabilities of state-of-the-art LLMs, including LLaMA-3.1-70B. Improvements include gains of up to 30 points on logical reasoning benchmarks, up to 10 points on math and coding benchmarks, and 5 points on the benchmark suite BBH.

[Arxiv](https://arxiv.org/abs/2411.12498)