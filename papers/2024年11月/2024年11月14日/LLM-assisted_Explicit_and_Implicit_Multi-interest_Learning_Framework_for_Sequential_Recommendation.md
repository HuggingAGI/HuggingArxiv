# 用于序列推荐的 LLM 辅助的显式与隐式多兴趣学习框架

发布时间：2024年11月14日

`LLM应用` `推荐系统` `用户兴趣建模`

> LLM-assisted Explicit and Implicit Multi-interest Learning Framework for Sequential Recommendation

# 摘要

> 在当下的推荐系统（RS）中，多兴趣建模主要依靠用户行为数据，从多个维度抓取用户的兴趣偏好。但因为行为数据是隐性的，还往往高度稀疏，所以要理解用户复杂多元的兴趣颇具挑战。近期研究显示，文本里丰富的语义信息能有效弥补行为数据的缺陷。即便如此，小型模型还是很难直接提取跟用户深层兴趣有关的语义特征。也就是说，怎样有效让语义和行为信息对齐，从而对用户兴趣形成更全面、准确的理解，已成为关键的研究问题。为应对此，我们提出一个 LLM 辅助的显式和隐式多兴趣学习框架（命名为 EIMF），从行为和语义两个层面为用户兴趣建模。该框架包含两部分：隐式行为兴趣模块（IBIM）和显式语义兴趣模块（ESIM）。IBIM 中的传统多兴趣 RS 模型能从与项目的交互中习得用户的隐式行为兴趣。在 ESIM 里，我们先是采用聚类算法选取典型样本，再在 LLM 上设计提示策略来获取显式语义兴趣。另外，在训练阶段，基于语义预测和模态对齐的多任务学习，典型样本的语义兴趣能够强化行为兴趣的表示学习。所以，在推理阶段，仅凭借用户的行为数据就能达成精准推荐。在真实世界数据集上的大量实验证实了所提出的 EIMF 框架的有效性，它成功且高效地将小型模型与 LLM 相结合，提升了多兴趣建模的准确性。

> Multi-interest modeling in current recommender systems (RS) is mainly based on user behavioral data, capturing user interest preferences from multiple dimensions. However, since behavioral data is implicit and often highly sparse, it is challenging to understand users' complex and diverse interests. Recent studies have shown that the rich semantic information in the text can effectively supplement the deficiencies of behavioral data. Despite this, it is still difficult for small models to directly extract semantic features associated with users' deep interests. That is, how to effectively align semantics with behavioral information to form a more comprehensive and accurate understanding of user interests has become a critical research problem. To address this, we propose an LLM-assisted explicit and implicit multi-interest learning framework (named EIMF) to model user interests on two levels: behavior and semantics. The framework consists of two parts: Implicit Behavioral Interest Module (IBIM) and Explicit Semantic Interest Module (ESIM). The traditional multi-interest RS model in IBIM can learn users' implicit behavioral interests from interactions with items. In ESIM, we first adopt a clustering algorithm to select typical samples and design a prompting strategy on LLM to obtain explicit semantic interests. Furthermore, in the training phase, the semantic interests of typical samples can enhance the representation learning of behavioral interests based on the multi-task learning on semantic prediction and modality alignment. Therefore, in the inference stage, accurate recommendations can be achieved with only the user's behavioral data. Extensive experiments on real-world datasets demonstrate the effectiveness of the proposed EIMF framework, which effectively and efficiently combines small models with LLM to improve the accuracy of multi-interest modeling.

[Arxiv](https://arxiv.org/abs/2411.09410)