# GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了基于Transformer的语言模型（如GPT-2 Small）的机械可解释性，特别是关于三字母缩写的预测机制。研究集中在模型内部的工作原理和注意力头的功能分析上，这是对大型语言模型理论层面的深入研究。因此，它属于LLM理论分类，因为它关注的是理解模型的内部运作和预测行为，而不是直接的应用或代理行为。` `模型解释性`

> How does GPT-2 Predict Acronyms? Extracting and Understanding a Circuit via Mechanistic Interpretability

# 摘要

> 基于Transformer的语言模型因其庞大的参数和复杂的内部交互而被视为神秘的黑箱，这引发了严重的安全担忧。机械可解释性（MI）试图揭开神经网络行为的神秘面纱，使其变得人类可理解。在本研究中，我们深入探讨了GPT-2 Small如何巧妙地预测三字母缩写。以往的MI研究多聚焦于单个令牌的预测，而我们的研究则是首次尝试机械地剖析涉及连续多个令牌预测的行为。我们揭示了一个由8个注意力头组成的预测电路，这些头根据其功能被分为三类，并集中体现了缩写预测的能力。我们还深入分析了这些关键的注意力头，发现它们巧妙地利用了位置信息，并通过因果掩码机制传递这一信息。我们相信，这项研究将为未来探索更复杂的多个令牌预测行为奠定坚实的基础。

> Transformer-based language models are treated as black-boxes because of their large number of parameters and complex internal interactions, which is a serious safety concern. Mechanistic Interpretability (MI) intends to reverse-engineer neural network behaviors in terms of human-understandable components. In this work, we focus on understanding how GPT-2 Small performs the task of predicting three-letter acronyms. Previous works in the MI field have focused so far on tasks that predict a single token. To the best of our knowledge, this is the first work that tries to mechanistically understand a behavior involving the prediction of multiple consecutive tokens. We discover that the prediction is performed by a circuit composed of 8 attention heads (~5% of the total heads) which we classified in three groups according to their role. We also demonstrate that these heads concentrate the acronym prediction functionality. In addition, we mechanistically interpret the most relevant heads of the circuit and find out that they use positional information which is propagated via the causal mask mechanism. We expect this work to lay the foundation for understanding more complex behaviors involving multiple-token predictions.

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x1.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x2.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x3.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x4.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x5.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x6.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x7.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x8.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x9.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x10.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x11.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x12.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x13.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x14.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x15.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x16.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x17.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x18.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x19.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x20.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x21.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x22.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x23.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x24.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x25.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x26.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x27.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x28.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x29.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x30.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x31.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x32.png)

![GPT-2如何巧妙预测缩写？我们通过机械可解释性的透镜，深入探索其内部运作，揭秘其预测缩写的神秘电路。](../../../paper_images/2405.04156/x33.png)

[Arxiv](https://arxiv.org/abs/2405.04156)