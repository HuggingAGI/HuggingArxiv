# Doppelgänger 的观察：大型语言模型的分裂目标策略

发布时间：2024年09月09日

`LLM理论` `人工智能`

> Doppelgänger's Watch: A Split Objective Approach to Large Language Models

# 摘要

> 本文探讨了大型语言模型中的“生成监督”问题，提出了一种创新的双重架构，将监督信号与核心能力——有用性分离。Doppelgänger，一个与底层语言模型并行的新模块，负责监督每个令牌的生成，并学习预测包括每个令牌在内的序列的监督分数。我们在此分享了理论发现，实验结果将留待后续发表。

> In this paper, we investigate the problem of "generation supervision" in large language models, and present a novel bicameral architecture to separate supervision signals from their core capability, helpfulness. Doppelgänger, a new module parallel to the underlying language model, supervises the generation of each token, and learns to concurrently predict the supervision score(s) of the sequences up to and including each token. In this work, we present the theoretical findings, and leave the report on experimental results to a forthcoming publication.

[Arxiv](https://arxiv.org/abs/2409.06107)