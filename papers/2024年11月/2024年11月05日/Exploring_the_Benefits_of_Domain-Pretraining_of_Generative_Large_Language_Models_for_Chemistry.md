# 探索生成式大型语言模型在化学领域的预训练的益处

发布时间：2024年11月05日

`LLM应用`

> Exploring the Benefits of Domain-Pretraining of Generative Large Language Models for Chemistry

# 摘要

> 大量的大型语言模型（GPT 系列、BLOOM、LLaMA 等等）正在推动多用途人工智能在各种任务中的新发展，特别是自然语言处理（NLP）任务。这些模型在一系列任务中表现出色；然而，当应用于更小众或狭窄的领域时，有证据表明其存在脆弱性，幻觉或流畅但不正确的响应会降低性能。鉴于科学领域的复杂性，谨慎研究利用现成模型与更有针对性的基础模型在科学领域的权衡是明智的。在这项工作中，我们研究了给定科学领域（化学）的领域内预训练的好处，并将其与具有零样本和少样本提示的开源现成模型进行比较。我们的结果表明，不仅领域内的基础模型在零样本设置下在领域内任务中表现相当好，而且使用指令微调的进一步适应在化学特定任务（如命名实体识别和分子式生成）上产生了令人印象深刻的性能。

> A proliferation of Large Language Models (the GPT series, BLOOM, LLaMA, and more) are driving forward novel development of multipurpose AI for a variety of tasks, particularly natural language processing (NLP) tasks. These models demonstrate strong performance on a range of tasks; however, there has been evidence of brittleness when applied to more niche or narrow domains where hallucinations or fluent but incorrect responses reduce performance. Given the complex nature of scientific domains, it is prudent to investigate the trade-offs of leveraging off-the-shelf versus more targeted foundation models for scientific domains. In this work, we examine the benefits of in-domain pre-training for a given scientific domain, chemistry, and compare these to open-source, off-the-shelf models with zero-shot and few-shot prompting. Our results show that not only do in-domain base models perform reasonably well on in-domain tasks in a zero-shot setting but that further adaptation using instruction fine-tuning yields impressive performance on chemistry-specific tasks such as named entity recognition and molecular formula generation.

[Arxiv](https://arxiv.org/abs/2411.03542)