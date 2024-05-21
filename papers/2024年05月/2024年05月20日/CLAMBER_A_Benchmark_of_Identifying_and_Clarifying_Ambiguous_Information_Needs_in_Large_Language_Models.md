# CLAMBER：大型语言模型中模糊信息需求识别与澄清的基准测试

发布时间：2024年05月20日

`LLM应用

理由：这篇论文主要关注于大型语言模型（LLMs）在处理模糊用户查询时的性能评估，并提出了一个名为CLAMBER的评估基准。它探讨了LLMs在识别和澄清模糊查询方面的局限性，并提出了改进的方向。这表明论文的重点是应用层面的评估和改进，而不是理论研究或Agent的设计，也不是关于检索增强生成（RAG）的具体研究。因此，它最适合归类为LLM应用。` `评估基准`

> CLAMBER: A Benchmark of Identifying and Clarifying Ambiguous Information Needs in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在满足用户信息需求方面的应用日益增多，它们在处理含糊不清的用户查询时的效果仍是一个未知数，这可能影响用户的信任和满意度。为此，我们推出了CLAMBER，一个基于有序分类法的LLMs评估基准。我们利用这一分类法，精心构建了约12,000个高质量数据点，旨在全面评估现成LLMs的优劣及潜在风险。研究显示，即便借助思维链（CoT）和小样本提示，当前LLMs在识别和澄清模糊查询方面仍显不足，可能导致过度自信，且在模糊性识别上的改进有限。此外，由于缺乏有效的冲突解决机制和内部知识的准确运用，LLMs在生成高质量澄清问题方面亦显乏力。本文中，CLAMBER不仅提供了研究方向，也推动了关于主动和可信赖LLMs的深入研究。我们的数据集已公开，详情请访问https://github.com/zt991211/CLAMBER。

> Large language models (LLMs) are increasingly used to meet user information needs, but their effectiveness in dealing with user queries that contain various types of ambiguity remains unknown, ultimately risking user trust and satisfaction. To this end, we introduce CLAMBER, a benchmark for evaluating LLMs using a well-organized taxonomy. Building upon the taxonomy, we construct ~12K high-quality data to assess the strengths, weaknesses, and potential risks of various off-the-shelf LLMs. Our findings indicate the limited practical utility of current LLMs in identifying and clarifying ambiguous user queries, even enhanced by chain-of-thought (CoT) and few-shot prompting. These techniques may result in overconfidence in LLMs and yield only marginal enhancements in identifying ambiguity. Furthermore, current LLMs fall short in generating high-quality clarifying questions due to a lack of conflict resolution and inaccurate utilization of inherent knowledge. In this paper, CLAMBER presents a guidance and promotes further research on proactive and trustworthy LLMs. Our dataset is available at https://github.com/zt991211/CLAMBER

![CLAMBER：大型语言模型中模糊信息需求识别与澄清的基准测试](../../../paper_images/2405.12063/prediction_bias.png)

![CLAMBER：大型语言模型中模糊信息需求识别与澄清的基准测试](../../../paper_images/2405.12063/few_shot_analysis.png)

![CLAMBER：大型语言模型中模糊信息需求识别与澄清的基准测试](../../../paper_images/2405.12063/new_cq_error.png)

[Arxiv](https://arxiv.org/abs/2405.12063)