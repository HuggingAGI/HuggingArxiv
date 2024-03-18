# [为实现检索与推荐，构建语言与物品之间的桥梁]

发布时间：2024年03月06日

`Agent`

> Bridging Language and Items for Retrieval and Recommendation

> 本文推出了面向推荐场景优化的预训练句子嵌入模型系列——BLaIR，它致力于捕捉项目元数据与可能存在的自然语言环境间的关联，有效助力物品的检索和推荐。基于全新的Amazon Reviews 2023数据集进行预训练，该数据集涵盖了超过5.7亿条评论及来自33种类别的4800万项商品，规模远超以往版本。我们对BLaIR在多元领域和多种任务中的泛化性能进行了全面测试，其中涵盖一个创新任务“复杂产品搜索”，即在面对冗长复杂的自然语言描述时找到匹配的商品。结合使用大型语言模型ChatGPT，我们创建了半合成评估集合Amazon-C4。实验结果显示，在复杂产品搜索任务及传统检索、推荐任务中，BLaIR均展现出卓越的文本与物品表征能力。相关数据集、代码及模型检查点已公开发布于GitHub：https://github.com/hyp1231/AmazonReviews2023。

> This paper introduces BLaIR, a series of pretrained sentence embedding models specialized for recommendation scenarios. BLaIR is trained to learn correlations between item metadata and potential natural language context, which is useful for retrieving and recommending items. To pretrain BLaIR, we collect Amazon Reviews 2023, a new dataset comprising over 570 million reviews and 48 million items from 33 categories, significantly expanding beyond the scope of previous versions. We evaluate the generalization ability of BLaIR across multiple domains and tasks, including a new task named complex product search, referring to retrieving relevant items given long, complex natural language contexts. Leveraging large language models like ChatGPT, we correspondingly construct a semi-synthetic evaluation set, Amazon-C4. Empirical results on the new task, as well as conventional retrieval and recommendation tasks, demonstrate that BLaIR exhibit strong text and item representation capacity. Our datasets, code, and checkpoints are available at: https://github.com/hyp1231/AmazonReviews2023.

[Arxiv](https://arxiv.org/abs/2403.03952)