# 通过复杂性的视角理解视觉特征依赖

发布时间：2024年07月08日

`其他` `计算机视觉`

> Understanding Visual Feature Reliance through the Lens of Complexity

# 摘要

> 摘要：最近的研究表明，深度学习模型倾向于偏爱更简单特征的归纳偏差可能是捷径学习的来源之一。然而，对于模型学习的无数特征的复杂性的理解一直有限。在这项工作中，我们基于 $\mathscr{V}$ - 信息引入了一种用于量化特征复杂性的新指标，并捕获一个特征是否需要复杂的计算转换才能提取。使用这个 $\mathscr{V}$ - 信息指标，我们分析了从标准 ImageNet 训练的视觉模型中提取的作为倒数第二层中的方向表示的 10,000 个特征的复杂性。我们的研究解决了四个关键问题：首先，我们询问特征根据复杂性看起来像什么，并发现模型中存在从简单到复杂的一系列特征。其次，我们询问特征在训练期间何时被学习。我们发现更简单的特征在训练早期占主导地位，更复杂的特征逐渐出现。第三，我们研究简单和复杂的特征在网络中的流动位置，发现更简单的特征倾向于通过残差连接绕过视觉层次结构。第四，我们探索特征复杂性与其在驱动网络决策中的重要性之间的联系。我们发现复杂的特征往往不太重要。令人惊讶的是，重要的特征在训练期间在较早的层中变得可访问，就像沉淀过程一样，允许模型基于这些基础元素构建。

> 
Abstract:Recent studies suggest that deep learning models inductive bias towards favoring simpler features may be one of the sources of shortcut learning. Yet, there has been limited focus on understanding the complexity of the myriad features that models learn. In this work, we introduce a new metric for quantifying feature complexity, based on $\mathscr{V}$-information and capturing whether a feature requires complex computational transformations to be extracted. Using this $\mathscr{V}$-information metric, we analyze the complexities of 10,000 features, represented as directions in the penultimate layer, that were extracted from a standard ImageNet-trained vision model. Our study addresses four key questions: First, we ask what features look like as a function of complexity and find a spectrum of simple to complex features present within the model. Second, we ask when features are learned during training. We find that simpler features dominate early in training, and more complex features emerge gradually. Third, we investigate where within the network simple and complex features flow, and find that simpler features tend to bypass the visual hierarchy via residual connections. Fourth, we explore the connection between features complexity and their importance in driving the networks decision. We find that complex features tend to be less important. Surprisingly, important features become accessible at earlier layers during training, like a sedimentation process, allowing the model to build upon these foundational elements.
    

[Arxiv](https://arxiv.org/pdf/2407.06076)