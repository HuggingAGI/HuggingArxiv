# 多模态 LLM 中的计算跳跃

发布时间：2024年10月12日

`LLM理论` `人工智能` `计算机视觉`

> Skipping Computations in Multimodal LLMs

# 摘要

> 大型语言模型 (LLM) 在文本和多模态领域取得了显著成就，但这些成就往往伴随着高昂的计算成本，尤其是在处理多模态长序列输入时。为此，我们研究了多模态大型语言模型 (MLLM) 在推理过程中的计算冗余，提出了跳过整个块、FFN 或自注意力 (SA) 层等方法，并探索了层并行化。研究结果表明，在推理时可以大幅减少计算量，特别是在视觉问答 (VQA) 等任务中；训练时跳过计算可恢复 97% 的性能，即使跳过一半的块或移除 70% 的权重；使用较小的 LLM 进行适当训练也能达到与大 2 或 3 倍的 LLM 相当的性能。此外，我们将研究扩展到最新的 MLLM，如 LLaVA-1.5，发现了类似的现象。这表明 MLLM 内部存在冗余计算，有望在不牺牲性能的情况下显著降低推理成本。代码已公开：https://github.com/mshukor/ima-lmms。

> Large Language Models (LLMs) have demonstrated remarkable success in both textual and multimodal domains. However, this success often comes with substantial computational costs, particularly when handling lengthy sequences of multimodal inputs. This has sparked many efforts focusing on enhancing efficiency during training and inference. In this study, we investigate the computation redundancy in Multimodal Large Language Models (MLLMs) during inference. We propose different methods to skip computations, such as skipping entire blocks, FFN or self-attention (SA) layers. Additionally, we explore parallelizing certain layers, such as FFN and SA layers. Our findings validate that (1) significant amount of computations can be avoided at inference time, especially for tasks such as Visual Question Answering (VQA). (2) Skipping computations during training can recover 97% of the original performance, even when skipping half of the blocks or removing 70% of the weights. Alternatively, (3) properly training with smaller LLMs can yield comparable performance to LLMs 2 or 3 times larger. To conclude, we extend our investigation to recent MLLMs, such as LLaVA-1.5, showing similar observations. Our work show that there is redundant computations inside MLLMs and thus the potential for significantly improving inference costs without sacrificing performance. The code is available here: https://github.com/mshukor/ima-lmms.

[Arxiv](https://arxiv.org/abs/2410.09454)