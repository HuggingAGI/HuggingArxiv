# Promptriever：经过指令训练的检索器，也能像语言模型一样灵活响应提示。

发布时间：2024年09月17日

`RAG` `信息检索`

> Promptriever: Instruction-Trained Retrievers Can Be Prompted Like Language Models

# 摘要

> 指令调优的语言模型 (LM) 能够响应命令式指令，提供比基础模型更自然的用户界面。我们在此介绍 Promptriever，这是首个能像 LM 一样被提示的检索模型。为训练 Promptriever，我们从 MS MARCO 中精选并发布了一个包含近 50 万个实例的新指令训练集。Promptriever 不仅在标准检索任务上表现优异，还能遵循指令。我们发现：(1) 在遵循详细相关性指令方面表现出色（在 FollowIR 上达到 SoTA，+14.3 p-MRR / +3.1 nDCG），(2) 对查询和指令中的词汇选择/措辞的鲁棒性显著提升（在 InstructIR 上 +12.9 Robustness@10），以及 (3) 通过提示进行超参数搜索以提升检索性能的能力（在 BEIR 上平均增加 +1.4）。Promptriever 展示了检索模型可通过提示在每个查询基础上进行控制，为未来将 LM 提示技术与信息检索结合的工作铺平了道路。

> Instruction-tuned language models (LM) are able to respond to imperative commands, providing a more natural user interface compared to their base counterparts. In this work, we present Promptriever, the first retrieval model able to be prompted like an LM. To train Promptriever, we curate and release a new instance-level instruction training set from MS MARCO, spanning nearly 500k instances. Promptriever not only achieves strong performance on standard retrieval tasks, but also follows instructions. We observe: (1) large gains (reaching SoTA) on following detailed relevance instructions (+14.3 p-MRR / +3.1 nDCG on FollowIR), (2) significantly increased robustness to lexical choices/phrasing in the query+instruction (+12.9 Robustness@10 on InstructIR), and (3) the ability to perform hyperparameter search via prompting to reliably improve retrieval performance (+1.4 average increase on BEIR). Promptriever demonstrates that retrieval models can be controlled with prompts on a per-query basis, setting the stage for future work aligning LM prompting techniques with information retrieval.

[Arxiv](https://arxiv.org/abs/2409.11136)