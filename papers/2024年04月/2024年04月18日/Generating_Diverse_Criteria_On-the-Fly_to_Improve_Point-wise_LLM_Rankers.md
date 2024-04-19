# 动态生成多样化评判标准，以提升大型语言模型的逐点排名性能。

发布时间：2024年04月18日

`LLM应用` `信息检索`

> Generating Diverse Criteria On-the-Fly to Improve Point-wise LLM Rankers

# 摘要

> 最新的逐点大型语言模型（LLM）排名器在排名效果上取得了显著成就。但它们存在两大缺陷：一是在排名操作中缺乏统一的比较准则；二是在处理复杂文本时考虑不够全面。为克服这些问题，我们建议开发一种基于多角度标准集的排名器，以生成排名分数。这些标准旨在确保每个视角都能提供既独立又协同的评估。我们的研究对BEIR基准中的八种数据集进行了检验，证实采用这种多视角标准集成方法能显著提升逐点LLM排名器的表现。

> The most recent pointwise Large Language Model (LLM) rankers have achieved remarkable ranking results. However, these rankers are hindered by two major drawbacks: (1) they fail to follow a standardized comparison guidance during the ranking process, and (2) they struggle with comprehensive considerations when dealing with complicated passages. To address these shortcomings, we propose to build a ranker that generates ranking scores based on a set of criteria from various perspectives. These criteria are intended to direct each perspective in providing a distinct yet synergistic evaluation. Our research, which examines eight datasets from the BEIR benchmark demonstrates that incorporating this multi-perspective criteria ensemble approach markedly enhanced the performance of pointwise LLM rankers.

[Arxiv](https://arxiv.org/abs/2404.11960)