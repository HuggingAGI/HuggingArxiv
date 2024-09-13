# 探索法律AI解决方案：以获取正义的问答为例

发布时间：2024年09月11日

`LLM应用`

> Experimenting with Legal AI Solutions: The Case of Question-Answering for Access to Justice

# 摘要

> 生成式 AI 模型如 GPT 和 Llama 系列，在帮助普通人解答法律问题上潜力巨大。然而，现有研究多忽视了这些模型在普通人使用场景中的数据获取、推理及评估。为此，我们设计了一套以人为本的法律 NLP 流程，涵盖数据获取、推理和评估。我们发布了一个名为 LegalQA 的数据集，包含从劳动法到刑法等领域的真实法律问题，由法律专家撰写的答案及引用。我们还开发了自动评估协议，结果显示，仅利用训练集中 850 个引用的检索增强生成，就能媲美甚至超越全网检索，尽管数据量少了 9 个数量级。最后，我们探讨了开源模型未来发展的方向，这些方向目前仍落后于闭源模型。

> Generative AI models, such as the GPT and Llama series, have significant potential to assist laypeople in answering legal questions. However, little prior work focuses on the data sourcing, inference, and evaluation of these models in the context of laypersons. To this end, we propose a human-centric legal NLP pipeline, covering data sourcing, inference, and evaluation. We introduce and release a dataset, LegalQA, with real and specific legal questions spanning from employment law to criminal law, corresponding answers written by legal experts, and citations for each answer. We develop an automatic evaluation protocol for this dataset, then show that retrieval-augmented generation from only 850 citations in the train set can match or outperform internet-wide retrieval, despite containing 9 orders of magnitude less data. Finally, we propose future directions for open-sourced efforts, which fall behind closed-sourced models.

[Arxiv](https://arxiv.org/abs/2409.07713)