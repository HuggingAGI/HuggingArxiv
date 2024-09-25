# 利用专家混合增强的语音条件LLM，提升代码切换ASR性能。

发布时间：2024年09月24日

`LLM应用` `语音识别` `自动语音识别`

> Boosting Code-Switching ASR with Mixture of Experts Enhanced Speech-Conditioned LLM

# 摘要

> 本文介绍了一种结合语音条件和专家混合（MoE）的连接器，用于解决自动语音识别（ASR）中的代码切换（CS）问题。我们提出了插入和删除中断标记（IDIT）机制，以提升LLM在语音识别任务中的文本生成能力。同时，我们设计了一个高效的MoE架构连接器，能够处理多语言。为增强专家协作和LLM的理解力，我们采用了两阶段渐进训练策略：首先，解冻连接器并结合语言专家进行训练，将语音映射到文本；其次，结合IDIT机制和所有专家，训练连接器和LLM适配器，学习通用表示。实验证明，我们的方法在性能上显著超越了现有最先进的端到端和大规模音频-语言模型。

> In this paper, we introduce a speech-conditioned Large Language Model (LLM) integrated with a Mixture of Experts (MoE) based connector to address the challenge of Code-Switching (CS) in Automatic Speech Recognition (ASR). Specifically, we propose an Insertion and Deletion of Interruption Token (IDIT) mechanism for better transfer text generation ability of LLM to speech recognition task. We also present a connecter with MoE architecture that manages multiple languages efficiently. To further enhance the collaboration of multiple experts and leverage the understanding capabilities of LLM, we propose a two-stage progressive training strategy: 1) The connector is unfrozen and trained with language-specialized experts to map speech representations to the text space. 2) The connector and LLM LoRA adaptor are trained with the proposed IDIT mechanism and all experts are activated to learn general representations. Experimental results demonstrate that our method significantly outperforms state-of-the-art models, including end-to-end and large-scale audio-language models.

[Arxiv](https://arxiv.org/abs/2409.15905)