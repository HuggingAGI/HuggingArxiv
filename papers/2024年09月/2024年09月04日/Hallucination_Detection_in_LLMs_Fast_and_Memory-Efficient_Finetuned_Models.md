# LLM 中的幻觉检测：快速且内存高效的微调模型

发布时间：2024年09月04日

`LLM应用` `自动驾驶`

> Hallucination Detection in LLMs: Fast and Memory-Efficient Finetuned Models

# 摘要

> 在高风险领域如自动驾驶、医疗和保险中，AI 的不确定性估计至关重要。尽管大型语言模型 (LLM) 近年来备受瞩目，但其幻觉问题在高风险环境下可能带来严重后果。虽然 LLM 表现出色，但其高昂的训练和运行成本（大量计算和内存需求）限制了集成方法的实际应用。为此，我们提出了一种创新方法，能够快速且高效地训练 LLM 集成。实验证明，这种方法不仅能检测幻觉，而且在实际应用中仅需一个 GPU 即可完成训练和推理，极具可行性。

> Uncertainty estimation is a necessary component when implementing AI in high-risk settings, such as autonomous cars, medicine, or insurances. Large Language Models (LLMs) have seen a surge in popularity in recent years, but they are subject to hallucinations, which may cause serious harm in high-risk settings. Despite their success, LLMs are expensive to train and run: they need a large amount of computations and memory, preventing the use of ensembling methods in practice. In this work, we present a novel method that allows for fast and memory-friendly training of LLM ensembles. We show that the resulting ensembles can detect hallucinations and are a viable approach in practice as only one GPU is needed for training and inference.

[Arxiv](https://arxiv.org/abs/2409.02976)