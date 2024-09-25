# Ducho 与 Elliot 相遇：探索多模态推荐的大规模基准

发布时间：2024年09月24日

`LLM应用`

> Ducho meets Elliot: Large-scale Benchmarks for Multimodal Recommendation

# 摘要

> 在时尚、音乐和电影推荐等领域，产品与服务的多面特征在在线销售平台上对每位顾客的影响各异，催生了能够从多模态内容中学习的新型推荐模型。文献显示，多模态推荐流程通常包括提取特征、优化表示、融合特征及预测评分。尽管（ii-iv）阶段已有大量优化研究，但（i）阶段的探索却鲜有关注。现有文献虽提及多模态数据集的丰富性和大型模型的增多，却也存在对有限标准化解决方案的过度依赖。因此，我们致力于探索（i）阶段的更广泛技术。本文首次尝试为多模态推荐系统提供大规模基准测试，特别聚焦于多模态提取器。我们借助Ducho和Elliot框架，构建了一个统一且即用的实验环境，以新颖的多模态特征提取器进行广泛基准测试。不同超参数设置下的验证结果，为下一代多模态推荐算法的训练与调优提供了宝贵见解。

> In specific domains like fashion, music, and movie recommendation, the multi-faceted features characterizing products and services may influence each customer on online selling platforms differently, paving the way to novel multimodal recommendation models that can learn from such multimodal content. According to the literature, the common multimodal recommendation pipeline involves (i) extracting multimodal features, (ii) refining their high-level representations to suit the recommendation task, (iii) optionally fusing all multimodal features, and (iv) predicting the user-item score. While great effort has been put into designing optimal solutions for (ii-iv), to the best of our knowledge, very little attention has been devoted to exploring procedures for (i). In this respect, the existing literature outlines the large availability of multimodal datasets and the ever-growing number of large models accounting for multimodal-aware tasks, but (at the same time) an unjustified adoption of limited standardized solutions. This motivates us to explore more extensive techniques for the (i) stage of the pipeline. To this end, this paper settles as the first attempt to offer a large-scale benchmarking for multimodal recommender systems, with a specific focus on multimodal extractors. Specifically, we take advantage of two popular and recent frameworks for multimodal feature extraction and reproducibility in recommendation, Ducho and Elliot, to offer a unified and ready-to-use experimental environment able to run extensive benchmarking analyses leveraging novel multimodal feature extractors. Results, largely validated under different hyper-parameter settings for the chosen extractors, provide important insights on how to train and tune the next generation of multimodal recommendation algorithms.

[Arxiv](https://arxiv.org/abs/2409.15857)