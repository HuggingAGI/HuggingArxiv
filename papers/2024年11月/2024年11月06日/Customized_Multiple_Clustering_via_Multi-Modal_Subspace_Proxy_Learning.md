# 通过多模态子空间代理学习的定制多聚类

发布时间：2024年11月06日

`Agent` `多聚类` `视觉处理`

> Customized Multiple Clustering via Multi-Modal Subspace Proxy Learning

# 摘要

> 多聚类旨在从不同方面发现数据的各种潜在结构。深度多聚类方法通过利用数据中的复杂模式和关系取得了显著的性能。然而，现有的工作难以灵活适应数据分组中各种用户特定的需求，这可能需要手动理解每个聚类。为了解决这些限制，在这项工作中，我们引入了 Multi-Sub，这是一种新颖的端到端多聚类方法，它结合了一个多模态子空间代理学习框架。利用 CLIP 和 GPT-4 的协同能力，Multi-Sub 将表达用户偏好的文本提示与其相应的视觉表示对齐。这是通过从大型语言模型自动生成作为子空间基础的代理词来实现的，从而允许根据用户的兴趣对数据进行定制表示。我们的方法在视觉多聚类任务的一系列广泛的数据集中始终优于现有的基线。我们的代码可在 https://github.com/Alexander-Yao/Multi-Sub 获得。

> Multiple clustering aims to discover various latent structures of data from different aspects. Deep multiple clustering methods have achieved remarkable performance by exploiting complex patterns and relationships in data. However, existing works struggle to flexibly adapt to diverse user-specific needs in data grouping, which may require manual understanding of each clustering. To address these limitations, we introduce Multi-Sub, a novel end-to-end multiple clustering approach that incorporates a multi-modal subspace proxy learning framework in this work. Utilizing the synergistic capabilities of CLIP and GPT-4, Multi-Sub aligns textual prompts expressing user preferences with their corresponding visual representations. This is achieved by automatically generating proxy words from large language models that act as subspace bases, thus allowing for the customized representation of data in terms specific to the user's interests. Our method consistently outperforms existing baselines across a broad set of datasets in visual multiple clustering tasks. Our code is available at https://github.com/Alexander-Yao/Multi-Sub.

[Arxiv](https://arxiv.org/abs/2411.03978)