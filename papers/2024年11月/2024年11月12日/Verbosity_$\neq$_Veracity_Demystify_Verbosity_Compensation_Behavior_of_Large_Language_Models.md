# 冗长性 $
eq$ 准确性：揭开大型语言模型的冗长性补偿行为的神秘面纱

发布时间：2024年11月12日

`LLM应用` `语言模型`

> Verbosity $\neq$ Veracity: Demystify Verbosity Compensation Behavior of Large Language Models

# 摘要

> 当对答案不确定时，人类经常用比必要更多的词来回应，希望回应的一部分是正确的。我们在大型语言模型（LLM）中观察到类似的行为，我们称之为“冗长补偿”（VC）。VC 是有害的，因为它混淆了用户的理解，导致效率低下，并通过增加生成无用标记的延迟和成本来影响 LLM 服务。在本文中，我们提出了第一项定义和分析冗长补偿的工作，探索其原因，并提出了一种简单的缓解方法。我们将冗长补偿定义为在被提示简洁写作时生成的可以在不丢失信息的情况下压缩的响应行为。我们在基于知识和推理的 QA 任务的五个数据集上使用 14 个新开发的 LLM 进行的实验揭示了三个结论。1）我们揭示了在所有模型和所有数据集中都普遍存在冗长补偿。值得注意的是，GPT-4 表现出 50.40％的 VC 频率。2）我们揭示了冗长和简洁响应之间的巨大性能差距，在 Qasper 数据集上有显著的 27.61％的差异。我们还证明，随着 LLM 能力的提高，这种差异不会自然减少。1）和 2）都突出了减少 VC 行为频率以及将冗长与准确性分开的迫切需要。我们提出了一种简单而有效的级联算法，用其他模型生成的响应替换冗长的响应。结果表明，在 Qasper 数据集上，我们的方法有效地将 Mistral 模型的 VC 从 63.81％降低到 16.16％。3）我们还发现，在所有五个数据集中，冗长的响应表现出更高的不确定性，表明冗长与模型不确定性之间有很强的联系。我们的数据集和代码可在 https://github.com/psunlpgroup/VerbosityLLM 获得。

> When unsure about an answer, humans often respond with more words than necessary, hoping that part of the response will be correct. We observe a similar behavior in large language models (LLMs), which we term "Verbosity Compensation" (VC). VC is harmful because it confuses the user understanding, leading to low efficiency, and influences the LLM services by increasing the latency and cost of generating useless tokens. In this paper, we present the first work that defines and analyzes Verbosity Compensation, explores its causes, and proposes a simple mitigating approach. We define Verbosity Compensation as the behavior of generating responses that can be compressed without information loss when prompted to write concisely. Our experiments, conducted on five datasets of knowledge and reasoning-based QA tasks with 14 newly developed LLMs, reveal three conclusions. 1) We reveal a pervasive presence of verbosity compensation across all models and all datasets. Notably, GPT-4 exhibits a VC frequency of 50.40%. 2) We reveal the large performance gap between verbose and concise responses, with a notable difference of 27.61% on the Qasper dataset. We also demonstrate that this difference does not naturally diminish as LLM capability increases. Both 1) and 2) highlight the urgent need to mitigate the frequency of VC behavior and disentangle verbosity with veracity. We propose a simple yet effective cascade algorithm that replaces the verbose responses with the other model-generated responses. The results show that our approach effectively alleviates the VC of the Mistral model from 63.81% to 16.16% on the Qasper dataset. 3) We also find that verbose responses exhibit higher uncertainty across all five datasets, suggesting a strong connection between verbosity and model uncertainty. Our dataset and code are available at https://github.com/psunlpgroup/VerbosityLLM.

[Arxiv](https://arxiv.org/abs/2411.07858)