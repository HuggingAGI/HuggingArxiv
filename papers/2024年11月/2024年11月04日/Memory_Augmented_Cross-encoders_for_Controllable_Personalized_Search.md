# 内存增强的交叉编码器用于可控的个性化搜索

发布时间：2024年11月04日

`LLM应用` `个性化`

> Memory Augmented Cross-encoders for Controllable Personalized Search

# 摘要

> 个性化搜索代表了这样一个问题，即检索模型根据历史用户交互数据进行条件设定，以改善检索结果。然而，个性化通常被认为是不透明的，并且不受用户控制。此外，个性化必然限制了用户接触到的项目空间。因此，先前的工作指出了个性化和用户发现新物品的能力之间的紧张关系。虽然在个性化设置中发现新物品可以通过搜索结果多样化来解决，但这些方法几乎无法让用户控制个性化。因此，在本文中，我们介绍了一种可控个性化搜索的方法。我们的模型 CtrlCE 提出了一种新颖的交叉编码器模型，该模型增加了一个由用户历史项目构建的可编辑内存。我们提出的内存扩充允许交叉编码器模型根据大量历史用户数据进行条件设定，并支持用户的交互，允许对个性化进行控制。此外，搜索的可控个性化必须考虑到不需要个性化的查询，以及用户控制。为此，我们引入了一个校准混合模型，该模型确定何时需要个性化。这使得使用 CtrlCE 的系统设计人员仅在必要时获取用户输入进行控制。在多个个性化搜索的数据集中，我们表明 CtrlCE 能够实现有效的个性化，并满足可控个性化搜索的各种关键目标。

> Personalized search represents a problem where retrieval models condition on historical user interaction data in order to improve retrieval results. However, personalization is commonly perceived as opaque and not amenable to control by users. Further, personalization necessarily limits the space of items that users are exposed to. Therefore, prior work notes a tension between personalization and users' ability for discovering novel items. While discovery of novel items in personalization setups may be resolved through search result diversification, these approaches do little to allow user control over personalization. Therefore, in this paper, we introduce an approach for controllable personalized search. Our model, CtrlCE presents a novel cross-encoder model augmented with an editable memory constructed from users historical items. Our proposed memory augmentation allows cross-encoder models to condition on large amounts of historical user data and supports interaction from users permitting control over personalization. Further, controllable personalization for search must account for queries which don't require personalization, and in turn user control. For this, we introduce a calibrated mixing model which determines when personalization is necessary. This allows system designers using CtrlCE to only obtain user input for control when necessary. In multiple datasets of personalized search, we show CtrlCE to result in effective personalization as well as fulfill various key goals for controllable personalized search.

[Arxiv](https://arxiv.org/abs/2411.02790)