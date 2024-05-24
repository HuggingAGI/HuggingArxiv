# AdpQ：大型语言模型无需校准的零-shot自适应后训练量化新方法

发布时间：2024年05月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的量化方法，特别是介绍了一种名为AdpQ的创新零-shot自适应后训练量化（PTQ）方法。这种方法涉及理论分析和模型优化，旨在提高LLMs的部署效率和隐私保护。论文中深入分析了AdpQ的信息理论基础，并展示了其在多个LLM基准测试中的性能。因此，这篇论文更偏向于LLM的理论研究，而不是具体的应用、Agent设计或RAG（Retrieval-Augmented Generation）技术。` `机器学习` `隐私保护`

> AdpQ: A Zero-shot Calibration Free Adaptive Post Training Quantization Method for LLMs

# 摘要

> 随着大型语言模型（LLMs）计算复杂性的不断攀升，高效的部署策略变得至关重要。本文介绍了一种名为AdpQ的创新零-shot自适应后训练量化（PTQ）方法，该方法在低精度（如3位）量化中表现卓越，无需依赖校准数据。借鉴自适应LASSO回归模型的理念，AdpQ通过自适应软阈值技术有效处理异常激活，确保量化权重与原始训练权重紧密匹配，从而无需校准，与SpQR和AWQ等方法形成鲜明对比。此外，AdpQ在保护隐私方面也展现出优势，因为它不涉及任何校准或训练数据的传输。我们深入分析了AdpQ的信息理论基础，揭示了其如何利用自适应LASSO最小化量化权重与原始权重间的Kullback-Leibler散度，从而在保持模型信息内容的同时实现高效部署。实验结果表明，AdpQ在多个LLM基准测试中达到了与现有技术相当的精度，同时将量化时间缩短了至少10倍，显著提升了LLM部署的效率和隐私保护水平。

> The ever-growing computational complexity of Large Language Models (LLMs) necessitates efficient deployment strategies. The current state-of-the-art approaches for Post-training Quantization (PTQ) often require calibration to achieve the desired accuracy. This paper presents AdpQ, a novel zero-shot adaptive PTQ method for LLMs that achieves the state-of-the-art performance in low-precision quantization (e.g. 3-bit) without requiring any calibration data. Inspired by Adaptive LASSO regression model, our proposed approach tackles the challenge of outlier activations by separating salient weights using an adaptive soft-thresholding method. Guided by Adaptive LASSO, this method ensures that the quantized weights distribution closely follows the originally trained weights and eliminates the need for calibration data entirely, setting our method apart from popular approaches such as SpQR and AWQ. Furthermore, our method offers an additional benefit in terms of privacy preservation by eliminating any calibration or training data. We also delve deeper into the information-theoretic underpinnings of the proposed method. We demonstrate that it leverages the Adaptive LASSO to minimize the Kullback-Leibler divergence between the quantized weights and the originally trained weights. This minimization ensures the quantized model retains the Shannon information content of the original model to a great extent, guaranteeing efficient deployment without sacrificing accuracy or information. Our results achieve the same accuracy as the existing methods on various LLM benchmarks while the quantization time is reduced by at least 10x, solidifying our contribution to efficient and privacy-preserving LLM deployment.

[Arxiv](https://arxiv.org/abs/2405.13358)