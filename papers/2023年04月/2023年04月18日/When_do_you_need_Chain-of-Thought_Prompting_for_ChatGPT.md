# 何时应为 ChatGPT 启用思维链提示？

发布时间：2023年04月18日

`LLM理论

理由：这篇论文主要探讨了思维链（CoT）提示在大型语言模型（LLMs）中的应用效果，特别是在ChatGPT这样的指令微调（IFT）模型上的表现。论文分析了CoT提示的有效性，以及可能导致的过度拟合/偏差风险，并探讨了预训练数据集泄露的问题。这些内容更多地涉及LLMs的理论和内部机制，而非具体的应用场景或Agent的设计，因此归类为LLM理论。` `人工智能`

> When do you need Chain-of-Thought Prompting for ChatGPT?

# 摘要

> 思维链（CoT）提示能有效激发大型语言模型（LLMs）进行复杂的多步骤推理。例如，只需在MultiArith数据集的每个查询前加上“让我们一步一步思考”的指令，GPT-3的准确率就能从17.7%跃升至78.7%。然而，对于像ChatGPT这样的最新指令微调（IFT）LLMs，CoT的有效性尚不明确。令人意外的是，在ChatGPT上，CoT在算术推理等任务中失效，而在其他推理任务中依然有效。更有趣的是，ChatGPT在这些任务中表现最佳，甚至无需指令就能自发生成CoT。这表明ChatGPT可能已在这些任务上接受了CoT训练，并记住了指令，因此在处理相同查询时，即使未明确指示，也能隐含地遵循CoT。我们的分析揭示了IFT中指令可能导致的过度拟合/偏差风险，这在LLMs训练中日益普遍。此外，这还暗示了预训练配方的潜在泄露，例如，可以检测ChatGPT的训练中是否使用了特定数据集和指令。我们的实验为ChatGPT在多种推理任务上设定了新的基准，并深入探讨了LLMs的特性、指令记忆以及预训练数据集泄露的问题。

> Chain-of-Thought (CoT) prompting can effectively elicit complex multi-step reasoning from Large Language Models~(LLMs). For example, by simply adding CoT instruction ``Let's think step-by-step'' to each input query of MultiArith dataset, GPT-3's accuracy can be improved from 17.7\% to 78.7\%. However, it is not clear whether CoT is still effective on more recent instruction finetuned (IFT) LLMs such as ChatGPT. Surprisingly, on ChatGPT, CoT is no longer effective for certain tasks such as arithmetic reasoning while still keeping effective on other reasoning tasks. Moreover, on the former tasks, ChatGPT usually achieves the best performance and can generate CoT even without being instructed to do so. Hence, it is plausible that ChatGPT has already been trained on these tasks with CoT and thus memorized the instruction so it implicitly follows such an instruction when applied to the same queries, even without CoT. Our analysis reflects a potential risk of overfitting/bias toward instructions introduced in IFT, which becomes more common in training LLMs. In addition, it indicates possible leakage of the pretraining recipe, e.g., one can verify whether a dataset and instruction were used in training ChatGPT. Our experiments report new baseline results of ChatGPT on a variety of reasoning tasks and shed novel insights into LLM's profiling, instruction memorization, and pretraining dataset leakage.

[Arxiv](https://arxiv.org/abs/2304.03262)