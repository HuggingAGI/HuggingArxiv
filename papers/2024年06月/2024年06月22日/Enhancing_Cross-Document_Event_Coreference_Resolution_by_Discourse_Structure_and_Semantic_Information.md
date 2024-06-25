# 借助话语结构与语义信息，提升跨文档事件共指解析能力

发布时间：2024年06月22日

`RAG

这篇论文主要关注的是跨文档事件共指问题，并提出了一种基于文档级修辞结构理论（RST）树和跨文档词汇链的方法来改进模型性能。这种方法涉及构建跨文档异构图和使用图注意力网络（GAT）来学习事件表示，以及通过评分器和聚类算法来识别共指事件。此外，论文还创建了一个大规模的中文数据集，以填补现有数据集仅限于英语的空白。这些内容主要涉及文档级信息的利用和跨文档语义关系的建模，属于信息检索和文档分析的范畴，因此归类为RAG（Retrieval-Augmented Generation）。` `事件共指`

> Enhancing Cross-Document Event Coreference Resolution by Discourse Structure and Semantic Information

# 摘要

> 现有的跨文档事件共指模型，或直接比对提及相似度，或通过提取事件参数（如位置、时间、执行者和受影响者）来强化提及表示，却未能充分利用文档级信息，导致难以捕捉长距离依赖。这一短板使得它们在处理依赖长距离信息的事件共指时表现平平。为此，我们提出构建文档级修辞结构理论（RST）树和跨文档词汇链，以模拟文档的结构与语义。接着，我们构建了跨文档异构图，并运用GAT学习事件表示。最后，通过一对评分器计算事件对间的相似度，并借助标准聚类算法识别共指事件。此外，鉴于现有跨文档事件共指数据集仅限于英语，我们创建了一个包含53,066个事件提及和4,476个集群的大规模中文数据集，填补了这一空白。在英汉数据集上的应用显示，我们的模型大幅领先于所有基线。

> Existing cross-document event coreference resolution models, which either compute mention similarity directly or enhance mention representation by extracting event arguments (such as location, time, agent, and patient), lacking the ability to utilize document-level information. As a result, they struggle to capture long-distance dependencies. This shortcoming leads to their underwhelming performance in determining coreference for the events where their argument information relies on long-distance dependencies. In light of these limitations, we propose the construction of document-level Rhetorical Structure Theory (RST) trees and cross-document Lexical Chains to model the structural and semantic information of documents. Subsequently, cross-document heterogeneous graphs are constructed and GAT is utilized to learn the representations of events. Finally, a pair scorer calculates the similarity between each pair of events and co-referred events can be recognized using standard clustering algorithm. Additionally, as the existing cross-document event coreference datasets are limited to English, we have developed a large-scale Chinese cross-document event coreference dataset to fill this gap, which comprises 53,066 event mentions and 4,476 clusters. After applying our model on the English and Chinese datasets respectively, it outperforms all baselines by large margins.

![借助话语结构与语义信息，提升跨文档事件共指解析能力](../../../paper_images/2406.15990/x1.png)

![借助话语结构与语义信息，提升跨文档事件共指解析能力](../../../paper_images/2406.15990/x2.png)

![借助话语结构与语义信息，提升跨文档事件共指解析能力](../../../paper_images/2406.15990/x3.png)

![借助话语结构与语义信息，提升跨文档事件共指解析能力](../../../paper_images/2406.15990/x4.png)

[Arxiv](https://arxiv.org/abs/2406.15990)