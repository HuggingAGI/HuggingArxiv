# 鸡尾酒：集成 LLM 生成文档的综合信息检索基准

发布时间：2024年05月26日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）生成内容对信息检索（IR）系统的影响，并为此推出了一个综合基准Cocktail，用于评估在LLM时代混合数据环境中IR模型的性能。这表明论文的研究重点是LLMs在实际应用中的效果和影响，特别是对信息检索系统的影响，因此属于LLM应用类别。` `信息检索` `人工智能`

> Cocktail: A Comprehensive Information Retrieval Benchmark with LLM-Generated Documents Integration

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，AI生成内容（AIGC）在互联网上大量涌现，使得信息检索（IR）系统的语料库从纯人类编写转变为与LLM生成内容并存。AIGC的激增对IR系统的影响尚不明确，关键挑战在于缺乏专门的研究基准。为此，我们推出了Cocktail，一个专为评估LLM时代混合数据环境中IR模型性能的综合基准，包含16个跨不同任务和领域的多样化数据集。为避免LLMs中已有数据集的潜在偏见，我们还引入了基于近期事件的最新数据集NQ-UTD。通过在Cocktail上对顶尖检索模型进行上千次测试，我们发现神经检索模型在排名性能与来源偏见之间存在明显权衡，强调了未来IR系统设计中平衡策略的重要性。我们期待Cocktail成为LLM时代IR研究的重要基石，其数据和代码已公开于\url{https://github.com/KID-22/Cocktail}。

> The proliferation of Large Language Models (LLMs) has led to an influx of AI-generated content (AIGC) on the internet, transforming the corpus of Information Retrieval (IR) systems from solely human-written to a coexistence with LLM-generated content. The impact of this surge in AIGC on IR systems remains an open question, with the primary challenge being the lack of a dedicated benchmark for researchers. In this paper, we introduce Cocktail, a comprehensive benchmark tailored for evaluating IR models in this mixed-sourced data landscape of the LLM era. Cocktail consists of 16 diverse datasets with mixed human-written and LLM-generated corpora across various text retrieval tasks and domains. Additionally, to avoid the potential bias from previously included dataset information in LLMs, we also introduce an up-to-date dataset, named NQ-UTD, with queries derived from recent events. Through conducting over 1,000 experiments to assess state-of-the-art retrieval models against the benchmarked datasets in Cocktail, we uncover a clear trade-off between ranking performance and source bias in neural retrieval models, highlighting the necessity for a balanced approach in designing future IR systems. We hope Cocktail can serve as a foundational resource for IR research in the LLM era, with all data and code publicly available at \url{https://github.com/KID-22/Cocktail}.

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x1.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x2.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x3.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x4.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x5.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x6.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x7.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x8.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x9.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x10.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x11.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x12.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x13.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x14.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x15.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x16.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x17.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x18.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x19.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x20.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x21.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x22.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x23.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x24.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x25.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x26.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x27.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x28.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x29.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x30.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x31.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x32.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x33.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x34.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x35.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x36.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x37.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x38.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x39.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x40.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x41.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x42.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x43.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x44.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x45.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x46.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x47.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x48.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x49.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x50.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x51.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x52.png)

![鸡尾酒：集成 LLM 生成文档的综合信息检索基准](../../../paper_images/2405.16546/x53.png)

[Arxiv](https://arxiv.org/abs/2405.16546)