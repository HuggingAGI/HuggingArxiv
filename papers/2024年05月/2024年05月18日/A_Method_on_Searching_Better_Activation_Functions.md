# 探索更优激活函数的新途径

发布时间：2024年05月18日

`LLM理论

理由：这篇论文主要探讨了激活函数的优化方法，特别是基于熵的激活函数优化（EAFO）方法，并提出了新型激活函数——校正正则化ReLU（CRReLU）。这些研究内容直接关联到大型语言模型（LLM）的理论基础，尤其是在神经网络激活函数的设计和优化方面。虽然论文中提到了在大型语言模型微调任务中的应用，但核心贡献在于理论层面的创新，因此更适合归类为LLM理论。` `人工智能`

> A Method on Searching Better Activation Functions

# 摘要

> 人工神经网络（ANNs）的成功关键在于激活函数的精心挑选，这为网络引入了非线性，使其能够捕捉数据中的复杂关系。然而，以往激活函数的选择多依赖经验，缺乏理论支撑，限制了更高效激活函数的发现。本研究提出了一种基于熵的激活函数优化（EAFO）方法，从信息熵的角度证明了存在最差激活函数边界条件（WAFBC），并借鉴信息熵函数的泰勒展开，为深度神经网络激活函数的设计提供了新思路，同时展示了训练过程中动态优化激活函数的潜力。我们基于ReLU开发了一种新型激活函数——校正正则化ReLU（CRReLU），并在CIFAR-10、CIFAR-100及ImageNet-1K数据集上验证了其优于现有ReLU修正版本的性能。在大型语言模型微调任务中，CRReLU的表现超越了GELU，预示着其在实际应用中的广阔前景。

> The success of artificial neural networks (ANNs) hinges greatly on the judicious selection of an activation function, introducing non-linearity into network and enabling them to model sophisticated relationships in data. However, the search of activation functions has largely relied on empirical knowledge in the past, lacking theoretical guidance, which has hindered the identification of more effective activation functions. In this work, we offer a proper solution to such issue. Firstly, we theoretically demonstrate the existence of the worst activation function with boundary conditions (WAFBC) from the perspective of information entropy. Furthermore, inspired by the Taylor expansion form of information entropy functional, we propose the Entropy-based Activation Function Optimization (EAFO) methodology. EAFO methodology presents a novel perspective for designing static activation functions in deep neural networks and the potential of dynamically optimizing activation during iterative training. Utilizing EAFO methodology, we derive a novel activation function from ReLU, known as Correction Regularized ReLU (CRReLU). Experiments conducted with vision transformer and its variants on CIFAR-10, CIFAR-100 and ImageNet-1K datasets demonstrate the superiority of CRReLU over existing corrections of ReLU. Extensive empirical studies on task of large language model (LLM) fine-tuning, CRReLU exhibits superior performance compared to GELU, suggesting its broader potential for practical applications.

[Arxiv](https://arxiv.org/abs/2405.12954)