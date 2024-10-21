# 心电图语言模型：少样本问答的元学习新篇章

发布时间：2024年10月18日

`LLM应用` `人工智能`

> Electrocardiogram-Language Model for Few-Shot Question Answering with Meta Learning

# 摘要

> 心电图解读需要专业知识，常需结合复杂临床问题与 ECG 信号。然而，标记 ECG 数据的稀缺性和临床查询的多样性为开发稳健的 ECG 诊断系统带来了挑战。为此，我们提出了一种多模态元学习方法，通过利用大型语言模型（LLM）的丰富知识，解决标记数据有限的问题。我们的方法通过融合模块将预训练的 ECG 编码器与冻结的 LLM（如 LLaMA 和 Gemma）结合，使语言模型能推理 ECG 数据并生成临床上有意义的答案。实验表明，我们的方法在未见过的诊断任务上表现优异，甚至在有限 ECG 导联下也能取得显著性能。例如，在 5-way 5-shot 设置中，LLaMA-3.1-8B 在单验证、选择和查询问题类型上分别达到了 84.6%、77.3% 和 69.6% 的准确率。这些结果展示了我们的方法在数据受限情况下，通过结合信号处理与 LLM 的细微语言理解能力，增强临床 ECG 解读的潜力。

> Electrocardiogram (ECG) interpretation requires specialized expertise, often involving synthesizing insights from ECG signals with complex clinical queries posed in natural language. The scarcity of labeled ECG data coupled with the diverse nature of clinical inquiries presents a significant challenge for developing robust and adaptable ECG diagnostic systems. This work introduces a novel multimodal meta-learning method for few-shot ECG question answering, addressing the challenge of limited labeled data while leveraging the rich knowledge encoded within large language models (LLMs). Our LLM-agnostic approach integrates a pre-trained ECG encoder with a frozen LLM (e.g., LLaMA and Gemma) via a trainable fusion module, enabling the language model to reason about ECG data and generate clinically meaningful answers. Extensive experiments demonstrate superior generalization to unseen diagnostic tasks compared to supervised baselines, achieving notable performance even with limited ECG leads. For instance, in a 5-way 5-shot setting, our method using LLaMA-3.1-8B achieves accuracy of 84.6%, 77.3%, and 69.6% on single verify, choose and query question types, respectively. These results highlight the potential of our method to enhance clinical ECG interpretation by combining signal processing with the nuanced language understanding capabilities of LLMs, particularly in data-constrained scenarios.

[Arxiv](https://arxiv.org/abs/2410.14464)