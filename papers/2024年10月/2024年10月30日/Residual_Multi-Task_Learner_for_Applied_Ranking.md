# 应用排名中的剩余多任务学习器

发布时间：2024年10月30日

`其他`

> Residual Multi-Task Learner for Applied Ranking

# 摘要

> 现代电商平台高度依赖对多样的用户反馈进行建模来提供个性化服务，所以多任务学习已成为其排名系统的重要部分。然而，现有的多任务学习方法存在两大主要挑战：有些缺少对任务关系的清晰建模，致使性能欠佳；另一些则因计算量大、可扩展性差或依赖强假设，适用性受限。为应对这些局限并更贴合我们的实际场景，也就是 Shopee 搜索中的预排名，本文引入了 ResFlow，这是一个轻量的多任务学习框架，能通过任务网络对应层间的残差连接实现高效的跨任务信息共享。在来自不同场景和模式的数据集上开展的大量实验表明，它的性能和适应性优于前沿方法。Shopee 搜索中的在线 A/B 测试彰显了其在大规模工业应用中的实用价值，OPU（每位用户的订单量）提升了 1.29%，且未增加系统延迟。ResFlow 现已全面部署于 Shopee 搜索的预排名模块。为助力高效的在线部署，我们提出了新颖的离线指标 Weighted Recall@K，它与在线指标 OPU 高度契合，解决了长期存在的在线与离线指标不一致问题。此外，我们提议在对项目进行排名时将多个任务的分数相加融合，效果优于传统的乘法融合。代码发布于 https://github.com/BrunoTruthAlliance/ResFlow

> Modern e-commerce platforms rely heavily on modeling diverse user feedback to provide personalized services. Consequently, multi-task learning has become an integral part of their ranking systems. However, existing multi-task learning methods encounter two main challenges: some lack explicit modeling of task relationships, resulting in inferior performance, while others have limited applicability due to being computationally intensive, having scalability issues, or relying on strong assumptions. To address these limitations and better fit our real-world scenario, pre-rank in Shopee Search, we introduce in this paper ResFlow, a lightweight multi-task learning framework that enables efficient cross-task information sharing via residual connections between corresponding layers of task networks. Extensive experiments on datasets from various scenarios and modalities demonstrate its superior performance and adaptability over state-of-the-art methods. The online A/B tests in Shopee Search showcase its practical value in large-scale industrial applications, evidenced by a 1.29% increase in OPU (order-per-user) without additional system latency. ResFlow is now fully deployed in the pre-rank module of Shopee Search. To facilitate efficient online deployment, we propose a novel offline metric Weighted Recall@K, which aligns well with our online metric OPU, addressing the longstanding online-offline metric misalignment issue. Besides, we propose to fuse scores from the multiple tasks additively when ranking items, which outperforms traditional multiplicative fusion. The code is released at https://github.com/BrunoTruthAlliance/ResFlow

[Arxiv](https://arxiv.org/abs/2411.09705)