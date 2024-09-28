# 本文提出了一种单分支嵌入多模态网络，专为冷启动和模态缺失场景下的推荐任务设计。

发布时间：2024年09月26日

`LLM应用` `电子商务`

> A Multimodal Single-Branch Embedding Network for Recommendation in Cold-Start and Missing Modality Scenarios

# 摘要

> 大多数推荐系统依赖协同过滤 (CF)，基于用户过去的互动提供推荐。然而，当互动数据稀缺时，CF 性能会显著下降，这种情况称为冷启动。为解决这一问题，以往研究尝试结合协同数据与用户或项目的侧面信息。类似多模态学习，这些模型旨在融合协同与内容表示于同一嵌入空间。我们提出了一种创新的多模态推荐技术——多模态单分支嵌入网络推荐 (SiBraR)。通过权重共享，SiBraR 使用单一网络同时编码不同模态的互动数据与侧面信息，使其在冷启动等模态缺失场景中表现出色。我们在音乐、电影和电商领域的多个大规模数据集上进行实验，结果表明 SiBraR 在冷启动场景中显著优于传统 CF 及最先进的内容推荐系统，在常规场景中也表现不俗。此外，SiBraR 能将不同模态映射至同一嵌入空间区域，有效缩小模态差距，确保推荐准确性。

> Most recommender systems adopt collaborative filtering (CF) and provide recommendations based on past collective interactions. Therefore, the performance of CF algorithms degrades when few or no interactions are available, a scenario referred to as cold-start. To address this issue, previous work relies on models leveraging both collaborative data and side information on the users or items. Similar to multimodal learning, these models aim at combining collaborative and content representations in a shared embedding space. In this work we propose a novel technique for multimodal recommendation, relying on a multimodal Single-Branch embedding network for Recommendation (SiBraR). Leveraging weight-sharing, SiBraR encodes interaction data as well as multimodal side information using the same single-branch embedding network on different modalities. This makes SiBraR effective in scenarios of missing modality, including cold start. Our extensive experiments on large-scale recommendation datasets from three different recommendation domains (music, movie, and e-commerce) and providing multimodal content information (audio, text, image, labels, and interactions) show that SiBraR significantly outperforms CF as well as state-of-the-art content-based RSs in cold-start scenarios, and is competitive in warm scenarios. We show that SiBraR's recommendations are accurate in missing modality scenarios, and that the model is able to map different modalities to the same region of the shared embedding space, hence reducing the modality gap.

[Arxiv](https://arxiv.org/abs/2409.17864)