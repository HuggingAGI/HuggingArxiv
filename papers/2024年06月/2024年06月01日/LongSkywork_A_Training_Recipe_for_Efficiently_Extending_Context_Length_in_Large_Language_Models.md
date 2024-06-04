# LongSkywork：大型语言模型上下文长度扩展的高效训练秘诀

发布时间：2024年06月01日

`LLM应用

这篇论文介绍了LongSkywork，一种能够处理极长上下文的大型语言模型，并详细描述了其训练方案和数据生成方法。这些内容主要关注于LLM的实际应用和性能提升，特别是在处理长上下文方面的能力。因此，它属于LLM应用分类。` `机器学习`

> LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models

# 摘要

> 我们推出了LongSkywork，这是一种能够处理高达200,000个令牌的长上下文大型语言模型。我们提供了一套高效的训练方案，用以扩展LLM的上下文长度。关键在于，在标准SFT阶段之后引入一个长上下文SFT阶段，仅需200次迭代即可将模型升级为长上下文处理能手。为了简化数据收集和标注的繁琐过程，我们创新性地开发了两种合成数据生成方法，这些方法在预训练和SFT阶段均得到应用，显著提升了训练效率。研究表明，这些合成的长上下文SFT数据在性能上甚至能超越人工精选的数据。LongSkywork在多个长上下文基准测试中大放异彩，尤其在Needle测试中，我们的模型在多个上下文跨度上均取得了满分。在实际应用中，LongSkywork-13B的表现与业界领先的长期上下文模型Claude2.1不相上下，充分证明了我们方法的卓越效果。

> We introduce LongSkywork, a long-context Large Language Model (LLM) capable of processing up to 200,000 tokens. We provide a training recipe for efficiently extending context length of LLMs. We identify that the critical element in enhancing long-context processing capability is to incorporate a long-context SFT stage following the standard SFT stage. A mere 200 iterations can convert the standard SFT model into a long-context model. To reduce the effort in collecting and annotating data for long-context language modeling, we develop two novel methods for creating synthetic data. These methods are applied during the continual pretraining phase as well as the Supervised Fine-Tuning (SFT) phase, greatly enhancing the training efficiency of our long-context LLMs. Our findings suggest that synthetic long-context SFT data can surpass the performance of data curated by humans to some extent. LongSkywork achieves outstanding performance on a variety of long-context benchmarks. In the Needle test, a benchmark for long-context information retrieval, our models achieved perfect accuracy across multiple context spans. Moreover, in realistic application scenarios, LongSkywork-13B demonstrates performance on par with Claude2.1, the leading long-context model, underscoring the effectiveness of our proposed methods.

![LongSkywork：大型语言模型上下文长度扩展的高效训练秘诀](../../../paper_images/2406.00605/output.png)

![LongSkywork：大型语言模型上下文长度扩展的高效训练秘诀](../../../paper_images/2406.00605/x1.png)

![LongSkywork：大型语言模型上下文长度扩展的高效训练秘诀](../../../paper_images/2406.00605/traing_loss.png)

[Arxiv](https://arxiv.org/abs/2406.00605)