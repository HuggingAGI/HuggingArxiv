# 对预训练的文本嵌入模型于建筑资产信息对齐方面展开基准测试

发布时间：2024年11月18日

`LLM应用` `资产管理` `数据分类`

> Benchmarking pre-trained text embedding models in aligning built asset information

# 摘要

> 将已建成资产信息准确映射到既定的数据分类系统和分类法，对于有效的资产管理而言至关重要，不管是在项目移交时的合规方面，还是在临时数据集成的场景下。鉴于已建成资产数据复杂，主要由技术文本元素构成，这一过程很大程度上仍需手动操作，并依赖领域专家的投入。近来，在上下文文本表示学习（文本嵌入）领域，尤其是通过预训练的大型语言模型，取得了突破，为已建成资产数据交叉映射的自动化提供了可行途径。然而，对于这些模型能否有效呈现已建成资产技术术语特有的复杂语义，尚未有全面评估。本研究给出了最先进的文本嵌入模型的对比基准，以评估它们在使已建成资产信息与特定领域技术概念相匹配方面的成效。我们提出的数据集源自两个知名的已建成资产数据分类词典。我们在涵盖聚类、检索和重新排序这三项任务的六个数据集上进行的基准测试结果表明，未来需要在领域适应技术方面展开研究。基准测试资源以开源库形式发布，并将持续维护和拓展，以支持该领域未来的评估工作。

> Accurate mapping of the built asset information to established data classification systems and taxonomies is crucial for effective asset management, whether for compliance at project handover or ad-hoc data integration scenarios. Due to the complex nature of built asset data, which predominantly comprises technical text elements, this process remains largely manual and reliant on domain expert input. Recent breakthroughs in contextual text representation learning (text embedding), particularly through pre-trained large language models, offer promising approaches that can facilitate the automation of cross-mapping of the built asset data. However, no comprehensive evaluation has yet been conducted to assess these models' ability to effectively represent the complex semantics specific to built asset technical terminology. This study presents a comparative benchmark of state-of-the-art text embedding models to evaluate their effectiveness in aligning built asset information with domain-specific technical concepts. Our proposed datasets are derived from two renowned built asset data classification dictionaries. The results of our benchmarking across six proposed datasets, covering three tasks of clustering, retrieval, and reranking, highlight the need for future research on domain adaptation techniques. The benchmarking resources are published as an open-source library, which will be maintained and extended to support future evaluations in this field.

[Arxiv](https://arxiv.org/abs/2411.12056)