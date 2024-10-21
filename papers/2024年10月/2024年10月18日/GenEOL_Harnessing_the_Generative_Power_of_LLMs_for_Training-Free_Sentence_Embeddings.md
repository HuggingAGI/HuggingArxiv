# GenEOL：释放 LLM 的生成力，实现无需训练的句子嵌入

发布时间：2024年10月18日

`LLM应用` `机器学习`

> GenEOL: Harnessing the Generative Power of LLMs for Training-Free Sentence Embeddings

# 摘要

> 无训练嵌入方法直接利用预训练的 LLM 进行文本嵌入，避免了对比学习的复杂过程。以往的方法主要优化嵌入提示，却忽略了 LLM 的生成能力。我们提出的 GenEOL 方法，通过 LLM 生成多样化的句子变换，并聚合这些变换的嵌入，显著提升了句子嵌入的质量。在 STS 基准测试中，GenEOL 平均优于现有方法 2.85 分。分析表明，GenEOL 在 LLM 各层间稳定了表示质量，并对提示扰动具有鲁棒性。此外，GenEOL 在 MTEB 基准的多个任务中表现出色。

> Training-free embedding methods directly leverage pretrained large language models (LLMs) to embed text, bypassing the costly and complex procedure of contrastive learning. Previous training-free embedding methods have mainly focused on optimizing embedding prompts and have overlooked the benefits of utilizing the generative abilities of LLMs. We propose a novel method, GenEOL, which uses LLMs to generate diverse transformations of a sentence that preserve its meaning, and aggregates the resulting embeddings of these transformations to enhance the overall sentence embedding. GenEOL significantly outperforms the existing training-free embedding methods by an average of 2.85 points across several LLMs on the sentence semantic text similarity (STS) benchmark. Our analysis shows that GenEOL stabilizes representation quality across LLM layers and is robust to perturbations of embedding prompts. GenEOL also achieves notable gains on multiple clustering, reranking and pair-classification tasks from the MTEB benchmark.

[Arxiv](https://arxiv.org/abs/2410.14635)