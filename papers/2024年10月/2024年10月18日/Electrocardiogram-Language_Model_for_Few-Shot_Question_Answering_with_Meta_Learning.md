# 心电图语言模型：少样本问答的元学习新篇章

发布时间：2024年10月18日

`LLM应用` `人工智能`

> Electrocardiogram-Language Model for Few-Shot Question Answering with Meta Learning

# 摘要

> 心电图解读需要专业知识，通常涉及将ECG信号与自然语言的复杂临床查询相结合。由于标记ECG数据稀缺且临床查询多样，开发稳健的ECG诊断系统面临挑战。本研究提出了一种多模态元学习方法，用于少样本ECG问答，解决了数据有限的问题，并利用了大型语言模型（LLM）的知识。通过将预训练的ECG编码器与冻结的LLM（如LLaMA和Gemma）结合，我们的方法使语言模型能够理解ECG数据并生成临床上有意义的答案。实验表明，该方法在未见过的诊断任务上表现优异，甚至在有限ECG导联下也能取得显著效果。例如，在5-way 5-shot设置中，使用LLaMA-3.1-8B的方法在不同问题类型上分别达到了84.6%、77.3%和69.6%的准确率。这些结果展示了我们的方法在数据受限情况下，通过结合信号处理与LLM的细致语言理解能力，增强临床ECG解读的潜力。

> Electrocardiogram (ECG) interpretation requires specialized expertise, often involving synthesizing insights from ECG signals with complex clinical queries posed in natural language. The scarcity of labeled ECG data coupled with the diverse nature of clinical inquiries presents a significant challenge for developing robust and adaptable ECG diagnostic systems. This work introduces a novel multimodal meta-learning method for few-shot ECG question answering, addressing the challenge of limited labeled data while leveraging the rich knowledge encoded within large language models (LLMs). Our LLM-agnostic approach integrates a pre-trained ECG encoder with a frozen LLM (e.g., LLaMA and Gemma) via a trainable fusion module, enabling the language model to reason about ECG data and generate clinically meaningful answers. Extensive experiments demonstrate superior generalization to unseen diagnostic tasks compared to supervised baselines, achieving notable performance even with limited ECG leads. For instance, in a 5-way 5-shot setting, our method using LLaMA-3.1-8B achieves accuracy of 84.6%, 77.3%, and 69.6% on single verify, choose and query question types, respectively. These results highlight the potential of our method to enhance clinical ECG interpretation by combining signal processing with the nuanced language understanding capabilities of LLMs, particularly in data-constrained scenarios.

[Arxiv](https://arxiv.org/abs/2410.14464)