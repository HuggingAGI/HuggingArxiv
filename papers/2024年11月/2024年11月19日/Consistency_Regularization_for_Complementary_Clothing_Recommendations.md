# 关于互补服装推荐的一致性正则化

发布时间：2024年11月19日

`其他` `推荐系统`

> Consistency Regularization for Complementary Clothing Recommendations

# 摘要

> 这篇论文讲述了用于贝叶斯个性化排序的一致性正则化模型（CR-BPR）的研发情况，旨在化解现有互补服装推荐方法存在的弊端，比如因多模态数据的不同特征规模而导致的一致性受限和有偏差的学习。和其他产品类别相比，时尚偏好本就主观且更具个性化，时尚往往不是通过单个服装产品展现，而是与其他互补产品以搭配协调的时尚套装形式呈现。当下的互补产品推荐研究主要着眼于用户偏好和产品匹配，而本研究在服装搭配这一特定情境中，进一步突出了用户 - 产品交互以及产品 - 产品交互中所观察到的一致性。多数传统方法常常低估了现有衣柜物品对未来搭配选择的影响，致使偏好预测模型效果欠佳。此外，许多基于多模态信息的模型忽略了不同特征规模带来的局限。为弥补这些不足，CR-BPR 模型融合了协同过滤技术，将用户偏好和产品匹配建模纳入其中，尤其注重各个方面的一致性正则化。另外，引入特征缩放流程进一步解决了不同特征规模造成的不平衡，保证模型能有效处理多模态数据，不被任何特定类型的特征所左右。CR-BPR 模型的有效性通过涉及两个基准数据集的详尽分析得以验证。结果表明，所提方法显著优于现有模型。

> This paper reports on the development of a Consistency Regularized model for Bayesian Personalized Ranking (CR-BPR), addressing to the drawbacks in existing complementary clothing recommendation methods, namely limited consistency and biased learning caused by diverse feature scale of multi-modal data. Compared to other product types, fashion preferences are inherently subjective and more personal, and fashion are often presented, not by individual clothing product, but with other complementary product(s) in a well coordinated fashion outfit. Current complementary-product recommendation studies primarily focus on user preference and product matching, this study further emphasizes the consistency observed in user-product interactions as well as product-product interactions, in the specific context of clothing matching. Most traditional approaches often underplayed the impact of existing wardrobe items on future matching choices, resulting in less effective preference prediction models. Moreover, many multi-modal information based models overlook the limitations arising from various feature scales being involved. To address these gaps, the CR-BPR model integrates collaborative filtering techniques to incorporate both user preference and product matching modeling, with a unique focus on consistency regularization for each aspect. Additionally, the incorporation of a feature scaling process further addresses the imbalances caused by different feature scales, ensuring that the model can effectively handle multi-modal data without being skewed by any particular type of feature. The effectiveness of the CR-BPR model was validated through detailed analysis involving two benchmark datasets. The results confirmed that the proposed approach significantly outperforms existing models.

[Arxiv](https://arxiv.org/abs/2411.12295)