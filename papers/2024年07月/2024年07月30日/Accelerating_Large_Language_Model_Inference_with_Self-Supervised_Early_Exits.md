# 通过自监督早期退出技术，加速大型语言模型的推理过程。

发布时间：2024年07月30日

`LLM应用` `人工智能` `语言处理`

> Accelerating Large Language Model Inference with Self-Supervised Early Exits

# 摘要

> 本文介绍了一种新颖的方法，通过在推理时提前退出，加速大型预训练语言模型的运行。鉴于这些模型在多种应用中的高计算需求，我们的策略利用了令牌复杂度的自然变化，有选择地加快推理速度。具体而言，我们在现有变换器层上添加了早期退出机制，这些机制根据置信度指标决定是否提前终止。这些机制通过模型自身的预测进行自监督训练，无需额外标注数据。通过校准集设定的置信度指标，既保证了准确性，又允许在置信度足够时提前结束。这种方法不仅保留了原始模型的准确性，还缩短了某些任务的计算时间，且无需大规模重新训练。这种轻巧且模块化的改进，有望显著提升LLM在资源有限环境下实时语言处理等应用的实用性。

> This paper presents a novel technique for accelerating inference in large, pre-trained language models (LLMs) by introducing early exits during inference. The computational demands of these models, used across a wide range of applications, can be substantial. By capitalizing on the inherent variability in token complexity, our approach enables selective acceleration of the inference process. Specifically, we propose the integration of early exit ''heads'' atop existing transformer layers, which facilitate conditional terminations based on a confidence metric. These heads are trained in a self-supervised manner using the model's own predictions as training data, thereby eliminating the need for additional annotated data. The confidence metric, established using a calibration set, ensures a desired level of accuracy while enabling early termination when confidence exceeds a predetermined threshold. Notably, our method preserves the original accuracy and reduces computational time on certain tasks, leveraging the existing knowledge of pre-trained LLMs without requiring extensive retraining. This lightweight, modular modification has the potential to greatly enhance the practical usability of LLMs, particularly in applications like real-time language processing in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2407.21082)