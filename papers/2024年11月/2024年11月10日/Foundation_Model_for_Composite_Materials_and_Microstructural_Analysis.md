# 复合材料和微观结构分析的基础模型

发布时间：2024年11月10日

`其他` `材料科学` `机器学习`

> Foundation Model for Composite Materials and Microstructural Analysis

# 摘要

> 机器学习的快速发展为材料科学开启了无数的机会，特别是在加速材料的设计和分析方面。然而，一个重大的挑战在于获取高质量材料数据集的稀缺性和高成本。在其他领域，如自然语言处理，在大型数据集上预训练的基础模型在迁移学习中取得了非凡的成功，有效地利用潜在特征在有限数据的任务中实现了高性能。尽管有这样的进展，基础模型的概念在材料科学中仍未得到充分探索。在这里，我们提出了一个专门为复合材料设计的基础模型。我们的模型在短纤维复合材料的数据集上进行预训练，以学习强大的潜在特征。在迁移学习期间，MMAE 准确地预测了均匀化刚度，R2 得分高达 0.959 并且始终超过 0.91，即使在有限数据上进行训练。这些发现验证了基础模型在复合材料中的可行性和有效性。我们预期将这种方法扩展到更复杂的三维复合材料、多晶材料等。此外，这个框架即使在实验数据稀缺时也能实现高精度预测，为更高效和更具成本效益的材料设计和分析铺平了道路。

> The rapid advancement of machine learning has unlocked numerous opportunities for materials science, particularly in accelerating the design and analysis of materials. However, a significant challenge lies in the scarcity and high cost of obtaining high-quality materials datasets. In other fields, such as natural language processing, foundation models pre-trained on large datasets have achieved exceptional success in transfer learning, effectively leveraging latent features to achieve high performance on tasks with limited data. Despite this progress, the concept of foundation models remains underexplored in materials science. Here, we present a foundation model specifically designed for composite materials. Our model is pre-trained on a dataset of short-fiber composites to learn robust latent features. During transfer learning, the MMAE accurately predicts homogenized stiffness, with an R2 score reaching as high as 0.959 and consistently exceeding 0.91, even when trained on limited data. These findings validate the feasibility and effectiveness of foundation models in composite materials. We anticipate extending this approach to more complex three-dimensional composite materials, polycrystalline materials, and beyond. Moreover, this framework enables high-accuracy predictions even when experimental data are scarce, paving the way for more efficient and cost-effective materials design and analysis.

[Arxiv](https://arxiv.org/abs/2411.06565)