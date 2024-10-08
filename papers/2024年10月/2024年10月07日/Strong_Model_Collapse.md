# 模型崩溃现象严重

发布时间：2024年10月07日

`LLM理论` `人工智能` `机器学习`

> Strong Model Collapse

# 摘要

> 在支撑ChatGPT和Llama等大型神经网络训练的缩放定律框架下，我们探讨了监督回归设置，并证实了模型崩溃现象的严重性，这一现象源于训练数据中的合成数据。研究发现，即使合成数据仅占训练集的1%，也可能导致模型性能无法随训练集增大而提升。此外，我们分析了增加模型大小（当前训练大型语言模型的趋势）对模型崩溃的影响，发现更大模型可能加剧崩溃。然而，理论预测显示，在极高插值阈值之外，更大模型或许能缓解崩溃，但无法完全消除。这一理论通过语言模型和图像前馈神经网络的实验得到了验证。

> Within the scaling laws paradigm, which underpins the training of large neural networks like ChatGPT and Llama, we consider a supervised regression setting and establish the existance of a strong form of the model collapse phenomenon, a critical performance degradation due to synthetic data in the training corpus. Our results show that even the smallest fraction of synthetic data (e.g., as little as 1\% of the total training dataset) can still lead to model collapse: larger and larger training sets do not enhance performance. We further investigate whether increasing model size, an approach aligned with current trends in training large language models, exacerbates or mitigates model collapse. In a simplified regime where neural networks are approximated via random projections of tunable size, we both theoretically and empirically show that larger models can amplify model collapse. Interestingly, our theory also indicates that, beyond the interpolation threshold (which can be extremely high for very large datasets), larger models may mitigate the collapse, although they do not entirely prevent it. Our theoretical findings are empirically verified through experiments on language models and feed-forward neural networks for images.

[Arxiv](https://arxiv.org/abs/2410.04840)