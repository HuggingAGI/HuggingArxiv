# EMMA-500：提升大型语言模型在海量多语言环境中的适应能力

发布时间：2024年09月26日

`LLM应用` `语言技术` `人工智能`

> EMMA-500: Enhancing Massively Multilingual Adaptation of Large Language Models

# 摘要

> 我们推出了 EMMA-500，一个在 546 种语言上继续训练的大型多语言模型，旨在提升低资源语言的覆盖率。为支持这一目标，我们构建了 MaLA 语料库，一个涵盖多领域的高质量多语言数据集。通过利用该语料库，我们对 Llama 2 7B 模型进行了深度预训练，生成的 EMMA-500 在多项基准测试中表现卓越，包括多语言任务和本研究开发的开放式生成基准 PolyWrite。研究结果表明，持续预训练显著增强了大型模型的语言能力，特别是在跨语言迁移、任务泛化和语言适应性方面，为低资源语言带来了显著提升。

> In this work, we introduce EMMA-500, a large-scale multilingual language model continue-trained on texts across 546 languages designed for enhanced multilingual performance, focusing on improving language coverage for low-resource languages. To facilitate continual pre-training, we compile the MaLA corpus, a comprehensive multilingual dataset enriched with curated datasets across diverse domains. Leveraging this corpus, we conduct extensive continual pre-training of the Llama 2 7B model, resulting in EMMA-500, which demonstrates robust performance across a wide collection of benchmarks, including a comprehensive set of multilingual tasks and PolyWrite, an open-ended generation benchmark developed in this study. Our results highlight the effectiveness of continual pre-training in expanding large language models' language capacity, particularly for underrepresented languages, demonstrating significant gains in cross-lingual transfer, task generalization, and language adaptability.

[Arxiv](https://arxiv.org/abs/2409.17892)