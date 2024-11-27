# 关于文本到图像生成的自动评估：任务分解框架、提炼训练与元评估基准

发布时间：2024年11月23日

`LLM应用` `图像生成` `模型评估`

> Automatic Evaluation for Text-to-image Generation: Task-decomposed Framework, Distilled Training, and Meta-evaluation Benchmark

# 摘要

> 在扩散模型的显著进步的驱动下，文本到图像生成取得了重大突破，这使得对生成图像的自动质量评估需求迫切。当下最先进的自动评估方法高度依赖多模态大型语言模型（MLLMs），尤其是像 GPT-4o 这般强大的商业模型。虽说这些模型效果显著，但高昂的成本限制了其在大规模评估中的可扩展性。选用开源的 MLLMs 是个替代选择，然而，与商业 MLLMs 相比，由于处理多模态数据的能力存在明显局限，其性能不尽人意。为应对这些难题，我们首先基于 GPT-4o 提出了一个任务分解评估框架，用于自动构建新的训练数据集，将复杂的评估任务拆解为更简单的子任务，有效降低了学习的复杂度。基于此数据集，我们设计了创新的训练策略，把 GPT-4o 的评估能力有效地提炼到一个 7B 开源 MLLM——MiniCPM-V-2.6 中。另外，为了可靠且全面地评估先前的工作和我们提出的模型，我们手动标注了一个元评估基准，其中涵盖了生成图像的思维链解释以及质量分数。实验结果显示，我们提炼的开源 MLLM 明显优于当前最先进的基于 GPT-4o 的基线 VIEScore，在与人类判断的 Spearman 和 Kendall 相关性方面提升超过 4.6％。

> Driven by the remarkable progress in diffusion models, text-to-image generation has made significant strides, creating a pressing demand for automatic quality evaluation of generated images. Current state-of-the-art automatic evaluation methods heavily rely on Multi-modal Large Language Models (MLLMs), particularly powerful commercial models like GPT-4o. While these models are highly effective, their substantial costs limit scalability in large-scale evaluations. Adopting open-source MLLMs is an alternative; however, their performance falls short due to significant limitations in processing multi-modal data compared to commercial MLLMs. To tackle these problems, we first propose a task decomposition evaluation framework based on GPT-4o to automatically construct a new training dataset, where the complex evaluation task is decoupled into simpler sub-tasks, effectively reducing the learning complexity. Based on this dataset, we design innovative training strategies to effectively distill GPT-4o's evaluation capabilities into a 7B open-source MLLM, MiniCPM-V-2.6. Furthermore, to reliably and comprehensively assess prior works and our proposed model, we manually annotate a meta-evaluation benchmark that includes chain-of-thought explanations alongside quality scores for generated images. Experimental results demonstrate that our distilled open-source MLLM significantly outperforms the current state-of-the-art GPT-4o-base baseline, VIEScore, with over 4.6\% improvement in Spearman and Kendall correlations with human judgments.

[Arxiv](https://arxiv.org/abs/2411.15488)