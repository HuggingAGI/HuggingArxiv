# UDKAG：为大型视觉-语言模型注入最新知识
发布时间：2024年05月23日

`RAG`
> UDKAG: Augmenting Large Vision-Language Models with Up-to-Date Knowledge
>
> 大型视觉-语言模型（LVLMs）因资源需求巨大而难以频繁更新，对最新信息如LLaVA系列一无所知，常在关键时刻失效。例如，2024年1月发布的LVLM对同年2月上映的《沙丘2》剧情一无所知。为此，我们提出了一种创新方法——互联网增强生成（IAG），在推理时通过网络搜索为模型注入最新知识，这一技术已在GPT-4V等商业模型中应用，但其运作细节仍不为人知。本文介绍了一种即插即用框架UDKAG，旨在提升LVLMs在处理最新知识相关的视觉问答（VQA）任务时的能力。我们训练了一个分层过滤模型，能从搜索引擎结果中精准筛选出最有价值的信息，以更新模型知识库。同时，我们开发了一套自动生成新闻相关VQA样本的流程，构建了UDK-VQA数据集，并采用多模型投票机制评估网站内容的有用性，以此训练模型。实验证明，我们的框架在准确性上超越了GPT-4V约25%。
>
> https://arxiv.org/abs/2405.14554


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14554](https://arxiv.org/abs/2405.14554)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886