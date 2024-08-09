# 细粒度引用学习：为大型语言模型赋予属性

发布时间：2024年08月08日

`LLM应用` `信息查询` `人工智能`

> Learning Fine-Grained Grounded Citations for Attributed Large Language Models

# 摘要

> 尽管大型语言模型（LLM）在信息查询任务上表现卓越，但仍难以避免“幻觉”现象。为此，我们提出了FRONT框架，旨在通过细粒度实证引用提升LLM的生成质量。该框架不仅改善了引用精度，还简化了用户的细粒度验证过程。实验结果显示，FRONT在ALCE基准测试中表现优异，使用LLaMA-2-7B模型时，引用质量平均提升了14.21%，超越了ChatGPT的表现。

> Despite the impressive performance on information-seeking tasks, large language models (LLMs) still struggle with hallucinations. Attributed LLMs, which augment generated text with in-line citations, have shown potential in mitigating hallucinations and improving verifiability. However, current approaches suffer from suboptimal citation quality due to their reliance on in-context learning. Furthermore, the practice of citing only coarse document identifiers makes it challenging for users to perform fine-grained verification. In this work, we introduce FRONT, a training framework designed to teach LLMs to generate Fine-Grained Grounded Citations. By grounding model outputs in fine-grained supporting quotes, these quotes guide the generation of grounded and consistent responses, not only improving citation quality but also facilitating fine-grained verification. Experiments on the ALCE benchmark demonstrate the efficacy of FRONT in generating superior grounded responses and highly supportive citations. With LLaMA-2-7B, the framework significantly outperforms all the baselines, achieving an average of 14.21% improvement in citation quality across all datasets, even surpassing ChatGPT.

[Arxiv](https://arxiv.org/abs/2408.04568)