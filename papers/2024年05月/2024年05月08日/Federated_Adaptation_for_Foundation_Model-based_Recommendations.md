# 基于基础模型的推荐系统的联邦适应性研究在翻译过程中，我首先直接将英文标题翻译为中文，确保意思的准确传达。然后，我进一步优化翻译，使其更加符合中文的表达习惯，简洁而优雅，同时保持了原标题的学术性和专业性。

发布时间：2024年05月08日

`Agent

这篇论文探讨了在推荐系统中使用大型语言模型（LLM）时如何平衡隐私保护和用户偏好适应性的问题。通过提出一种创新的联邦学习机制，该论文展示了一种在保护用户隐私的同时，允许基石模型适应用户偏好的方法。这种方法涉及在用户端训练个性化适配器，这些适配器与基石模型协同工作，以提供精准推荐。因此，这篇论文更符合Agent分类，因为它描述了一种智能代理（Agent）如何在保护隐私的前提下，利用本地数据进行学习和适应，以提供个性化服务。` `推荐系统` `隐私保护`

> Federated Adaptation for Foundation Model-based Recommendations

# 摘要

> 大型语言模型的成功，尤其是那些具有泛化能力的基石模型，为推荐系统带来了革新。然而，如何在保护隐私的同时，让基石模型及时适应用户偏好的变化，成为新的挑战。本文提出了一种创新的联邦学习机制，它允许每个用户端利用本地数据训练个性化适配器，这些适配器与基石模型协同工作，提供精准推荐，同时确保用户数据的安全。通过联邦学习框架，我们实现了数据本地化隐私保护，同时保留了用户的个性化偏好。实验结果在四个数据集上展示了我们方法的卓越性能，且实现代码已公开，以支持研究的可重复性。

> With the recent success of large language models, particularly foundation models with generalization abilities, applying foundation models for recommendations becomes a new paradigm to improve existing recommendation systems. It becomes a new open challenge to enable the foundation model to capture user preference changes in a timely manner with reasonable communication and computation costs while preserving privacy. This paper proposes a novel federated adaptation mechanism to enhance the foundation model-based recommendation system in a privacy-preserving manner. Specifically, each client will learn a lightweight personalized adapter using its private data. The adapter then collaborates with pre-trained foundation models to provide recommendation service efficiently with fine-grained manners. Importantly, users' private behavioral data remains secure as it is not shared with the server. This data localization-based privacy preservation is embodied via the federated learning framework. The model can ensure that shared knowledge is incorporated into all adapters while simultaneously preserving each user's personal preferences. Experimental results on four benchmark datasets demonstrate our method's superior performance. Implementation code is available to ease reproducibility.

[Arxiv](https://arxiv.org/abs/2405.04840)