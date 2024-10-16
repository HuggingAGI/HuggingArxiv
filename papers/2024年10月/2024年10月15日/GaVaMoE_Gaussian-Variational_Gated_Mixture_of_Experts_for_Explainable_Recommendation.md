# GaVaMoE：一种结合高斯变分和门控混合专家技术，旨在提升推荐系统可解释性的模型。

发布时间：2024年10月15日

`LLM应用` `推荐系统` `个性化服务`

> GaVaMoE: Gaussian-Variational Gated Mixture of Experts for Explainable Recommendation

# 摘要

> 基于大型语言模型的可解释推荐系统在生成人性化解释方面潜力巨大，但在模拟用户与项目的协同偏好、个性化解释以及处理稀疏交互方面仍面临挑战。为此，我们提出了GaVaMoE，一种结合高斯变分门控专家混合的创新框架。GaVaMoE包含两个核心模块：一是利用VAE与GMM的评分重构模块，捕捉复杂协同偏好，作为预训练的多门控机制；二是细粒度专家模型，与多门控机制协同，生成高度个性化解释。通过VAE建模潜在交互因素，GMM对相似行为用户聚类，每个聚类对应一个门，将用户-项目对路由至合适专家模型。这种设计使GaVaMoE能针对特定用户类型和偏好生成定制解释，有效缓解数据稀疏问题。实验证明，GaVaMoE在解释质量、个性化和一致性上显著超越现有方法，尤其在稀疏交互场景下表现出色，即使历史数据有限，也能提供高质量解释。

> Large language model-based explainable recommendation (LLM-based ER) systems show promise in generating human-like explanations for recommendations. However, they face challenges in modeling user-item collaborative preferences, personalizing explanations, and handling sparse user-item interactions. To address these issues, we propose GaVaMoE, a novel Gaussian-Variational Gated Mixture of Experts framework for explainable recommendation. GaVaMoE introduces two key components: (1) a rating reconstruction module that employs Variational Autoencoder (VAE) with a Gaussian Mixture Model (GMM) to capture complex user-item collaborative preferences, serving as a pre-trained multi-gating mechanism; and (2) a set of fine-grained expert models coupled with the multi-gating mechanism for generating highly personalized explanations. The VAE component models latent factors in user-item interactions, while the GMM clusters users with similar behaviors. Each cluster corresponds to a gate in the multi-gating mechanism, routing user-item pairs to appropriate expert models. This architecture enables GaVaMoE to generate tailored explanations for specific user types and preferences, mitigating data sparsity by leveraging user similarities. Extensive experiments on three real-world datasets demonstrate that GaVaMoE significantly outperforms existing methods in explanation quality, personalization, and consistency. Notably, GaVaMoE exhibits robust performance in scenarios with sparse user-item interactions, maintaining high-quality explanations even for users with limited historical data.

[Arxiv](https://arxiv.org/abs/2410.11841)