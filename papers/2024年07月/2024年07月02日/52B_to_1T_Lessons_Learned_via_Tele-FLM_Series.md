# 从 52B 到 1T：Tele-FLM 系列中的经验启示

发布时间：2024年07月02日

`LLM理论` `人工智能` `机器学习`

> 52B to 1T: Lessons Learned via Tele-FLM Series

# 摘要

> 大型语言模型 (LLM) 是通往通用人工智能的关键进展。随着模型规模的扩大，学术界对超过 500 亿参数的 LLM 研究日益深入。本报告基于我们与 Tele-FLM（FLM-2）的合作，该模型拥有 520 亿参数。我们探讨了两个核心领域：首先，我们发现 Tele-FLM-52B 上的监督微调 (SFT) 支持“少即是多”的数据构建策略；其次，我们展示了如何从 520 亿逐步扩展到 1 万亿参数的最佳实践。为推动研究，我们将公开 Tele-FLM-1T 模型。

> Large Language Models (LLMs) represent a significant stride toward Artificial General Intelligence. As scaling laws underscore the potential of increasing model sizes, the academic community has intensified its investigations into LLMs with capacities exceeding 50 billion parameters. This technical report builds on our prior work with Tele-FLM (also known as FLM-2), a publicly available 52-billion-parameter model. We delve into two primary areas: we first discuss our observation of Supervised Fine-tuning (SFT) on Tele-FLM-52B, which supports the "less is more" approach for SFT data construction; second, we demonstrate our experiments and analyses on the best practices for progressively growing a model from 52 billion to 102 billion, and subsequently to 1 trillion parameters. We will open-source a 1T model checkpoint, namely Tele-FLM-1T, to advance further training and research.

[Arxiv](https://arxiv.org/abs/2407.02783)