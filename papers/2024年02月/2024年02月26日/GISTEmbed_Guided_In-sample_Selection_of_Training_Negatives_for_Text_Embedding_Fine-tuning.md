# GISTEmbed 是一种创新方法，旨在通过引导式的样本内负例选择策略优化文本嵌入微调过程。该技术专为提升文本embedding在训练阶段的效果而设计，尤其关注有效筛选和利用训练集中内在的负样本。

发布时间：2024年02月26日

`LLM应用`

> GISTEmbed: Guided In-sample Selection of Training Negatives for Text Embedding Fine-tuning

> 嵌入模型是诸如语义搜索、个性化推荐和LLMs检索增强生成等AI应用的核心组件，而优质训练数据是其必需品。但人工筛选数据难以规模化，急需自动化的数据质量保障方案。传统无监督三元组挖掘虽能自动生成训练数据，却在不经意间引入了偏见和噪声，导致模型性能下滑。为此，我们提出了创新策略GISTEmbed，它运用引导模型优化对比训练时的批次内负样本选择，告别了随机抽样和平等效用假设，有效降低了由数据质量问题引起的噪声，大幅提升模型微调表现。经过 Massive Text Embedding Benchmark (MTEB) 的基准测试，GISTEmbed在各类模型尺寸上均表现出一致且显著的性能进步，并在某些领域达到业界领先水平。这一框架巧妙借助了强大但资源消耗大的大型模型的优势，极大提升了小型模型的表现力。GISTEmbed有潜力革新高效小型模型的研发方式，让更多人能平等地享受到尖端AI技术带来的便利。通过提升这些技术的易用性和经济性，特别是在资源约束的应用环境中，将进一步拓宽前沿AI解决方案在多元领域的影响范围和普及程度。

> Embedding models are integral to AI applications like semantic search, personalized recommendations, and retrieval augmented generation for LLMs, necessitating high-quality training data. However, the limited scalability of manual data curation prompts the need for automated methods to ensure data integrity. Traditional unsupervised triplet mining automates training data generation, crucial for embedding model training, yet inadvertently injects biases and noise, thereby degrading model performance. Addressing this, we introduce GISTEmbed, a novel strategy that enhances in-batch negative selection during contrastive training through a guide model. This approach departs from reliance on random sampling and equal utility assumption of batch negatives, significantly reducing noise from data quality issues and improving model fine-tuning. Benchmarked against the Massive Text Embedding Benchmark (MTEB), GISTEmbed showcases consistent performance improvements across various model sizes and achieves state-of-the-art results in select categories. This framework enables significant enhancements for smaller models by leveraging the capabilities of powerful yet resource-intensive large models. GISTEmbed can potentially revolutionize the creation of highly efficient, smaller models, democratizing access to advanced AI technologies. Making these technologies more accessible and cost-effective, especially for applications constrained by resources, significantly expands the impact and accessibility of state-of-the-art AI solutions across diverse sectors.

[Arxiv](https://arxiv.org/abs/2402.16829)