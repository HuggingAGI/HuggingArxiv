# 多模态大型语言模型中的计算跳跃

发布时间：2024年10月12日

`LLM理论` `人工智能` `计算机视觉`

> Skipping Computations in Multimodal LLMs

# 摘要

> 大型语言模型 (LLM) 在文本和多模态领域表现出色，但处理多模态长序列时计算成本高昂。本研究探讨了多模态大型语言模型 (MLLM) 推理中的计算冗余，提出跳过整个块、FFN 或自注意力 (SA) 层等方法，并探索层并行化。研究发现：(1) 推理时可大幅减少计算，尤其在视觉问答 (VQA) 任务中；(2) 训练时跳过计算可恢复 97% 性能，即使跳过一半块或移除 70% 权重；(3) 小 LLM 适当训练可媲美大 2-3 倍 LLM 的性能。研究还扩展至 LLaVA-1.5 等 MLLM，发现类似现象。研究表明，MLLM 存在冗余计算，有望在不牺牲性能的情况下显著降低推理成本。代码见：https://github.com/mshukor/ima-lmms。

> Large Language Models (LLMs) have demonstrated remarkable success in both textual and multimodal domains. However, this success often comes with substantial computational costs, particularly when handling lengthy sequences of multimodal inputs. This has sparked many efforts focusing on enhancing efficiency during training and inference. In this study, we investigate the computation redundancy in Multimodal Large Language Models (MLLMs) during inference. We propose different methods to skip computations, such as skipping entire blocks, FFN or self-attention (SA) layers. Additionally, we explore parallelizing certain layers, such as FFN and SA layers. Our findings validate that (1) significant amount of computations can be avoided at inference time, especially for tasks such as Visual Question Answering (VQA). (2) Skipping computations during training can recover 97% of the original performance, even when skipping half of the blocks or removing 70% of the weights. Alternatively, (3) properly training with smaller LLMs can yield comparable performance to LLMs 2 or 3 times larger. To conclude, we extend our investigation to recent MLLMs, such as LLaVA-1.5, showing similar observations. Our work show that there is redundant computations inside MLLMs and thus the potential for significantly improving inference costs without sacrificing performance. The code is available here: https://github.com/mshukor/ima-lmms.

[Arxiv](https://arxiv.org/abs/2410.09454)