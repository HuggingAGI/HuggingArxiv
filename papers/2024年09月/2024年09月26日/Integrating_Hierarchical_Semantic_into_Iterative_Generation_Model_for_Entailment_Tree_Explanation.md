# 融合分层语义至迭代生成模型，解析蕴涵树的奥秘

发布时间：2024年09月26日

`LLM应用` `问答系统`

> Integrating Hierarchical Semantic into Iterative Generation Model for Entailment Tree Explanation

# 摘要

> 在可解释问答（QA）中，从证据到答案的推理线路需要清晰且逻辑地展示。蕴涵树结构性地呈现了这些线路，与大规模语言模型的自我解释原则不同。现有方法往往忽视树结构中层次间和层次内的句子语义关联，容易导致组合错误。为此，我们提出了控制器-生成器（Controller-Generator）框架下的层次语义整合架构（HiSCG），通过设计假设与事实的层次映射、区分树构建中的事实，并优化单步蕴涵，来解释答案。据我们所知，我们是首个关注同一层与相邻层间句子层次语义并实现改进的团队。该方法在EntailmentBank数据集的三种设置中表现出色，并在两个域外数据集上展示了其泛化能力。

> Manifestly and logically displaying the line of reasoning from evidence to answer is significant to explainable question answering (QA). The entailment tree exhibits the lines structurally, which is different from the self-explanation principle in large-scale language models. Existing methods rarely consider the semantic association of sentences between and within hierarchies within the tree structure, which is prone to apparent mistakes in combinations. In this work, we propose an architecture of integrating the Hierarchical Semantics of sentences under the framework of Controller-Generator (HiSCG) to explain answers. The HiSCG designs a hierarchical mapping between hypotheses and facts, discriminates the facts involved in tree constructions, and optimizes single-step entailments. To the best of our knowledge, We are the first to notice hierarchical semantics of sentences between the same layer and adjacent layers to yield improvements. The proposed method achieves comparable performance on all three settings of the EntailmentBank dataset. The generalization results on two out-of-domain datasets also demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2409.17757)