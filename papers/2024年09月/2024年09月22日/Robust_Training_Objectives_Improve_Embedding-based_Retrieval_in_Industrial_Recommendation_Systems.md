# 通过强化训练目标，基于嵌入的检索在工业推荐系统中展现出更强的鲁棒性。

发布时间：2024年09月22日

`LLM应用` `社交媒体` `推荐系统`

> Robust Training Objectives Improve Embedding-based Retrieval in Industrial Recommendation Systems

# 摘要

> 提升推荐系统（RS）能显著改善多领域的用户体验，如社交媒体。许多RS采用基于嵌入的检索（EBR）方法来筛选推荐候选。在EBR系统中，嵌入质量至关重要。最新研究表明，自监督多任务学习（SSMTL）在嵌入学习方面表现优异，提升了多个下游任务的性能，增强了任务间的抗干扰能力，从而提高了鲁棒性和泛化能力。然而，SSMTL在学术界的成功是否适用于大规模工业RS（涉及数亿用户和互动）尚待验证。直接将学术方法应用于工业RS可能面临两大问题：一是许多自监督目标需要对大量用户和项目进行数据增强，成本高昂；二是部分自监督目标可能与推荐任务不匹配，导致计算浪费或负面影响。为此，我们在科技行业社交媒体平台的大规模好友推荐系统中，评估了SSMTL作为鲁棒训练目标的效果，以验证其在大规模生产环境中的检索增强能力。通过在线A/B测试，我们发现基于SSMTL的EBR显著提升了好友推荐的关键指标，新好友增加高达5.45%，冷启动用户新好友增加1.91%。

> Improving recommendation systems (RS) can greatly enhance the user experience across many domains, such as social media. Many RS utilize embedding-based retrieval (EBR) approaches to retrieve candidates for recommendation. In an EBR system, the embedding quality is key. According to recent literature, self-supervised multitask learning (SSMTL) has showed strong performance on academic benchmarks in embedding learning and resulted in an overall improvement in multiple downstream tasks, demonstrating a larger resilience to the adverse conditions between each downstream task and thereby increased robustness and task generalization ability through the training objective. However, whether or not the success of SSMTL in academia as a robust training objectives translates to large-scale (i.e., over hundreds of million users and interactions in-between) industrial RS still requires verification. Simply adopting academic setups in industrial RS might entail two issues. Firstly, many self-supervised objectives require data augmentations (e.g., embedding masking/corruption) over a large portion of users and items, which is prohibitively expensive in industrial RS. Furthermore, some self-supervised objectives might not align with the recommendation task, which might lead to redundant computational overheads or negative transfer. In light of these two challenges, we evaluate using a robust training objective, specifically SSMTL, through a large-scale friend recommendation system on a social media platform in the tech sector, identifying whether this increase in robustness can work at scale in enhancing retrieval in the production setting. Through online A/B testing with SSMTL-based EBR, we observe statistically significant increases in key metrics in the friend recommendations, with up to 5.45% improvements in new friends made and 1.91% improvements in new friends made with cold-start users.

[Arxiv](https://arxiv.org/abs/2409.14682)