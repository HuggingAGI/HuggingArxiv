# 缓解对话查询生成中的过度关联问题

发布时间：2024年09月29日

`LLM应用` `对话系统` `搜索引擎`

> Mitigating the Negative Impact of Over-association for Conversational Query Production

# 摘要

> 对话查询生成旨在从对话历史中提取搜索查询，进而从搜索引擎中获取相关知识，以支持基于知识的对话系统。然而，先前模型在最大化黄金查询可能性时，常因数据匮乏而遗漏重要概念，并在推理时生成无关内容。我们发现，这源于标注者在生成黄金查询时，无意识地运用了背景知识，导致查询与对话主题间接关联，即“过度关联现象”。为此，我们深入分析了该现象对预训练Seq2seq查询生成器的负面影响，并提出了多角度实例级加权策略以缓解问题。实验结果表明，我们的策略在Wizard-of-Internet和DuSinc两个基准测试中，有效提升了模型性能（自动指标和人工评估分别提升2%-5%）。此外，我们的模型在选择对话历史中的关键概念方面表现更佳，数据效率比基线模型高出10倍。代码已公开，详见https://github.com/DeepLearnXMU/QG-OverAsso。

> Conversational query generation aims at producing search queries from dialogue histories, which are then used to retrieve relevant knowledge from a search engine to help knowledge-based dialogue systems. Trained to maximize the likelihood of gold queries, previous models suffer from the data hunger issue, and they tend to both drop important concepts from dialogue histories and generate irrelevant concepts at inference time. We attribute these issues to the over-association phenomenon where a large number of gold queries are indirectly related to the dialogue topics, because annotators may unconsciously perform reasoning with their background knowledge when generating these gold queries. We carefully analyze the negative effects of this phenomenon on pretrained Seq2seq query producers and then propose effective instance-level weighting strategies for training to mitigate these issues from multiple perspectives. Experiments on two benchmarks, Wizard-of-Internet and DuSinc, show that our strategies effectively alleviate the negative effects and lead to significant performance gains (2%-5% across automatic metrics and human evaluation). Further analysis shows that our model selects better concepts from dialogue histories and is 10 times more data efficient than the baseline. The code is available at https://github.com/DeepLearnXMU/QG-OverAsso.

[Arxiv](https://arxiv.org/abs/2409.19572)