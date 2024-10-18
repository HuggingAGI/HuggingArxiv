# 活跃与休眠的注意力头：揭秘 LLM 中的极端标记现象

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Active-Dormant Attention Heads: Mechanistically Demystifying Extreme-Token Phenomena in LLMs

# 摘要

> 在基于transformer的LLM中，从业者发现了三个令人费解的现象：注意力下沉、价值流失和残差峰值，统称为极端标记现象。这些现象表现为某些“下沉标记”获得异常高的注意力权重，价值状态显著减小，残差范数远超其他标记，给LLM的推理、量化和解释性带来挑战。我们深入探讨了这些现象的成因。首先，我们发现这些现象甚至在简单的transformer架构（一到三层）和基础任务（Bigram-Backcopy，BB任务）中就已显现。通过分析，我们揭示了一种活跃-休眠机制，即注意力头在特定输入下成为下沉点，而在其他输入下则保持正常。理论分析表明，这些现象源于相互强化机制。基于此，我们提出在预训练中缓解这些现象的方法，如用ReLU替代softmax，用SGD替代Adam。进一步，我们将研究扩展至预训练的LLM（如Llama和OLMo），发现许多注意力头同样表现出活跃-休眠机制，且相互强化机制在LLM预训练中也起主导作用。研究结果显示，BB任务预测的极端标记现象属性与预训练LLM的实际观察高度吻合。

> Practitioners have consistently observed three puzzling phenomena in transformer-based large language models (LLMs): attention sinks, value-state drains, and residual-state peaks, collectively referred to as extreme-token phenomena. These phenomena are characterized by certain so-called "sink tokens" receiving disproportionately high attention weights, exhibiting significantly smaller value states, and having much larger residual-state norms than those of other tokens. These extreme tokens give rise to various challenges in LLM inference, quantization, and interpretability.
  We elucidate the mechanisms behind extreme-token phenomena. First, we show that these phenomena arise in very simple architectures -- transformers with one to three layers -- trained on a toy model, the Bigram-Backcopy (BB) task. In this setting, we identify an active-dormant mechanism, where attention heads become sinks for specific input domains while remaining non-sinks for others. Our theoretical analysis of the training dynamics reveals that these phenomena are driven by a mutual reinforcement mechanism. Building on these insights, we propose strategies to mitigate extreme-token phenomena during pretraining, including replacing softmax with ReLU and Adam with SGD. Next, we extend our analysis to pretrained LLMs, including Llama and OLMo, showing that many attention heads exhibit a similar active-dormant mechanism as in the BB task, and that the mutual reinforcement mechanism also governs the emergence of extreme-token phenomena during LLM pretraining. Our results reveal that many of the static and dynamic properties of extreme-token phenomena predicted by the BB task align with observations in pretrained LLMs.

[Arxiv](https://arxiv.org/abs/2410.13835)