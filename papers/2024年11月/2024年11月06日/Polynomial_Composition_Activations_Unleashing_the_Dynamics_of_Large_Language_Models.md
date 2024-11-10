# 多项式组合激活：释放大型语言模型的动态

发布时间：2024年11月06日

`LLM理论` `计算机` `人工智能`

> Polynomial Composition Activations: Unleashing the Dynamics of Large Language Models

# 摘要

> 由于强大的拟合能力，Transformer 在各个领域都有广泛的应用。这一成功部分归因于它们固有的非线性。因此，除了原始 Transformer 架构中使用的 ReLU 函数外，研究人员还探索了诸如 GeLU 和 SwishGLU 等替代模块，以增强非线性，从而提高表示能力。在本文中，我们提出了一种新型的多项式组合激活（PolyCom）类别，旨在优化 Transformer 的动态。从理论上讲，我们对 PolyCom 进行了全面的数学分析，突出了其相对于其他激活函数增强的表达能力和功效。值得注意的是，我们证明了包含 PolyCom 的网络实现了“最优逼近率”，这表明 PolyCom 网络在 Sobolev 空间中近似一般光滑函数所需的参数最少。我们对大型语言模型（LLM）的预训练配置进行了实证实验，包括密集和稀疏架构。通过用 PolyCom 替代传统的激活函数，我们使 LLM 能够捕获数据中的高阶交互，从而在准确性和收敛速度方面提高性能指标。大量的实验结果证明了我们方法的有效性，显示出相对于其他激活函数的显著改进。代码可在 https://github.com/BryceZhuo/PolyCom 获得。

> Transformers have found extensive applications across various domains due to the powerful fitting capabilities. This success can be partially attributed to their inherent nonlinearity. Thus, in addition to the ReLU function employed in the original transformer architecture, researchers have explored alternative modules such as GeLU and SwishGLU to enhance nonlinearity and thereby augment representational capacity. In this paper, we propose a novel category of polynomial composition activations (PolyCom), designed to optimize the dynamics of transformers. Theoretically, we provide a comprehensive mathematical analysis of PolyCom, highlighting its enhanced expressivity and efficacy relative to other activation functions. Notably, we demonstrate that networks incorporating PolyCom achieve the $\textbf{optimal approximation rate}$, indicating that PolyCom networks require minimal parameters to approximate general smooth functions in Sobolev spaces. We conduct empirical experiments on the pre-training configurations of large language models (LLMs), including both dense and sparse architectures. By substituting conventional activation functions with PolyCom, we enable LLMs to capture higher-order interactions within the data, thus improving performance metrics in terms of accuracy and convergence rates. Extensive experimental results demonstrate the effectiveness of our method, showing substantial improvements over other activation functions. Code is available at https://github.com/BryceZhuo/PolyCom.

[Arxiv](https://arxiv.org/abs/2411.03884)