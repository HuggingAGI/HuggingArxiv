# 受认知启发的基于能量的世界观

发布时间：2024年06月13日

`LLM理论

理由：这篇论文探讨了自回归预测模型与人类认知的差异，并提出了基于能量的世界模型（EBWM）和基于能量的变压器（EBT），旨在模拟人类的认知过程。这些模型和方法的提出是为了改进现有的语言模型理论，特别是在理解人类认知和预测机制方面。因此，这篇论文更偏向于理论研究，而不是具体的应用、代理（Agent）或检索增强生成（RAG）技术。` `计算机视觉`

> Cognitively Inspired Energy-Based World Models

# 摘要

> 在NLP和CV领域，自回归预测是训练世界模型的主流方法，但这种方法与人类认知存在差异。人类预测未来时，会主动影响认知过程，并自然评估预测的合理性，动态调整预测时间，这种适应性思维类似于心理学中的系统2。为了弥补传统自回归模型的不足，我们提出了基于能量的世界模型（EBWM），它通过训练基于能量的模型（EBM）来评估上下文与未来状态的兼容性，从而模拟人类的认知过程。我们还开发了基于能量的变压器（EBT），一种专为基于能量的模型设计的自回归变压器变体。实验表明，EBWM在CV和NLP任务中展现出优于传统模型的扩展性能，为未来模型训练提供了新的方向，使其能够进行系统2思维和智能搜索状态空间。

> One of the predominant methods for training world models is autoregressive prediction in the output space of the next element of a sequence. In Natural Language Processing (NLP), this takes the form of Large Language Models (LLMs) predicting the next token; in Computer Vision (CV), this takes the form of autoregressive models predicting the next frame/token/pixel. However, this approach differs from human cognition in several respects. First, human predictions about the future actively influence internal cognitive processes. Second, humans naturally evaluate the plausibility of predictions regarding future states. Based on this capability, and third, by assessing when predictions are sufficient, humans allocate a dynamic amount of time to make a prediction. This adaptive process is analogous to System 2 thinking in psychology. All these capabilities are fundamental to the success of humans at high-level reasoning and planning. Therefore, to address the limitations of traditional autoregressive models lacking these human-like capabilities, we introduce Energy-Based World Models (EBWM). EBWM involves training an Energy-Based Model (EBM) to predict the compatibility of a given context and a predicted future state. In doing so, EBWM enables models to achieve all three facets of human cognition described. Moreover, we developed a variant of the traditional autoregressive transformer tailored for Energy-Based models, termed the Energy-Based Transformer (EBT). Our results demonstrate that EBWM scales better with data and GPU Hours than traditional autoregressive transformers in CV, and that EBWM offers promising early scaling in NLP. Consequently, this approach offers an exciting path toward training future models capable of System 2 thinking and intelligently searching across state spaces.

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/transformer_arch.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/rnn_arch.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/diffusion_arch.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/ebwm_arch.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/proposed_model.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x1.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x2.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x3.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x4.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x5.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x6.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x7.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x8.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/x9.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/early_scaling_mcmc_condition.png)

![受认知启发的基于能量的世界观](../../../paper_images/2406.08862/late_scaling_mcmc_condition.png)

[Arxiv](https://arxiv.org/abs/2406.08862)