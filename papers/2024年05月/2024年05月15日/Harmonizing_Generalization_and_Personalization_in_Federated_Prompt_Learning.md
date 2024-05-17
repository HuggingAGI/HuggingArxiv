# 在联邦提示学习中寻求泛化与个性化的和谐共舞

发布时间：2024年05月15日

`Agent

这篇论文讨论了联邦提示学习（FPL）及其在联邦学习中的应用，特别是在处理数据异质性时如何平衡个性化与泛化。它提出了FedPGP方法，这是一种结合了CLIP的知识引导和低秩个性化的技术，旨在通过提示级对比损失实现个性化与泛化的平衡。虽然这种方法涉及大型视觉-语言模型（VLM）的使用，但它的重点在于开发一种新的学习策略（Agent），以在联邦学习环境中优化模型的性能。因此，它更符合Agent分类，因为它关注的是模型如何在特定环境中自主学习和适应，而不是LLM的理论研究或应用。` `联邦学习` `视觉-语言模型`

> Harmonizing Generalization and Personalization in Federated Prompt Learning

# 摘要

> 联邦提示学习（FPL）通过提示调优将大型视觉-语言模型（VLM）融入联邦学习，利用VLM的强大泛化能力应对数据异质性。然而，过度个性化可能会削弱模型的泛化能力。为此，我们提出了FedPGP方法，它巧妙结合了CLIP的知识引导和低秩个性化，通过提示级对比损失实现了个性化与泛化的平衡。实验证明，FedPGP在处理异构数据时，无论是类别还是域级别，都能有效平衡个性化与泛化，展现出其优越性。

> Federated Prompt Learning (FPL) incorporates large pre-trained Vision-Language models (VLM) into federated learning through prompt tuning. The transferable representations and remarkable generalization capacity of VLM make them highly compatible with the integration of federated learning. Addressing data heterogeneity in federated learning requires personalization, but excessive focus on it across clients could compromise the model's ability to generalize effectively. To preserve the impressive generalization capability of VLM, it is crucial to strike a balance between personalization and generalization in FPL. To tackle this challenge, we proposed Federated Prompt Learning with CLIP Generalization and low-rank Personalization (FedPGP), which employs pre-trained CLIP to provide knowledge-guidance on the global prompt for improved generalization and incorporates a low-rank adaptation term to personalize the global prompt. Further, FedPGP integrates a prompt-wise contrastive loss to achieve knowledge guidance and personalized adaptation simultaneously, enabling a harmonious balance between personalization and generalization in FPL. We conduct extensive experiments on various datasets to explore base-to-novel generalization in both category-level and domain-level scenarios with heterogeneous data, showing the superiority of FedPGP in balancing generalization and personalization.

![在联邦提示学习中寻求泛化与个性化的和谐共舞](../../../paper_images/2405.09771/x1.png)

![在联邦提示学习中寻求泛化与个性化的和谐共舞](../../../paper_images/2405.09771/x2.png)

![在联邦提示学习中寻求泛化与个性化的和谐共舞](../../../paper_images/2405.09771/x3.png)

![在联邦提示学习中寻求泛化与个性化的和谐共舞](../../../paper_images/2405.09771/x4.png)

![在联邦提示学习中寻求泛化与个性化的和谐共舞](../../../paper_images/2405.09771/x5.png)

[Arxiv](https://arxiv.org/abs/2405.09771)